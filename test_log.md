#### Test 113351851f4ec514 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-07-20 12:50:01 - INFO HttpServer: 'listening on *:3000'

2017-07-20 12:50:03 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'eb443dac-3bf6-4f18-accb-2bfba7c1dbd2', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 12:50:03 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-07-20 12:50:05 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'eb443dac-3bf6-4f18-accb-2bfba7c1dbd2', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 12:50:05 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: 'eb443dac-3bf6-4f18-accb-2bfba7c1dbd2', platformName: 'ios''

2017-07-20 12:50:07 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '8b1a52f9-1a49-4994-bc93-4785b998d2dc', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 12:50:07 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-07-20 12:50:07 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6sPlus-1', uuid: '9b85ac8e-ac7f-41c0-8589-fb7e6dbb81ef', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 12:50:07 - DEBUG TestFramework: 'device added, name: 'Apple-Iphone6sPlus-1''

2017-07-20 12:50:07 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-07-20 12:50:07 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-07-20 12:50:07 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-20 12:50:09 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-20 12:50:09 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-20 12:50:09 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '8b1a52f9-1a49-4994-bc93-4785b998d2dc', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 12:50:09 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: '8b1a52f9-1a49-4994-bc93-4785b998d2dc', platformName: 'ios''

2017-07-20 12:50:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-20 12:50:09 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-20 12:50:09 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6sPlus-1', uuid: '9b85ac8e-ac7f-41c0-8589-fb7e6dbb81ef', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 12:50:09 - INFO TestFramework: 'updating existing device, name: 'Apple-Iphone6sPlus-1', uuid: '9b85ac8e-ac7f-41c0-8589-fb7e6dbb81ef', platformName: 'ios''

2017-07-20 12:50:09 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-20 12:50:09 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-20 12:50:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-20 12:50:10 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-20 12:50:10 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-20 12:50:10 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-20 12:50:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-20 12:50:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-20 12:50:11 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-20 12:50:11 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:50:11 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:50:11 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:50:11 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:50:11 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:50:13 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''
2017-07-20 12:50:13 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:50:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:50:14 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:50:14 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:50:14 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:50:14 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:50:14 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:50:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:50:15 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:50:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-20 12:50:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-20 12:50:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-20 12:50:15 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:50:15 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:50:16 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:50:16 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:50:17 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:50:17 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:50:17 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:50:17 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:50:17 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:50:17 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:50:17 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:50:18 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:50:18 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:50:18 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:50:18 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:50:18 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:50:18 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:50:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:50:19 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:50:19 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:50:19 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:50:19 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:50:19 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:50:19 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:50:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:50:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:50:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:50:19 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:50:19 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:50:19 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:50:19 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-20 12:50:20 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-20 12:50:20 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-20 12:50:20 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-20 12:50:20 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-20 12:50:21 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-20 12:50:21 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-20 12:50:22 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-20 12:50:22 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-20 12:50:23 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-20 12:50:23 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-20 12:50:23 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-20 12:50:23 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-20 12:50:23 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-20 12:50:23 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-20 12:50:23 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-20 12:50:23 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-20 12:50:23 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-20 12:50:23 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-20 12:50:24 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-20 12:50:24 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-20 12:50:24 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-20 12:50:24 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-20 12:50:24 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-20 12:50:24 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-20 12:50:24 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-20 12:50:24 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-20 12:50:24 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-20 12:50:24 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-20 12:50:25 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-20 12:50:25 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-20 12:50:25 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-20 12:50:25 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-20 12:50:25 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-20 12:50:25 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-20 12:50:25 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-20 12:50:25 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-20 12:50:25 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-20 12:50:25 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-20 12:50:27 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-20 12:50:27 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-20 12:50:28 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-20 12:50:29 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-20 12:50:29 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-20 12:50:29 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-20 12:50:29 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-20 12:50:29 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-20 12:50:29 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-20 12:50:31 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-20 12:50:31 - DEBUG UnitTestFramework: '#run ok: 'another skip''
2017-07-20 12:50:31 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-20 12:50:32 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-20 12:50:32 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-20 12:50:32 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-20 12:50:32 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-20 12:50:32 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-20 12:50:32 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-20 12:50:32 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-20 12:50:32 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-20 12:50:32 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-20 12:50:32 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-20 12:50:33 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-20 12:50:34 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-20 12:50:34 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-20 12:50:34 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-20 12:50:34 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-20 12:50:34 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-20 12:50:34 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-20 12:50:34 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-20 12:50:34 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-20 12:50:34 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-20 12:50:34 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-20 12:50:35 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-20 12:50:35 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-20 12:50:35 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-20 12:50:35 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-20 12:50:37 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-20 12:50:37 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-20 12:50:37 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-20 12:50:37 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-20 12:50:38 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-20 12:50:38 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-20 12:50:40 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-20 12:50:40 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-20 12:50:40 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-20 12:50:40 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-20 12:50:40 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-20 12:50:40 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-20 12:50:40 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-20 12:50:40 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-20 12:50:40 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-20 12:50:41 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-20 12:50:41 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-20 12:50:41 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-20 12:50:41 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-20 12:50:41 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-20 12:50:41 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-20 12:50:41 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-20 12:50:41 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-20 12:50:41 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-20 12:50:42 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-20 12:50:42 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:50:42 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:50:42 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:50:43 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:50:43 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:50:44 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:50:44 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:50:47 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:50:47 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:50:49 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:50:49 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:50:50 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:50:50 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:50:52 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:50:52 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:50:52 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:50:52 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:50:53 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:50:53 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:50:54 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:50:54 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:50:55 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:50:55 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:50:56 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:50:56 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:50:56 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:50:56 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:50:57 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:50:57 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:50:57 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:50:57 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:50:57 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:50:57 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:50:58 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:50:58 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:51:00 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:51:00 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-20 12:51:02 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-20 12:51:02 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-20 12:51:03 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-20 12:51:03 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-20 12:51:04 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-20 12:51:04 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-20 12:51:04 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-20 12:51:04 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-20 12:51:14 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-20 12:51:14 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-20 12:51:14 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-20 12:51:14 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-20 12:51:14 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-20 12:51:14 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-20 12:51:29 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'd439ea7f-e10e-4d5f-8ac3-c286daf51c8d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 12:51:29 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-20 12:51:32 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-20 12:51:32 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-20 12:51:33 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-20 12:51:33 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-20 12:51:33 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-20 12:51:33 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-20 12:51:44 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '4853b810-73dc-48d1-9738-4cbf9ba00737', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 12:51:44 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-20 12:51:59 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-20 12:51:59 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-20 12:52:00 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-20 12:52:00 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-20 12:52:00 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-20 12:52:00 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-20 12:52:16 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-20 12:52:16 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-20 12:52:16 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-20 12:52:16 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-20 12:52:16 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-20 12:52:16 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-20 12:52:32 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-20 12:52:32 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-20 12:52:33 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-20 12:52:33 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:52:33 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:52:33 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:52:38 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:52:38 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:52:38 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:52:38 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-20 12:52:38 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-20 12:52:38 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-20 12:52:39 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-20 12:52:39 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-20 12:52:39 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:52:39 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-07-20 12:52:39 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-07-20 12:52:39 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:52:39 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:52:40 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:52:40 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:52:40 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:52:40 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:52:40 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-20 12:52:40 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-20 12:52:40 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-20 12:52:40 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:52:40 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:52:40 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:52:40 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:52:40 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:52:40 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:52:40 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:52:40 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:52:41 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:52:41 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:52:41 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:52:41 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:52:41 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:52:41 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:52:41 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:52:42 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:52:42 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:52:42 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:52:42 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:52:42 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 12:52:42 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 12:52:42 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 12:52:43 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 12:52:43 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 12:52:43 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect with illegal peerID''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect with illegal peerID''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect with illegal peerID''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect with illegal peerID''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect with illegal peerID''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect with illegal peerID''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#setup: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#setup ok: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-20 12:52:43 - DEBUG UnitTestFramework: '#run: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-20 12:52:44 - INFO Socket: 'run skipped, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID''

2017-07-20 12:52:44 - INFO Socket: 'run skipped, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID''

2017-07-20 12:52:44 - INFO Socket: 'run skipped, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID''

2017-07-20 12:52:44 - DEBUG UnitTestFramework: '#run ok: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-20 12:52:44 - DEBUG UnitTestFramework: '#teardown: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-20 12:52:44 - DEBUG UnitTestFramework: '#teardown ok: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-20 12:52:44 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect with invalid syncValue''

2017-07-20 12:52:44 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect with invalid syncValue''

2017-07-20 12:52:44 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect with invalid syncValue''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect with invalid syncValue''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect with invalid syncValue''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect with invalid syncValue''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#setup: 'cannot call disconnect with invalid peer id''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#setup ok: 'cannot call disconnect with invalid peer id''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#run: 'cannot call disconnect with invalid peer id''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#run ok: 'cannot call disconnect with invalid peer id''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#teardown: 'cannot call disconnect with invalid peer id''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call disconnect with invalid peer id''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#setup: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#setup ok: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-20 12:52:45 - DEBUG UnitTestFramework: '#run: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-20 12:52:46 - DEBUG UnitTestFramework: '#run ok: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-20 12:52:46 - DEBUG UnitTestFramework: '#teardown: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-20 12:52:46 - DEBUG UnitTestFramework: '#teardown ok: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-20 12:52:46 - DEBUG UnitTestFramework: '#setup: 'Get same port when trying to connect multiple times on iOS''

2017-07-20 12:52:47 - DEBUG UnitTestFramework: '#setup ok: 'Get same port when trying to connect multiple times on iOS''

2017-07-20 12:52:47 - DEBUG UnitTestFramework: '#run: 'Get same port when trying to connect multiple times on iOS''

2017-07-20 12:52:59 - DEBUG UnitTestFramework: '#run ok: 'Get same port when trying to connect multiple times on iOS''

2017-07-20 12:52:59 - DEBUG UnitTestFramework: '#teardown: 'Get same port when trying to connect multiple times on iOS''

2017-07-20 12:52:59 - DEBUG UnitTestFramework: '#teardown ok: 'Get same port when trying to connect multiple times on iOS''

2017-07-20 12:52:59 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-07-20 12:52:59 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-07-20 12:52:59 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-07-20 12:52:59 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-20 12:52:59 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-20 12:52:59 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-20 12:52:59 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-07-20 12:52:59 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-07-20 12:53:00 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-07-20 12:53:00 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-07-20 12:53:00 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-07-20 12:53:00 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-07-20 12:53:01 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-20 12:53:01 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-20 12:53:01 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-07-20 12:53:01 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-20 12:53:01 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-20 12:53:01 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-07-20 12:53:01 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-20 12:53:01 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-20 12:53:01 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-07-20 12:53:01 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-07-20 12:53:02 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-20 12:53:02 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-20 12:53:02 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#run: 'no peer discovery''

2017-07-20 12:53:02 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-20 12:53:02 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-20 12:53:02 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-07-20 12:53:02 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-07-20 12:53:03 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 12:53:04 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 12:53:05 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 12:53:06 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 12:53:06 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 12:53:07 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-07-20 12:53:08 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#setup: 'Single local http request''

2017-07-20 12:53:09 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '4c71869b-df56-443b-b756-1af524e6858c', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-20 12:53:09 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-07-20 12:53:09 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#setup ok: 'Single local http request''

2017-07-20 12:53:09 - DEBUG UnitTestFramework: '#run: 'Single local http request''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#run ok: 'Single local http request''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#teardown: 'Single local http request''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#teardown ok: 'Single local http request''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#setup: 'Single coordinated request ios native''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#setup ok: 'Single coordinated request ios native''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#run: 'Single coordinated request ios native''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:53:10 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:53:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-20 12:53:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-20 12:53:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:53:11 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:53:11 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:53:11 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-20 12:53:11 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:53:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:53:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:53:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:53:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:53:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:53:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-20 12:53:12 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-20 12:53:13 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-20 12:53:14 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''
2017-07-20 12:53:14 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-20 12:53:17 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-20 12:53:17 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-20 12:53:18 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-20 12:53:18 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-20 12:53:20 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-20 12:53:20 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-20 12:53:21 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-20 12:53:21 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-20 12:53:23 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-20 12:53:23 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-20 12:53:24 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-20 12:53:24 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-20 12:53:27 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-20 12:53:27 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-20 12:53:27 - DEBUG UnitTestFramework: '#run ok: 'Single coordinated request ios native''

2017-07-20 12:53:27 - DEBUG UnitTestFramework: '#teardown: 'Single coordinated request ios native''

2017-07-20 12:53:28 - DEBUG UnitTestFramework: '#teardown ok: 'Single coordinated request ios native''

2017-07-20 12:53:28 - DEBUG UnitTestFramework: '#setup: 'Multiple local http requests''

2017-07-20 12:53:28 - DEBUG UnitTestFramework: '#setup ok: 'Multiple local http requests''

2017-07-20 12:53:28 - DEBUG UnitTestFramework: '#run: 'Multiple local http requests''

2017-07-20 12:53:28 - DEBUG UnitTestFramework: '#run ok: 'Multiple local http requests''

2017-07-20 12:53:28 - DEBUG UnitTestFramework: '#teardown: 'Multiple local http requests''

2017-07-20 12:53:29 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple local http requests''

2017-07-20 12:53:29 - DEBUG UnitTestFramework: '#setup: 'Multiple coordinated request ios native''

2017-07-20 12:53:29 - DEBUG UnitTestFramework: '#setup ok: 'Multiple coordinated request ios native''

2017-07-20 12:53:29 - DEBUG UnitTestFramework: '#run: 'Multiple coordinated request ios native''

2017-07-20 12:53:31 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-20 12:53:31 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-20 12:53:35 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-20 12:53:35 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-20 12:53:37 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-20 12:53:37 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-20 12:53:39 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-20 12:53:39 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-20 12:53:41 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-20 12:53:41 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-20 12:53:43 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-20 12:53:43 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-20 12:53:44 - DEBUG UnitTestFramework: '#run ok: 'Multiple coordinated request ios native''

2017-07-20 12:53:44 - DEBUG UnitTestFramework: '#teardown: 'Multiple coordinated request ios native''

2017-07-20 12:53:45 - DEBUG UnitTestFramework: '#teardown ok: 'Multiple coordinated request ios native''

2017-07-20 12:53:45 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:53:45 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:53:45 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:53:45 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-20 12:53:45 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:53:46 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:53:47 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:53:48 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:53:48 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:53:48 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:53:48 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:53:48 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:53:48 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:53:49 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:53:49 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:53:49 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:53:49 - DEBUG UnitTestFramework: '#setup: 'can get the network status before starting''

2017-07-20 12:53:49 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-20 12:53:49 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-20 12:53:49 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status before starting''

2017-07-20 12:53:49 - DEBUG UnitTestFramework: '#run: 'can get the network status before starting''

2017-07-20 12:53:49 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-20 12:53:49 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-20 12:53:50 - DEBUG UnitTestFramework: '#run ok: 'can get the network status before starting''

2017-07-20 12:53:50 - DEBUG UnitTestFramework: '#teardown: 'can get the network status before starting''

2017-07-20 12:53:50 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status before starting''

2017-07-20 12:53:50 - DEBUG UnitTestFramework: '#setup: 'error returned with bad router''

2017-07-20 12:53:50 - DEBUG UnitTestFramework: '#setup ok: 'error returned with bad router''

2017-07-20 12:53:50 - DEBUG UnitTestFramework: '#run: 'error returned with bad router''

2017-07-20 12:53:50 - DEBUG UnitTestFramework: '#run ok: 'error returned with bad router''

2017-07-20 12:53:50 - DEBUG UnitTestFramework: '#teardown: 'error returned with bad router''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#teardown ok: 'error returned with bad router''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#setup: 'all services are started when we call start''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#setup ok: 'all services are started when we call start''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#run: 'all services are started when we call start''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#run ok: 'all services are started when we call start''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#teardown: 'all services are started when we call start''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#teardown ok: 'all services are started when we call start''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#setup: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#setup ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#run: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#run ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#teardown: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#teardown ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-07-20 12:53:51 - DEBUG UnitTestFramework: '#setup: 'all services are stopped when we call stop''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#setup ok: 'all services are stopped when we call stop''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#run: 'all services are stopped when we call stop''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#run ok: 'all services are stopped when we call stop''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#teardown: 'all services are stopped when we call stop''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#teardown ok: 'all services are stopped when we call stop''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is properly hooked up''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is properly hooked up''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is properly hooked up''

2017-07-20 12:53:52 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is properly hooked up', event: 'run_make sure terminateConnection is properly hooked up''

2017-07-20 12:53:52 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is properly hooked up', event: 'run_make sure terminateConnection is properly hooked up''

2017-07-20 12:53:52 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is properly hooked up', event: 'run_make sure terminateConnection is properly hooked up''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is properly hooked up''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is properly hooked up''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is properly hooked up''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-20 12:53:52 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is properly hooked up''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is properly hooked up''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is properly hooked up''

2017-07-20 12:53:53 - INFO Socket: 'run skipped, test: 'make sure terminateListener is properly hooked up', event: 'run_make sure terminateListener is properly hooked up''

2017-07-20 12:53:53 - INFO Socket: 'run skipped, test: 'make sure terminateListener is properly hooked up', event: 'run_make sure terminateListener is properly hooked up''

2017-07-20 12:53:53 - INFO Socket: 'run skipped, test: 'make sure terminateListener is properly hooked up', event: 'run_make sure terminateListener is properly hooked up''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is properly hooked up''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is properly hooked up''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is properly hooked up''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is return error if we get called on iOS''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-20 12:53:53 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is return error if we get called on iOS''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is return error if we get called on iOS''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is return error if we get called on iOS''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#setup: 'make sure we actually call kill connections properly''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#setup ok: 'make sure we actually call kill connections properly''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#run: 'make sure we actually call kill connections properly''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#run ok: 'make sure we actually call kill connections properly''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#teardown: 'make sure we actually call kill connections properly''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#teardown ok: 'make sure we actually call kill connections properly''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-20 12:53:54 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-20 12:53:54 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-20 12:53:54 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-20 12:53:55 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-20 12:53:55 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-20 12:53:55 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-20 12:53:55 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-20 12:53:55 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-20 12:53:55 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-07-20 12:53:55 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-20 12:53:55 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-20 12:53:55 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-20 12:53:56 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager', event: 'run_We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-20 12:53:56 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager', event: 'run_We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-20 12:53:56 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager', event: 'run_We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:56 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#setup: 'make sure bad PSK connections fail''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#setup ok: 'make sure bad PSK connections fail''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#run: 'make sure bad PSK connections fail''

2017-07-20 12:53:57 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-20 12:53:57 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-20 12:53:57 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#run ok: 'make sure bad PSK connections fail''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#teardown: 'make sure bad PSK connections fail''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#teardown ok: 'make sure bad PSK connections fail''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#setup: 'peer changes handled from a queue''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#setup ok: 'peer changes handled from a queue''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#run: 'peer changes handled from a queue''

2017-07-20 12:53:57 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-20 12:53:57 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-20 12:53:57 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#run ok: 'peer changes handled from a queue''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#teardown: 'peer changes handled from a queue''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#teardown ok: 'peer changes handled from a queue''

2017-07-20 12:53:57 - DEBUG UnitTestFramework: '#setup: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#setup ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#run: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-20 12:53:58 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-20 12:53:58 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-20 12:53:58 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#run ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#teardown: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#teardown ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-20 12:53:58 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-20 12:53:58 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-20 12:53:58 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#setup: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#setup ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#run: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-20 12:53:58 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-20 12:53:58 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-20 12:53:59 - DEBUG UnitTestFramework: '#run ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-20 12:53:59 - DEBUG UnitTestFramework: '#teardown: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-07-20 12:53:59 - DEBUG UnitTestFramework: '#teardown ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''
2017-07-20 12:53:59 - DEBUG UnitTestFramework: '#setup: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-20 12:53:59 - DEBUG UnitTestFramework: '#setup ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-20 12:53:59 - DEBUG UnitTestFramework: '#run: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-20 12:53:59 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#run ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#teardown: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#teardown ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#setup: 'can do HTTP requests between peers''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#setup ok: 'can do HTTP requests between peers''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#run: 'can do HTTP requests between peers''

2017-07-20 12:54:00 - INFO Socket: 'run skipped, test: 'can do HTTP requests between peers', event: 'run_can do HTTP requests between peers''

2017-07-20 12:54:00 - INFO Socket: 'run skipped, test: 'can do HTTP requests between peers', event: 'run_can do HTTP requests between peers''

2017-07-20 12:54:00 - INFO Socket: 'run skipped, test: 'can do HTTP requests between peers', event: 'run_can do HTTP requests between peers''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#run ok: 'can do HTTP requests between peers''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#teardown: 'can do HTTP requests between peers''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#teardown ok: 'can do HTTP requests between peers''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#setup: 'can still do HTTP requests between peers with coordinator''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#setup ok: 'can still do HTTP requests between peers with coordinator''

2017-07-20 12:54:00 - DEBUG UnitTestFramework: '#run: 'can still do HTTP requests between peers with coordinator''

2017-07-20 12:54:01 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-20 12:54:01 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-20 12:54:01 - INFO Socket: 'run skipped, test: 'can still do HTTP requests between peers with coordinator', event: 'run_can still do HTTP requests between peers with coordinator''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#run ok: 'can still do HTTP requests between peers with coordinator''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#teardown: 'can still do HTTP requests between peers with coordinator''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#teardown ok: 'can still do HTTP requests between peers with coordinator''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#setup: 'calls correct starts when network changes''

2017-07-20 12:54:01 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#setup ok: 'calls correct starts when network changes''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#run: 'calls correct starts when network changes''

2017-07-20 12:54:01 - INFO Socket: 'run skipped, test: 'calls correct starts when network changes', event: 'run_calls correct starts when network changes''

2017-07-20 12:54:01 - INFO Socket: 'run skipped, test: 'calls correct starts when network changes', event: 'run_calls correct starts when network changes''

2017-07-20 12:54:01 - INFO Socket: 'run skipped, test: 'calls correct starts when network changes', event: 'run_calls correct starts when network changes''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#run ok: 'calls correct starts when network changes''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#teardown: 'calls correct starts when network changes''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#teardown ok: 'calls correct starts when network changes''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#setup: 'test to coordinate connection cut''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#setup ok: 'test to coordinate connection cut''

2017-07-20 12:54:01 - DEBUG UnitTestFramework: '#run: 'test to coordinate connection cut''

2017-07-20 12:54:02 - DEBUG UnitTestFramework: '#run ok: 'test to coordinate connection cut''

2017-07-20 12:54:02 - DEBUG UnitTestFramework: '#teardown: 'test to coordinate connection cut''

2017-07-20 12:54:02 - DEBUG UnitTestFramework: '#teardown ok: 'test to coordinate connection cut''

2017-07-20 12:54:02 - DEBUG UnitTestFramework: '#setup: 'can do HTTP requests after connections are cut''

2017-07-20 12:54:02 - DEBUG UnitTestFramework: '#setup ok: 'can do HTTP requests after connections are cut''

2017-07-20 12:54:02 - DEBUG UnitTestFramework: '#run: 'can do HTTP requests after connections are cut''

2017-07-20 12:54:02 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-20 12:54:02 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-20 12:54:05 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-20 12:54:05 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-20 12:54:05 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-20 12:54:05 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-20 12:54:06 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-20 12:54:06 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-20 12:54:06 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-20 12:54:08 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-20 12:54:08 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-20 12:54:08 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-20 12:54:08 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-20 12:54:09 - DEBUG UnitTestFramework: '#run ok: 'can do HTTP requests after connections are cut''

2017-07-20 12:54:09 - DEBUG UnitTestFramework: '#teardown: 'can do HTTP requests after connections are cut''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#teardown ok: 'can do HTTP requests after connections are cut''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#setup: 'will fail bad PSK connection between peers''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#setup ok: 'will fail bad PSK connection between peers''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#run: 'will fail bad PSK connection between peers''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#run ok: 'will fail bad PSK connection between peers''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#teardown: 'will fail bad PSK connection between peers''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#teardown ok: 'will fail bad PSK connection between peers''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#setup: 'We provide notification when a listener dies and we recreate it''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#setup ok: 'We provide notification when a listener dies and we recreate it''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#run: 'We provide notification when a listener dies and we recreate it''

2017-07-20 12:54:11 - INFO Socket: 'run skipped, test: 'We provide notification when a listener dies and we recreate it', event: 'run_We provide notification when a listener dies and we recreate it''

2017-07-20 12:54:11 - INFO Socket: 'run skipped, test: 'We provide notification when a listener dies and we recreate it', event: 'run_We provide notification when a listener dies and we recreate it''

2017-07-20 12:54:11 - INFO Socket: 'run skipped, test: 'We provide notification when a listener dies and we recreate it', event: 'run_We provide notification when a listener dies and we recreate it''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#run ok: 'We provide notification when a listener dies and we recreate it''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#teardown: 'We provide notification when a listener dies and we recreate it''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#teardown ok: 'We provide notification when a listener dies and we recreate it''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-20 12:54:11 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-20 12:54:12 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-20 12:54:12 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-20 12:54:12 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:54:12 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:54:13 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-07-20 12:54:13 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:54:13 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:54:13 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:54:13 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:54:13 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:54:13 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-07-20 12:54:13 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:54:13 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:54:13 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-20 12:54:14 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#setup: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#setup ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#run: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#run ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#teardown: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#teardown ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#setup: '#start should fail if called twice in a row''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#setup ok: '#start should fail if called twice in a row''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#run: '#start should fail if called twice in a row''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#run ok: '#start should fail if called twice in a row''

2017-07-20 12:54:15 - DEBUG UnitTestFramework: '#teardown: '#start should fail if called twice in a row''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#teardown ok: '#start should fail if called twice in a row''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#setup: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#setup ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#run: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 12:54:16 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 12:54:16 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 12:54:16 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#run ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#teardown: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#teardown ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#setup: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#setup ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#run: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 12:54:16 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 12:54:16 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 12:54:16 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#run ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#teardown: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#teardown ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#setup: 'does not send duplicate availability changes''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#setup ok: 'does not send duplicate availability changes''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#run: 'does not send duplicate availability changes''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#run ok: 'does not send duplicate availability changes''

2017-07-20 12:54:16 - DEBUG UnitTestFramework: '#teardown: 'does not send duplicate availability changes''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#teardown ok: 'does not send duplicate availability changes''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#setup: 'can get the network status''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#run: 'can get the network status''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#run ok: 'can get the network status''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#teardown: 'can get the network status''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 12:54:17 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#setup: 'native available - new peer is cached''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#setup ok: 'native available - new peer is cached''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#run: 'native available - new peer is cached''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#run ok: 'native available - new peer is cached''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#teardown: 'native available - new peer is cached''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#teardown ok: 'native available - new peer is cached''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#setup: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#run: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 12:54:18 - INFO Socket: 'run skipped, test: 'native available - peer with same port and different generation is cached (BLUETOOTH)', event: 'run_native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 12:54:18 - INFO Socket: 'run skipped, test: 'native available - peer with same port and different generation is cached (BLUETOOTH)', event: 'run_native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 12:54:18 - INFO Socket: 'run skipped, test: 'native available - peer with same port and different generation is cached (BLUETOOTH)', event: 'run_native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-07-20 12:54:18 - DEBUG UnitTestFramework: '#setup: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#run: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 12:54:19 - INFO Socket: 'run skipped, test: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)', event: 'run_native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 12:54:19 - INFO Socket: 'run skipped, test: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)', event: 'run_native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 12:54:19 - INFO Socket: 'run skipped, test: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)', event: 'run_native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#setup: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#run: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with greater generation is cached (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#setup: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#run: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#setup: 'native unavailable - new peer is ignored''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#setup ok: 'native unavailable - new peer is ignored''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#run: 'native unavailable - new peer is ignored''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#run ok: 'native unavailable - new peer is ignored''

2017-07-20 12:54:19 - DEBUG UnitTestFramework: '#teardown: 'native unavailable - new peer is ignored''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#teardown ok: 'native unavailable - new peer is ignored''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#setup: 'native unavailable - cached peer is removed''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#setup ok: 'native unavailable - cached peer is removed''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#run: 'native unavailable - cached peer is removed''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#run ok: 'native unavailable - cached peer is removed''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#teardown: 'native unavailable - cached peer is removed''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#teardown ok: 'native unavailable - cached peer is removed''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 12:54:20 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 12:54:20 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 12:54:20 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 12:54:20 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#setup: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#setup ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#run: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 12:54:21 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 12:54:21 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 12:54:21 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#run ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#teardown: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#teardown ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#setup: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#setup ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#run: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 12:54:21 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 12:54:21 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 12:54:21 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#run ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#teardown: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#teardown ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 12:54:21 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (TCP_NATIVE)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (BLUETOOTH)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (BLUETOOTH)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (BLUETOOTH)''

2017-07-20 12:54:22 - INFO Socket: 'run skipped, test: 'newAddressPort field (BLUETOOTH)', event: 'run_newAddressPort field (BLUETOOTH)''

2017-07-20 12:54:22 - INFO Socket: 'run skipped, test: 'newAddressPort field (BLUETOOTH)', event: 'run_newAddressPort field (BLUETOOTH)''

2017-07-20 12:54:22 - INFO Socket: 'run skipped, test: 'newAddressPort field (BLUETOOTH)', event: 'run_newAddressPort field (BLUETOOTH)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (BLUETOOTH)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (BLUETOOTH)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (BLUETOOTH)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (MPCF)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (MPCF)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (MPCF)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (MPCF)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (MPCF)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (MPCF)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#setup: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 12:54:22 - DEBUG UnitTestFramework: '#run: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 12:54:23 - INFO Socket: 'run skipped, test: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)', event: 'run_newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 12:54:23 - INFO Socket: 'run skipped, test: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)', event: 'run_newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 12:54:23 - INFO Socket: 'run skipped, test: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)', event: 'run_newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 12:54:23 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)', event: 'run_#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 12:54:23 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)', event: 'run_#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 12:54:23 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)', event: 'run_#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 12:54:23 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#setup: '#disconnect fails on wifi peers''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#setup ok: '#disconnect fails on wifi peers''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#run: '#disconnect fails on wifi peers''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#run ok: '#disconnect fails on wifi peers''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#teardown: '#disconnect fails on wifi peers''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#teardown ok: '#disconnect fails on wifi peers''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#setup: '#disconnect delegates native peers to the native wrapper''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#setup ok: '#disconnect delegates native peers to the native wrapper''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#run: '#disconnect delegates native peers to the native wrapper''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#run ok: '#disconnect delegates native peers to the native wrapper''

2017-07-20 12:54:24 - DEBUG UnitTestFramework: '#teardown: '#disconnect delegates native peers to the native wrapper''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#teardown ok: '#disconnect delegates native peers to the native wrapper''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#setup: 'network changes emitted correctly''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#setup ok: 'network changes emitted correctly''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#run: 'network changes emitted correctly''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#run ok: 'network changes emitted correctly''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#teardown: 'network changes emitted correctly''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#teardown ok: 'network changes emitted correctly''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in started state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in started state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in started state''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in started state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in started state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in started state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in stopped state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in stopped state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in stopped state''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in stopped state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in stopped state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in stopped state''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#setup: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#setup ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#run: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on Android', event: 'run_We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on Android', event: 'run_We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 12:54:25 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on Android', event: 'run_We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#run ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 12:54:25 - DEBUG UnitTestFramework: '#teardown: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#teardown ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#setup: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#setup ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#run: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 12:54:26 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 12:54:26 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 12:54:26 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#run ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#teardown: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#teardown ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#setup: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#setup ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#run: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 12:54:26 - INFO Socket: 'run skipped, test: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen', event: 'run_If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 12:54:26 - INFO Socket: 'run skipped, test: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen', event: 'run_If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 12:54:26 - INFO Socket: 'run skipped, test: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen', event: 'run_If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#run ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#teardown: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#teardown ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#setup: 'does not fire duplicate events after peer listener recreation''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#setup ok: 'does not fire duplicate events after peer listener recreation''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#run: 'does not fire duplicate events after peer listener recreation''

2017-07-20 12:54:26 - INFO Socket: 'run skipped, test: 'does not fire duplicate events after peer listener recreation', event: 'run_does not fire duplicate events after peer listener recreation''

2017-07-20 12:54:26 - INFO Socket: 'run skipped, test: 'does not fire duplicate events after peer listener recreation', event: 'run_does not fire duplicate events after peer listener recreation''

2017-07-20 12:54:26 - INFO Socket: 'run skipped, test: 'does not fire duplicate events after peer listener recreation', event: 'run_does not fire duplicate events after peer listener recreation''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#run ok: 'does not fire duplicate events after peer listener recreation''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#teardown: 'does not fire duplicate events after peer listener recreation''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#teardown ok: 'does not fire duplicate events after peer listener recreation''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#setup: '#stop should change peers''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#setup ok: '#stop should change peers''

2017-07-20 12:54:26 - DEBUG UnitTestFramework: '#run: '#stop should change peers''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#run ok: '#stop should change peers''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#teardown: '#stop should change peers''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#teardown ok: '#stop should change peers''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#setup: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#setup ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#run: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#run ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#teardown: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#teardown ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#setup: 'peer should be found once after listening and discovery started''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#setup ok: 'peer should be found once after listening and discovery started''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#run: 'peer should be found once after listening and discovery started''

2017-07-20 12:54:27 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-20 12:54:27 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-20 12:54:27 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#run ok: 'peer should be found once after listening and discovery started''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#teardown: 'peer should be found once after listening and discovery started''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#teardown ok: 'peer should be found once after listening and discovery started''

2017-07-20 12:54:27 - DEBUG UnitTestFramework: '#setup: 'can get data from all participants''

2017-07-20 12:54:28 - DEBUG UnitTestFramework: '#setup ok: 'can get data from all participants''

2017-07-20 12:54:28 - DEBUG UnitTestFramework: '#run: 'can get data from all participants''

2017-07-20 12:54:31 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-20 12:54:31 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-20 12:54:32 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-20 12:54:32 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-20 12:54:34 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-20 12:54:34 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-20 12:54:36 - DEBUG UnitTestFramework: '#run ok: 'can get data from all participants''

2017-07-20 12:54:36 - DEBUG UnitTestFramework: '#teardown: 'can get data from all participants''

2017-07-20 12:54:37 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-20 12:54:37 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-20 12:54:38 - DEBUG UnitTestFramework: '#teardown ok: 'can get data from all participants''

2017-07-20 12:54:38 - DEBUG UnitTestFramework: '#setup: 'test for data corruption''

2017-07-20 12:54:38 - DEBUG UnitTestFramework: '#setup ok: 'test for data corruption''

2017-07-20 12:54:38 - DEBUG UnitTestFramework: '#run: 'test for data corruption''

2017-07-20 12:54:38 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-20 12:54:38 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-20 12:54:38 - INFO Socket: 'run skipped, test: 'test for data corruption', event: 'run_test for data corruption''

2017-07-20 12:54:38 - DEBUG UnitTestFramework: '#run ok: 'test for data corruption''

2017-07-20 12:54:38 - DEBUG UnitTestFramework: '#teardown: 'test for data corruption''

2017-07-20 12:54:38 - DEBUG UnitTestFramework: '#teardown ok: 'test for data corruption''

2017-07-20 12:54:38 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - test getters''

2017-07-20 12:54:38 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - test getters''

2017-07-20 12:54:38 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - test getters''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - test getters''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - test getters''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - test getters''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - start and kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - start and kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - start and kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - start and kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - start and kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - start and kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - double start''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - double start''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - double start''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - double start''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - double start''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - double start''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - start after kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - start after kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - start after kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - start after kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - start after kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - start after kill''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 12:54:39 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - make sure ids are unique''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#setup: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#setup ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#run: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#run ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#teardown: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#teardown ok: '#testThaliPeerAction - check that forever agent can be destroyed''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#setup: 'Test PeerDictionary basic functionality''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerDictionary basic functionality''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#run: 'Test PeerDictionary basic functionality''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#run ok: 'Test PeerDictionary basic functionality''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#teardown: 'Test PeerDictionary basic functionality''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerDictionary basic functionality''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#setup: 'Test PeerDictionary with multiple entries.''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#setup ok: 'Test PeerDictionary with multiple entries.''

2017-07-20 12:54:40 - DEBUG UnitTestFramework: '#run: 'Test PeerDictionary with multiple entries.''

2017-07-20 12:54:41 - DEBUG UnitTestFramework: '#run ok: 'Test PeerDictionary with multiple entries.''

2017-07-20 12:54:41 - DEBUG UnitTestFramework: '#teardown: 'Test PeerDictionary with multiple entries.''

2017-07-20 12:54:41 - DEBUG UnitTestFramework: '#teardown ok: 'Test PeerDictionary with multiple entries.''

2017-07-20 12:54:41 - DEBUG UnitTestFramework: '#setup: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 12:54:41 - DEBUG UnitTestFramework: '#setup ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 12:54:41 - DEBUG UnitTestFramework: '#run: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 12:54:42 - DEBUG UnitTestFramework: '#run ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 12:54:42 - DEBUG UnitTestFramework: '#teardown: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 12:54:42 - DEBUG UnitTestFramework: '#teardown ok: 'RESOLVED entries are removed before WAITING state entry.''

2017-07-20 12:54:42 - DEBUG UnitTestFramework: '#setup: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 12:54:42 - DEBUG UnitTestFramework: '#setup ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 12:54:42 - DEBUG UnitTestFramework: '#run: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 12:54:42 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-20 12:54:42 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#run ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#teardown: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#teardown ok: 'WAITING entries are removed before CONTROLLED_BY_POOL state entry.''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#setup: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#setup ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#run: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#run ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#teardown: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#teardown ok: 'When CONTROLLED_BY_POOL entry is removed and kill is called.''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - single action''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - single action''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - single action''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - single action''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - single action''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - single action''

2017-07-20 12:54:43 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - multiple actions''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - PSK Pool works''

2017-07-20 12:54:44 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolDefault - stop''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolDefault - stop''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolDefault - stop''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolDefault - stop''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolDefault - stop''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolDefault - stop''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure that start verifies queue length''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - bad enqueues''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 12:54:45 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - do not allow same object type''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure we catch kill and dequeue''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent''

2017-07-20 12:54:46 - DEBUG UnitTestFramework: '#setup: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#setup ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#run: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#run ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#teardown: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#teardown ok: '#ThaliPeerPoolInterface - make sure that stop removes all actions''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#setup: 'We reject unrecognized connection type''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#setup ok: 'We reject unrecognized connection type''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#run: 'We reject unrecognized connection type''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#run ok: 'We reject unrecognized connection type''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#teardown: 'We reject unrecognized connection type''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#teardown ok: 'We reject unrecognized connection type''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#setup: 'We reject unrecognized action type''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#setup ok: 'We reject unrecognized action type''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#run: 'We reject unrecognized action type''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#run ok: 'We reject unrecognized action type''

2017-07-20 12:54:47 - DEBUG UnitTestFramework: '#teardown: 'We reject unrecognized action type''

2017-07-20 12:54:48 - DEBUG UnitTestFramework: '#teardown ok: 'We reject unrecognized action type''

2017-07-20 12:54:48 - DEBUG UnitTestFramework: '#setup: 'One action on bluetooth''

2017-07-20 12:54:48 - DEBUG UnitTestFramework: '#setup ok: 'One action on bluetooth''

2017-07-20 12:54:48 - DEBUG UnitTestFramework: '#run: 'One action on bluetooth''

2017-07-20 12:54:48 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-20 12:54:48 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-20 12:54:48 - DEBUG UnitTestFramework: '#run ok: 'One action on bluetooth''

2017-07-20 12:54:48 - DEBUG UnitTestFramework: '#teardown: 'One action on bluetooth''

2017-07-20 12:54:48 - DEBUG UnitTestFramework: '#teardown ok: 'One action on bluetooth''

2017-07-20 12:54:48 - DEBUG UnitTestFramework: '#setup: 'Two notification actions''

2017-07-20 12:54:49 - DEBUG UnitTestFramework: '#setup ok: 'Two notification actions''

2017-07-20 12:54:49 - DEBUG UnitTestFramework: '#run: 'Two notification actions''

2017-07-20 12:54:49 - DEBUG UnitTestFramework: '#run ok: 'Two notification actions''

2017-07-20 12:54:49 - DEBUG UnitTestFramework: '#teardown: 'Two notification actions''

2017-07-20 12:54:49 - DEBUG UnitTestFramework: '#teardown ok: 'Two notification actions''

2017-07-20 12:54:49 - DEBUG UnitTestFramework: '#setup: 'replicateThroughProblems''

2017-07-20 12:54:50 - DEBUG UnitTestFramework: '#setup ok: 'replicateThroughProblems''

2017-07-20 12:54:50 - DEBUG UnitTestFramework: '#run: 'replicateThroughProblems''

2017-07-20 12:54:50 - DEBUG UnitTestFramework: '#run ok: 'replicateThroughProblems''

2017-07-20 12:54:50 - DEBUG UnitTestFramework: '#teardown: 'replicateThroughProblems''

2017-07-20 12:54:50 - DEBUG UnitTestFramework: '#teardown ok: 'replicateThroughProblems''

2017-07-20 12:54:50 - DEBUG UnitTestFramework: '#setup: 'Replication goes first''

2017-07-20 12:54:50 - DEBUG UnitTestFramework: '#setup ok: 'Replication goes first''

2017-07-20 12:54:50 - DEBUG UnitTestFramework: '#run: 'Replication goes first''

2017-07-20 12:54:50 - DEBUG UnitTestFramework: '#run ok: 'Replication goes first''

2017-07-20 12:54:50 - DEBUG UnitTestFramework: '#teardown: 'Replication goes first''

2017-07-20 12:54:51 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-20 12:54:51 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-20 12:54:51 - DEBUG UnitTestFramework: '#teardown ok: 'Replication goes first''

2017-07-20 12:54:51 - DEBUG UnitTestFramework: '#setup: 'wifi allows many parallel non-replication actions''

2017-07-20 12:54:51 - DEBUG UnitTestFramework: '#setup ok: 'wifi allows many parallel non-replication actions''

2017-07-20 12:54:51 - DEBUG UnitTestFramework: '#run: 'wifi allows many parallel non-replication actions''

2017-07-20 12:54:51 - DEBUG UnitTestFramework: '#run ok: 'wifi allows many parallel non-replication actions''

2017-07-20 12:54:51 - DEBUG UnitTestFramework: '#teardown: 'wifi allows many parallel non-replication actions''

2017-07-20 12:54:51 - DEBUG UnitTestFramework: '#teardown ok: 'wifi allows many parallel non-replication actions''

2017-07-20 12:54:51 - DEBUG UnitTestFramework: '#setup: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#setup ok: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#run: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#run ok: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#teardown: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#teardown ok: 'wifi allows no more than 2 simultaneous replication actions for same peerID''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#setup: 'Client to server request coordinated''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#setup ok: 'Client to server request coordinated''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#run: 'Client to server request coordinated''

2017-07-20 12:54:52 - INFO Socket: 'run skipped, test: 'Client to server request coordinated', event: 'run_Client to server request coordinated''

2017-07-20 12:54:52 - INFO Socket: 'run skipped, test: 'Client to server request coordinated', event: 'run_Client to server request coordinated''

2017-07-20 12:54:52 - INFO Socket: 'run skipped, test: 'Client to server request coordinated', event: 'run_Client to server request coordinated''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#run ok: 'Client to server request coordinated''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#teardown: 'Client to server request coordinated''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#teardown ok: 'Client to server request coordinated''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#setup: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-20 12:54:52 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-20 12:54:53 - DEBUG UnitTestFramework: '#setup ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 12:54:53 - DEBUG UnitTestFramework: '#run: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 12:54:53 - DEBUG UnitTestFramework: '#run ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 12:54:53 - DEBUG UnitTestFramework: '#teardown: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 12:54:53 - DEBUG UnitTestFramework: '#teardown ok: 'Test BEACONS_RETRIEVED_AND_PARSED locally''

2017-07-20 12:54:53 - DEBUG UnitTestFramework: '#setup: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 12:54:54 - DEBUG UnitTestFramework: '#setup ok: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 12:54:54 - DEBUG UnitTestFramework: '#run: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 12:54:54 - INFO Socket: 'run skipped, test: 'Test HTTP_BAD_RESPONSE locally', event: 'run_Test HTTP_BAD_RESPONSE locally''

2017-07-20 12:54:54 - INFO Socket: 'run skipped, test: 'Test HTTP_BAD_RESPONSE locally', event: 'run_Test HTTP_BAD_RESPONSE locally''

2017-07-20 12:54:54 - INFO Socket: 'run skipped, test: 'Test HTTP_BAD_RESPONSE locally', event: 'run_Test HTTP_BAD_RESPONSE locally''

2017-07-20 12:54:54 - DEBUG UnitTestFramework: '#run ok: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 12:54:54 - DEBUG UnitTestFramework: '#teardown: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 12:54:54 - DEBUG UnitTestFramework: '#teardown ok: 'Test HTTP_BAD_RESPONSE locally''

2017-07-20 12:54:54 - DEBUG UnitTestFramework: '#setup: 'Test NETWORK_PROBLEM locally''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#setup ok: 'Test NETWORK_PROBLEM locally''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#run: 'Test NETWORK_PROBLEM locally''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#run ok: 'Test NETWORK_PROBLEM locally''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#teardown: 'Test NETWORK_PROBLEM locally''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#teardown ok: 'Test NETWORK_PROBLEM locally''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#setup: 'Action fails when getPeerHostInfo fails''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#setup ok: 'Action fails when getPeerHostInfo fails''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#run: 'Action fails when getPeerHostInfo fails''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#run ok: 'Action fails when getPeerHostInfo fails''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#teardown: 'Action fails when getPeerHostInfo fails''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#teardown ok: 'Action fails when getPeerHostInfo fails''

2017-07-20 12:54:55 - DEBUG UnitTestFramework: '#setup: 'Call the start two times''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#setup ok: 'Call the start two times''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#run: 'Call the start two times''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#run ok: 'Call the start two times''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#teardown: 'Call the start two times''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#teardown ok: 'Call the start two times''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#setup: 'Call the kill before calling the start''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill before calling the start''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#run: 'Call the kill before calling the start''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#run ok: 'Call the kill before calling the start''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#teardown: 'Call the kill before calling the start''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill before calling the start''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#setup: 'Call the kill immediately after the start''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill immediately after the start''

2017-07-20 12:54:56 - DEBUG UnitTestFramework: '#run: 'Call the kill immediately after the start''

2017-07-20 12:54:57 - DEBUG UnitTestFramework: '#run ok: 'Call the kill immediately after the start''

2017-07-20 12:54:57 - DEBUG UnitTestFramework: '#teardown: 'Call the kill immediately after the start''

2017-07-20 12:54:57 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill immediately after the start''

2017-07-20 12:54:57 - DEBUG UnitTestFramework: '#setup: 'Call the kill while waiting a response from the server''

2017-07-20 12:54:57 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-20 12:54:57 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-20 12:54:57 - DEBUG UnitTestFramework: '#setup ok: 'Call the kill while waiting a response from the server''

2017-07-20 12:54:57 - DEBUG UnitTestFramework: '#run: 'Call the kill while waiting a response from the server''

2017-07-20 12:54:58 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-20 12:54:58 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-20 12:54:59 - DEBUG UnitTestFramework: '#run ok: 'Call the kill while waiting a response from the server''

2017-07-20 12:54:59 - DEBUG UnitTestFramework: '#teardown: 'Call the kill while waiting a response from the server''

2017-07-20 12:54:59 - DEBUG UnitTestFramework: '#teardown ok: 'Call the kill while waiting a response from the server''

2017-07-20 12:54:59 - DEBUG UnitTestFramework: '#setup: 'Test to exceed the max content size locally''

2017-07-20 12:55:00 - DEBUG UnitTestFramework: '#setup ok: 'Test to exceed the max content size locally''

2017-07-20 12:55:00 - DEBUG UnitTestFramework: '#run: 'Test to exceed the max content size locally''

2017-07-20 12:55:00 - DEBUG UnitTestFramework: '#run ok: 'Test to exceed the max content size locally''

2017-07-20 12:55:00 - DEBUG UnitTestFramework: '#teardown: 'Test to exceed the max content size locally''

2017-07-20 12:55:00 - DEBUG UnitTestFramework: '#teardown ok: 'Test to exceed the max content size locally''

2017-07-20 12:55:00 - DEBUG UnitTestFramework: '#setup: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:01 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-20 12:55:01 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-20 12:55:01 - DEBUG UnitTestFramework: '#setup ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:01 - DEBUG UnitTestFramework: '#run: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:03 - DEBUG UnitTestFramework: '#run ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:03 - DEBUG UnitTestFramework: '#teardown: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:03 - DEBUG UnitTestFramework: '#teardown ok: 'Close the server socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:03 - DEBUG UnitTestFramework: '#setup: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:03 - DEBUG UnitTestFramework: '#setup ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:03 - DEBUG UnitTestFramework: '#run: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:04 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-20 12:55:04 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#run ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#teardown: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#teardown ok: 'Close the client socket while the client is waiting a response from the server. Local test.''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons bad args''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons bad args''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons bad args''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons bad args''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons bad args''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons bad args''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 12:55:06 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 12:55:07 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:55:07 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:55:07 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 12:55:07 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 12:55:07 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons empty keys to notify''

2017-07-20 12:55:07 - DEBUG UnitTestFramework: '#setup: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 12:55:07 - DEBUG UnitTestFramework: '#setup ok: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 12:55:07 - DEBUG UnitTestFramework: '#run: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 12:55:08 - DEBUG UnitTestFramework: '#run ok: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 12:55:08 - DEBUG UnitTestFramework: '#teardown: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 12:55:08 - DEBUG UnitTestFramework: '#teardown ok: '#generatePreambleAndBeacons multiple keys to notify''

2017-07-20 12:55:08 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 12:55:08 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 12:55:08 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid expiration in beaconStreamWithPreAmble''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#setup: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#run: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#setup: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:09 - DEBUG UnitTestFramework: '#run: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons expiration out of range lower''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#setup: '#parseBeacons no beacons returns null''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons no beacons returns null''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#run: '#parseBeacons no beacons returns null''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons no beacons returns null''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons no beacons returns null''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons no beacons returns null''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#setup: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#run: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 12:55:10 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 12:55:11 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble''

2017-07-20 12:55:11 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 12:55:11 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:55:11 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:55:11 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 12:55:11 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 12:55:11 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 12:55:11 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 12:55:12 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback fails decrypt''

2017-07-20 12:55:12 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 12:55:12 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 12:55:12 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 12:55:12 - INFO Socket: 'run skipped, test: '#parseBeacons addressBookCallback returns no matches', event: 'run_#parseBeacons addressBookCallback returns no matches''

2017-07-20 12:55:12 - INFO Socket: 'run skipped, test: '#parseBeacons addressBookCallback returns no matches', event: 'run_#parseBeacons addressBookCallback returns no matches''

2017-07-20 12:55:12 - INFO Socket: 'run skipped, test: '#parseBeacons addressBookCallback returns no matches', event: 'run_#parseBeacons addressBookCallback returns no matches''

2017-07-20 12:55:12 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 12:55:12 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 12:55:12 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-07-20 12:55:12 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns no matches''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns spurious match''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#setup: '#parseBeacons addressBookCallback returns public key''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#setup ok: '#parseBeacons addressBookCallback returns public key''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#run: '#parseBeacons addressBookCallback returns public key''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#run ok: '#parseBeacons addressBookCallback returns public key''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#teardown: '#parseBeacons addressBookCallback returns public key''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#teardown ok: '#parseBeacons addressBookCallback returns public key''

2017-07-20 12:55:13 - DEBUG UnitTestFramework: '#setup: 'validate generatePskIdentityField''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskIdentityField''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#run: 'validate generatePskIdentityField''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskIdentityField''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskIdentityField''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskIdentityField''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#setup: 'validate generatePskSecret''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskSecret''
2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#run: 'validate generatePskSecret''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskSecret''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskSecret''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskSecret''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#setup: 'validate generatePskSecrets''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#setup ok: 'validate generatePskSecrets''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#run: 'validate generatePskSecrets''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#run ok: 'validate generatePskSecrets''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#teardown: 'validate generatePskSecrets''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#teardown ok: 'validate generatePskSecrets''

2017-07-20 12:55:14 - DEBUG UnitTestFramework: '#setup: 'validate generateBeaconStreamAndSecrets''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#setup ok: 'validate generateBeaconStreamAndSecrets''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#run: 'validate generateBeaconStreamAndSecrets''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#run ok: 'validate generateBeaconStreamAndSecrets''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#teardown: 'validate generateBeaconStreamAndSecrets''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#teardown ok: 'validate generateBeaconStreamAndSecrets''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#setup: 'Add two Peers.''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#setup ok: 'Add two Peers.''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#run: 'Add two Peers.''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#run ok: 'Add two Peers.''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#teardown: 'Add two Peers.''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#teardown ok: 'Add two Peers.''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#setup: 'TCP_NATIVE peer loses DNS''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#setup ok: 'TCP_NATIVE peer loses DNS''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#run: 'TCP_NATIVE peer loses DNS''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#run ok: 'TCP_NATIVE peer loses DNS''

2017-07-20 12:55:15 - DEBUG UnitTestFramework: '#teardown: 'TCP_NATIVE peer loses DNS''

2017-07-20 12:55:16 - DEBUG UnitTestFramework: '#teardown ok: 'TCP_NATIVE peer loses DNS''

2017-07-20 12:55:16 - DEBUG UnitTestFramework: '#setup: 'Received beacons with no values for us''

2017-07-20 12:55:16 - DEBUG UnitTestFramework: '#setup ok: 'Received beacons with no values for us''

2017-07-20 12:55:16 - DEBUG UnitTestFramework: '#run: 'Received beacons with no values for us''

2017-07-20 12:55:16 - DEBUG UnitTestFramework: '#run ok: 'Received beacons with no values for us''

2017-07-20 12:55:16 - DEBUG UnitTestFramework: '#teardown: 'Received beacons with no values for us''

2017-07-20 12:55:16 - DEBUG UnitTestFramework: '#teardown ok: 'Received beacons with no values for us''

2017-07-20 12:55:16 - DEBUG UnitTestFramework: '#setup: 'Notification action killed with a superseded''

2017-07-20 12:55:16 - DEBUG UnitTestFramework: '#setup ok: 'Notification action killed with a superseded''

2017-07-20 12:55:16 - DEBUG UnitTestFramework: '#run: 'Notification action killed with a superseded''

2017-07-20 12:55:17 - DEBUG UnitTestFramework: '#run ok: 'Notification action killed with a superseded''

2017-07-20 12:55:17 - DEBUG UnitTestFramework: '#teardown: 'Notification action killed with a superseded''

2017-07-20 12:55:17 - DEBUG UnitTestFramework: '#teardown ok: 'Notification action killed with a superseded''

2017-07-20 12:55:17 - DEBUG UnitTestFramework: '#setup: 'Resolves an action locally''

2017-07-20 12:55:17 - DEBUG UnitTestFramework: '#setup ok: 'Resolves an action locally''

2017-07-20 12:55:17 - DEBUG UnitTestFramework: '#run: 'Resolves an action locally''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#run ok: 'Resolves an action locally''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#teardown: 'Resolves an action locally''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#teardown ok: 'Resolves an action locally''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#setup: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#setup ok: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#run: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#run ok: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#teardown: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#teardown ok: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:18 - DEBUG UnitTestFramework: '#setup: 'Resolves an action locally using ThaliPeerPoolDefault''

2017-07-20 12:55:19 - DEBUG UnitTestFramework: '#setup ok: 'Resolves an action locally using ThaliPeerPoolDefault''

2017-07-20 12:55:19 - DEBUG UnitTestFramework: '#run: 'Resolves an action locally using ThaliPeerPoolDefault''

2017-07-20 12:55:19 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-20 12:55:19 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:55:19 - DEBUG UnitTestFramework: '#run ok: 'Resolves an action locally using ThaliPeerPoolDefault''

2017-07-20 12:55:19 - DEBUG UnitTestFramework: '#teardown: 'Resolves an action locally using ThaliPeerPoolDefault''

2017-07-20 12:55:19 - DEBUG UnitTestFramework: '#teardown ok: 'Resolves an action locally using ThaliPeerPoolDefault''

2017-07-20 12:55:19 - DEBUG UnitTestFramework: '#setup: 'Action fails because of a bad hostname.''

2017-07-20 12:55:19 - DEBUG UnitTestFramework: '#setup ok: 'Action fails because of a bad hostname.''

2017-07-20 12:55:19 - DEBUG UnitTestFramework: '#run: 'Action fails because of a bad hostname.''

2017-07-20 12:55:21 - DEBUG UnitTestFramework: '#run ok: 'Action fails because of a bad hostname.''

2017-07-20 12:55:21 - DEBUG UnitTestFramework: '#teardown: 'Action fails because of a bad hostname.''

2017-07-20 12:55:21 - DEBUG UnitTestFramework: '#teardown ok: 'Action fails because of a bad hostname.''

2017-07-20 12:55:21 - DEBUG UnitTestFramework: '#setup: 'hostaddress is removed when the action is running. ''

2017-07-20 12:55:21 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:55:21 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:55:21 - DEBUG UnitTestFramework: '#setup ok: 'hostaddress is removed when the action is running. ''

2017-07-20 12:55:21 - DEBUG UnitTestFramework: '#run: 'hostaddress is removed when the action is running. ''

2017-07-20 12:55:22 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:55:22 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:55:23 - DEBUG UnitTestFramework: '#run ok: 'hostaddress is removed when the action is running. ''

2017-07-20 12:55:23 - DEBUG UnitTestFramework: '#teardown: 'hostaddress is removed when the action is running. ''

2017-07-20 12:55:23 - DEBUG UnitTestFramework: '#teardown ok: 'hostaddress is removed when the action is running. ''

2017-07-20 12:55:23 - DEBUG UnitTestFramework: '#setup: 'notificationClient does not retry action with BAD_PEER resolution''

2017-07-20 12:55:23 - DEBUG UnitTestFramework: '#setup ok: 'notificationClient does not retry action with BAD_PEER resolution''

2017-07-20 12:55:24 - DEBUG UnitTestFramework: '#run: 'notificationClient does not retry action with BAD_PEER resolution''

2017-07-20 12:55:24 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-20 12:55:24 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:55:24 - DEBUG UnitTestFramework: '#run ok: 'notificationClient does not retry action with BAD_PEER resolution''

2017-07-20 12:55:24 - DEBUG UnitTestFramework: '#teardown: 'notificationClient does not retry action with BAD_PEER resolution''

2017-07-20 12:55:24 - DEBUG UnitTestFramework: '#teardown ok: 'notificationClient does not retry action with BAD_PEER resolution''

2017-07-20 12:55:24 - DEBUG UnitTestFramework: '#setup: 'notification client correctly handles peer availability changes of the same peer''

2017-07-20 12:55:24 - DEBUG UnitTestFramework: '#setup ok: 'notification client correctly handles peer availability changes of the same peer''

2017-07-20 12:55:24 - DEBUG UnitTestFramework: '#run: 'notification client correctly handles peer availability changes of the same peer''

2017-07-20 12:55:25 - DEBUG UnitTestFramework: '#run ok: 'notification client correctly handles peer availability changes of the same peer''

2017-07-20 12:55:25 - DEBUG UnitTestFramework: '#teardown: 'notification client correctly handles peer availability changes of the same peer''

2017-07-20 12:55:25 - DEBUG UnitTestFramework: '#teardown ok: 'notification client correctly handles peer availability changes of the same peer''

2017-07-20 12:55:25 - DEBUG UnitTestFramework: '#setup: 'Client to server request locally''

2017-07-20 12:55:25 - DEBUG UnitTestFramework: '#setup ok: 'Client to server request locally''

2017-07-20 12:55:25 - DEBUG UnitTestFramework: '#run: 'Client to server request locally''

2017-07-20 12:55:26 - DEBUG UnitTestFramework: '#run ok: 'Client to server request locally''

2017-07-20 12:55:26 - DEBUG UnitTestFramework: '#teardown: 'Client to server request locally''

2017-07-20 12:55:26 - DEBUG UnitTestFramework: '#teardown ok: 'Client to server request locally''

2017-07-20 12:55:26 - DEBUG UnitTestFramework: '#setup: 'Test ThaliPskMapCache clean and expiration''

2017-07-20 12:55:26 - DEBUG UnitTestFramework: '#setup ok: 'Test ThaliPskMapCache clean and expiration''

2017-07-20 12:55:26 - DEBUG UnitTestFramework: '#run: 'Test ThaliPskMapCache clean and expiration''

2017-07-20 12:55:27 - DEBUG UnitTestFramework: '#run ok: 'Test ThaliPskMapCache clean and expiration''

2017-07-20 12:55:27 - DEBUG UnitTestFramework: '#teardown: 'Test ThaliPskMapCache clean and expiration''

2017-07-20 12:55:27 - DEBUG UnitTestFramework: '#teardown ok: 'Test ThaliPskMapCache clean and expiration''

2017-07-20 12:55:27 - DEBUG UnitTestFramework: '#setup: 'Test ThaliPskMapCache getSecret and getPublic''

2017-07-20 12:55:27 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:55:27 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:55:27 - DEBUG UnitTestFramework: '#setup ok: 'Test ThaliPskMapCache getSecret and getPublic''

2017-07-20 12:55:27 - DEBUG UnitTestFramework: '#run: 'Test ThaliPskMapCache getSecret and getPublic''

2017-07-20 12:55:29 - DEBUG UnitTestFramework: '#run ok: 'Test ThaliPskMapCache getSecret and getPublic''

2017-07-20 12:55:29 - DEBUG UnitTestFramework: '#teardown: 'Test ThaliPskMapCache getSecret and getPublic''

2017-07-20 12:55:29 - DEBUG UnitTestFramework: '#teardown ok: 'Test ThaliPskMapCache getSecret and getPublic''

2017-07-20 12:55:29 - DEBUG UnitTestFramework: '#setup: 'Test ThaliPskMapCache multiple entries''

2017-07-20 12:55:30 - DEBUG UnitTestFramework: '#setup ok: 'Test ThaliPskMapCache multiple entries''

2017-07-20 12:55:30 - DEBUG UnitTestFramework: '#run: 'Test ThaliPskMapCache multiple entries''

2017-07-20 12:55:30 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:55:30 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:55:32 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-20 12:55:32 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:55:32 - DEBUG UnitTestFramework: '#run ok: 'Test ThaliPskMapCache multiple entries''

2017-07-20 12:55:32 - DEBUG UnitTestFramework: '#teardown: 'Test ThaliPskMapCache multiple entries''

2017-07-20 12:55:32 - DEBUG UnitTestFramework: '#teardown ok: 'Test ThaliPskMapCache multiple entries''

2017-07-20 12:55:32 - DEBUG UnitTestFramework: '#setup: 'Start and stop ThaliNotificationServer''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#setup ok: 'Start and stop ThaliNotificationServer''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#run: 'Start and stop ThaliNotificationServer''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#run ok: 'Start and stop ThaliNotificationServer''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#teardown: 'Start and stop ThaliNotificationServer''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#teardown ok: 'Start and stop ThaliNotificationServer''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#setup: 'Pass an empty array to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#setup ok: 'Pass an empty array to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#run: 'Pass an empty array to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#run ok: 'Pass an empty array to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#teardown: 'Pass an empty array to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#teardown ok: 'Pass an empty array to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#setup: 'Pass a string to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#setup ok: 'Pass a string to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#run: 'Pass a string to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#run ok: 'Pass a string to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#teardown: 'Pass a string to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#teardown ok: 'Pass a string to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#setup: 'Pass an empty parameter to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#setup ok: 'Pass an empty parameter to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#run: 'Pass an empty parameter to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#run ok: 'Pass an empty parameter to ThaliNotificationServer.start''

2017-07-20 12:55:33 - DEBUG UnitTestFramework: '#teardown: 'Pass an empty parameter to ThaliNotificationServer.start''

2017-07-20 12:55:34 - DEBUG UnitTestFramework: '#teardown ok: 'Pass an empty parameter to ThaliNotificationServer.start''

2017-07-20 12:55:34 - DEBUG UnitTestFramework: '#setup: 'Make an HTTP request to /NotificationBeacons''

2017-07-20 12:55:35 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:55:35 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:55:35 - DEBUG UnitTestFramework: '#setup ok: 'Make an HTTP request to /NotificationBeacons''

2017-07-20 12:55:35 - DEBUG UnitTestFramework: '#run: 'Make an HTTP request to /NotificationBeacons''

2017-07-20 12:55:35 - DEBUG UnitTestFramework: '#run ok: 'Make an HTTP request to /NotificationBeacons''

2017-07-20 12:55:35 - DEBUG UnitTestFramework: '#teardown: 'Make an HTTP request to /NotificationBeacons''

2017-07-20 12:55:36 - DEBUG UnitTestFramework: '#teardown ok: 'Make an HTTP request to /NotificationBeacons''

2017-07-20 12:55:36 - DEBUG UnitTestFramework: '#setup: 'Make an HTTP request to /NotificationBeacons (no keys)''

2017-07-20 12:55:36 - DEBUG UnitTestFramework: '#setup ok: 'Make an HTTP request to /NotificationBeacons (no keys)''

2017-07-20 12:55:36 - DEBUG UnitTestFramework: '#run: 'Make an HTTP request to /NotificationBeacons (no keys)''

2017-07-20 12:55:36 - DEBUG UnitTestFramework: '#run ok: 'Make an HTTP request to /NotificationBeacons (no keys)''

2017-07-20 12:55:36 - DEBUG UnitTestFramework: '#teardown: 'Make an HTTP request to /NotificationBeacons (no keys)''

2017-07-20 12:55:36 - DEBUG UnitTestFramework: '#teardown ok: 'Make an HTTP request to /NotificationBeacons (no keys)''

2017-07-20 12:55:36 - DEBUG UnitTestFramework: '#setup: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

2017-07-20 12:55:36 - DEBUG UnitTestFramework: '#setup ok: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

2017-07-20 12:55:36 - DEBUG UnitTestFramework: '#run: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#run ok: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#teardown: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#teardown ok: 'Make an HTTP request to /NotificationBeaconsbefore calling start''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#setup: 'Make sure peerDictionaryKey is reasonable''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#setup ok: 'Make sure peerDictionaryKey is reasonable''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#run: 'Make sure peerDictionaryKey is reasonable''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#run ok: 'Make sure peerDictionaryKey is reasonable''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#teardown: 'Make sure peerDictionaryKey is reasonable''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure peerDictionaryKey is reasonable''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#setup: 'Make sure start works''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#setup ok: 'Make sure start works''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#run: 'Make sure start works''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#run ok: 'Make sure start works''

2017-07-20 12:55:37 - DEBUG UnitTestFramework: '#teardown: 'Make sure start works''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure start works''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#setup: 'Make sure stop works''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#setup ok: 'Make sure stop works''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#run: 'Make sure stop works''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#run ok: 'Make sure stop works''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#teardown: 'Make sure stop works''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure stop works''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#setup: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#setup ok: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#run: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#run ok: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#teardown: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#teardown ok: 'Emits error event when peerPool.enqueue throws''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#setup: 'Simple peer event''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#setup ok: 'Simple peer event''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#run: 'Simple peer event''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#run ok: 'Simple peer event''

2017-07-20 12:55:38 - DEBUG UnitTestFramework: '#teardown: 'Simple peer event''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#teardown ok: 'Simple peer event''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#setup: 'Coordinated pull replication from notification test''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated pull replication from notification test''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#run: 'Coordinated pull replication from notification test''

2017-07-20 12:55:39 - INFO Socket: 'run skipped, test: 'Coordinated pull replication from notification test', event: 'run_Coordinated pull replication from notification test''

2017-07-20 12:55:39 - INFO Socket: 'run skipped, test: 'Coordinated pull replication from notification test', event: 'run_Coordinated pull replication from notification test''

2017-07-20 12:55:39 - INFO Socket: 'run skipped, test: 'Coordinated pull replication from notification test', event: 'run_Coordinated pull replication from notification test''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#run ok: 'Coordinated pull replication from notification test''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#teardown: 'Coordinated pull replication from notification test''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#teardown ok: 'Coordinated pull replication from notification test''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#setup: 'Server is not there''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:55:39 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:55:40 - DEBUG UnitTestFramework: '#setup ok: 'Server is not there''

2017-07-20 12:55:40 - DEBUG UnitTestFramework: '#run: 'Server is not there''

2017-07-20 12:55:40 - DEBUG UnitTestFramework: '#run ok: 'Server is not there''

2017-07-20 12:55:40 - DEBUG UnitTestFramework: '#teardown: 'Server is not there''

2017-07-20 12:55:40 - DEBUG UnitTestFramework: '#teardown ok: 'Server is not there''

2017-07-20 12:55:40 - DEBUG UnitTestFramework: '#setup: 'Server accepts & closes connection''

2017-07-20 12:55:40 - DEBUG UnitTestFramework: '#setup ok: 'Server accepts & closes connection''

2017-07-20 12:55:40 - DEBUG UnitTestFramework: '#run: 'Server accepts & closes connection''

2017-07-20 12:55:41 - DEBUG UnitTestFramework: '#run ok: 'Server accepts & closes connection''

2017-07-20 12:55:41 - DEBUG UnitTestFramework: '#teardown: 'Server accepts & closes connection''

2017-07-20 12:55:41 - DEBUG UnitTestFramework: '#teardown ok: 'Server accepts & closes connection''

2017-07-20 12:55:41 - DEBUG UnitTestFramework: '#setup: 'Server always returns 500''

2017-07-20 12:55:41 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 500''

2017-07-20 12:55:41 - DEBUG UnitTestFramework: '#run: 'Server always returns 500''

2017-07-20 12:55:41 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 500''

2017-07-20 12:55:41 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 500''

2017-07-20 12:55:41 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 500''

2017-07-20 12:55:41 - DEBUG UnitTestFramework: '#setup: 'Server always returns 401''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 401''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#run: 'Server always returns 401''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 401''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 401''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 401''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#setup: 'Server always returns 403''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#setup ok: 'Server always returns 403''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#run: 'Server always returns 403''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#run ok: 'Server always returns 403''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#teardown: 'Server always returns 403''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#teardown ok: 'Server always returns 403''

2017-07-20 12:55:42 - DEBUG UnitTestFramework: '#setup: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 12:55:43 - DEBUG UnitTestFramework: '#setup ok: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 12:55:43 - DEBUG UnitTestFramework: '#run: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 12:55:45 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-20 12:55:45 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-20 12:55:48 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-20 12:55:48 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-20 12:55:48 - DEBUG UnitTestFramework: '#run ok: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 12:55:48 - DEBUG UnitTestFramework: '#teardown: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 12:55:48 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure docs replicate with remote db with same name as local db''

2017-07-20 12:55:48 - DEBUG UnitTestFramework: '#setup: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 12:55:48 - DEBUG UnitTestFramework: '#setup ok: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 12:55:48 - DEBUG UnitTestFramework: '#run: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 12:55:51 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-20 12:55:51 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-20 12:55:53 - DEBUG UnitTestFramework: '#run ok: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 12:55:53 - DEBUG UnitTestFramework: '#teardown: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 12:55:53 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure docs replicate with remote db with different name than local db''

2017-07-20 12:55:53 - DEBUG UnitTestFramework: '#setup: 'Do nothing and make sure we time out''

2017-07-20 12:55:53 - DEBUG UnitTestFramework: '#setup ok: 'Do nothing and make sure we time out''

2017-07-20 12:55:53 - DEBUG UnitTestFramework: '#run: 'Do nothing and make sure we time out''

2017-07-20 12:55:54 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-20 12:55:54 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-20 12:55:54 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-20 12:55:54 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-20 12:55:56 - DEBUG UnitTestFramework: '#run ok: 'Do nothing and make sure we time out''

2017-07-20 12:55:56 - DEBUG UnitTestFramework: '#teardown: 'Do nothing and make sure we time out''

2017-07-20 12:55:56 - DEBUG UnitTestFramework: '#teardown ok: 'Do nothing and make sure we time out''

2017-07-20 12:55:56 - DEBUG UnitTestFramework: '#setup: 'Do something and make sure we time out''

2017-07-20 12:55:56 - DEBUG UnitTestFramework: '#setup ok: 'Do something and make sure we time out''

2017-07-20 12:55:56 - DEBUG UnitTestFramework: '#run: 'Do something and make sure we time out''

2017-07-20 12:56:00 - DEBUG UnitTestFramework: '#run ok: 'Do something and make sure we time out''

2017-07-20 12:56:00 - DEBUG UnitTestFramework: '#teardown: 'Do something and make sure we time out''

2017-07-20 12:56:01 - DEBUG UnitTestFramework: '#teardown ok: 'Do something and make sure we time out''

2017-07-20 12:56:01 - DEBUG UnitTestFramework: '#setup: 'Start replicating and then catch error when server goes''

2017-07-20 12:56:01 - DEBUG UnitTestFramework: '#setup ok: 'Start replicating and then catch error when server goes''

2017-07-20 12:56:01 - DEBUG UnitTestFramework: '#run: 'Start replicating and then catch error when server goes''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#run ok: 'Start replicating and then catch error when server goes''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#teardown: 'Start replicating and then catch error when server goes''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#teardown ok: 'Start replicating and then catch error when server goes''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#setup: 'Make sure clone works''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#setup ok: 'Make sure clone works''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#run: 'Make sure clone works''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#run ok: 'Make sure clone works''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#teardown: 'Make sure clone works''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#teardown ok: 'Make sure clone works''

2017-07-20 12:56:02 - DEBUG UnitTestFramework: '#setup: 'Coordinated replication action test - each device has the same local db name''

2017-07-20 12:56:03 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated replication action test - each device has the same local db name''

2017-07-20 12:56:03 - DEBUG UnitTestFramework: '#run: 'Coordinated replication action test - each device has the same local db name''

2017-07-20 12:56:03 - INFO Socket: 'run skipped, test: 'Coordinated replication action test - each device has the same local db name', event: 'run_Coordinated replication action test - each device has the same local db name''

2017-07-20 12:56:03 - INFO Socket: 'run skipped, test: 'Coordinated replication action test - each device has the same local db name', event: 'run_Coordinated replication action test - each device has the same local db name''

2017-07-20 12:56:03 - INFO Socket: 'run skipped, test: 'Coordinated replication action test - each device has the same local db name', event: 'run_Coordinated replication action test - each device has the same local db name''

2017-07-20 12:56:03 - DEBUG UnitTestFramework: '#run ok: 'Coordinated replication action test - each device has the same local db name''

2017-07-20 12:56:03 - DEBUG UnitTestFramework: '#teardown: 'Coordinated replication action test - each device has the same local db name''

2017-07-20 12:56:03 - DEBUG UnitTestFramework: '#teardown ok: 'Coordinated replication action test - each device has the same local db name''

2017-07-20 12:56:03 - DEBUG UnitTestFramework: '#setup: 'Coordinated replication action test - each device has different local db name''

2017-07-20 12:56:03 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated replication action test - each device has different local db name''

2017-07-20 12:56:03 - DEBUG UnitTestFramework: '#run: 'Coordinated replication action test - each device has different local db name''

2017-07-20 12:56:05 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''
2017-07-20 12:56:05 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-20 12:56:08 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-20 12:56:08 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-20 12:56:11 - DEBUG UnitTestFramework: '#sync'

2017-07-20 12:56:11 - DEBUG UnitTestFramework: '#sync'

2017-07-20 12:56:12 - DEBUG UnitTestFramework: '#sync'

2017-07-20 12:56:20 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-20 12:56:20 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-20 12:56:23 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-20 12:56:23 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-20 12:56:24 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-20 12:56:24 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-20 12:56:24 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-20 12:56:25 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-20 12:56:26 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-07-20 12:56:26 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-20 12:56:26 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-20 12:56:28 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-20 12:56:28 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-20 12:56:29 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-20 12:56:29 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-20 12:56:38 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-20 12:56:38 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-20 12:56:42 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-20 12:56:42 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-20 12:56:42 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-20 12:56:42 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-20 12:56:59 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-20 12:56:59 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-20 12:57:01 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-20 12:57:01 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:57:02 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:57:02 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:57:09 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:57:09 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:57:13 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-20 12:57:13 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-20 12:57:14 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-20 12:57:14 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-20 12:57:14 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-20 12:57:15 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-20 12:57:16 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-20 12:57:16 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-20 12:57:16 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-20 12:57:18 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-20 12:57:18 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:57:20 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:57:20 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:57:25 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:57:25 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:57:26 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-20 12:57:26 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:57:28 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:57:28 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:57:31 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:57:31 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:57:31 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-20 12:57:31 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:57:35 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:57:35 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:57:35 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-20 12:57:37 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-20 12:57:37 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-20 12:57:37 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:57:37 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:57:38 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-07-20 12:57:38 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:57:39 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:57:39 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:57:47 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:57:47 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:57:49 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-20 12:57:49 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:57:52 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:57:52 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:57:52 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:57:52 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:57:54 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:57:54 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:57:54 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:57:55 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-20 12:57:55 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:57:57 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:57:57 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-20 12:58:56 - ERROR UnitTestFramework: '#run failed: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', error: 'Error: run failed, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', sent data: '[{"uuid":"d439ea7f-e10e-4d5f-8ac3-c286daf51c8d"},{"uuid":"4853b810-73dc-48d1-9738-4cbf9ba00737"},{"uuid":"4c71869b-df56-443b-b756-1af524e6858c"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', sent data: '[{"uuid":"d439ea7f-e10e-4d5f-8ac3-c286daf51c8d"},{"uuid":"4853b810-73dc-48d1-9738-4cbf9ba00737"},{"uuid":"4c71869b-df56-443b-b756-1af524e6858c"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_113351851f4ec514/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_113351851f4ec514/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-07-20 12:58:56 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: run failed, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', sent data: '[{"uuid":"d439ea7f-e10e-4d5f-8ac3-c286daf51c8d"},{"uuid":"4853b810-73dc-48d1-9738-4cbf9ba00737"},{"uuid":"4c71869b-df56-443b-b756-1af524e6858c"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', sent data: '[{"uuid":"d439ea7f-e10e-4d5f-8ac3-c286daf51c8d"},{"uuid":"4853b810-73dc-48d1-9738-4cbf9ba00737"},{"uuid":"4c71869b-df56-443b-b756-1af524e6858c"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_113351851f4ec514/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_113351851f4ec514/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-07-20 12:59:03 - ERROR UnitTestFramework: '#run failed: 'Coordinated replication action test - each device has different local db name', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated replication action test - each device has different local db name_finished', test: 'Coordinated replication action test - each device has different local db name'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated replication action test - each device has different local db name_finished', test: 'Coordinated replication action test - each device has different local db name'
    at afterTimeout (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-20 12:59:03 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated replication action test - each device has different local db name_finished', test: 'Coordinated replication action test - each device has different local db name'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated replication action test - each device has different local db name_finished', test: 'Coordinated replication action test - each device has different local db name'
    at afterTimeout (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851f4ec514/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-20 12:59:03 - DEBUG TestServer: 'completed'

2017-07-20 12:59:03 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-07-20 12:59:03 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-07-20 12:59:03 - INFO HttpServer: 'Socket to device name: 'Apple-Iphone6sPlus-1' disconnected, reason: 'undefined''

2017-07-20 12:59:03 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-20 12:59:03 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-20 12:59:03 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
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

ios : Error: Command failed: true
20/7/2017@14:46:40 Getting the list of iOS devices 
20/7/2017@14:46:45 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
20/7/2017@14:46:45 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
20/7/2017@14:46:45 ios: device name: Iphone6sPlus-1 , device identifier:  f70cda60583ea0f895d05ea355cd125983c27594
20/7/2017@14:46:45 Deploying iOS test app 
20/7/2017@14:46:45 uninstalling the application 
20/7/2017@14:46:45 installing the application 
20/7/2017@14:46:45 ios.run: bffa901fefdea07f59339a6737776943349f5077 /Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app
20/7/2017@14:46:45 ios.run: 00b2e2c1b30013159b62125fe7f097bdcc055c10 /Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app
20/7/2017@14:46:45 ios.run: f70cda60583ea0f895d05ea355cd125983c27594 /Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app
20/7/2017@15:09:59 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
20/7/2017@15:09:59 ios: child process exited with code null on device f70cda60583ea0f895d05ea355cd125983c27594 
20/7/2017@15:09:59 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
true

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

Error! Unexpected exit on device ce061606e320561102 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce061606e320561102 green
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851f4ec514_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851f4ec514_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851f4ec514_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/113351851f4ec514_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/113351851f4ec514_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[Iphone6sPlus-1](https://github.com/ThaliTester/TestResults/blob/113351851f4ec514_CI_sanity_check_jareksl/iOS_Iphone6sPlus-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/113351851f4ec514_CI_sanity_check_jareksl/iOS_server.md)





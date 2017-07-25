#### Test 13228325722939a4 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":2}}
2017-07-25 16:23:56 - INFO HttpServer: 'listening on *:3000'

2017-07-25 16:24:00 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'f98a2584-a3fa-4132-acbe-1dcf2916ee48', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-25 16:24:00 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-07-25 16:24:01 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'f98a2584-a3fa-4132-acbe-1dcf2916ee48', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-25 16:24:01 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'f98a2584-a3fa-4132-acbe-1dcf2916ee48', platformName: 'ios''

2017-07-25 16:24:02 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'f19dbd28-331f-4e7c-a8e9-6cd55ede1de5', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-25 16:24:02 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-07-25 16:24:04 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6sPlus-1', uuid: '8641dfc1-acf8-4ae6-b12b-771009332f70', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-25 16:24:04 - DEBUG TestFramework: 'device added, name: 'Apple-Iphone6sPlus-1''

2017-07-25 16:24:04 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-07-25 16:24:04 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-07-25 16:24:04 - DEBUG UnitTestFramework: 'scheduling tests'

2017-07-25 16:24:04 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'f19dbd28-331f-4e7c-a8e9-6cd55ede1de5', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-25 16:24:04 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: 'f19dbd28-331f-4e7c-a8e9-6cd55ede1de5', platformName: 'ios''

2017-07-25 16:24:05 - DEBUG UnitTestFramework: 'tests scheduled'

2017-07-25 16:24:05 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-07-25 16:24:05 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-07-25 16:24:05 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-07-25 16:24:05 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-07-25 16:24:05 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-07-25 16:24:05 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6sPlus-1', uuid: '8641dfc1-acf8-4ae6-b12b-771009332f70', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-25 16:24:05 - INFO TestFramework: 'updating existing device, name: 'Apple-Iphone6sPlus-1', uuid: '8641dfc1-acf8-4ae6-b12b-771009332f70', platformName: 'ios''

2017-07-25 16:24:06 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-07-25 16:24:06 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-07-25 16:24:06 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-07-25 16:24:06 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-25 16:24:07 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-07-25 16:24:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-25 16:24:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-25 16:24:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-25 16:24:08 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-25 16:24:09 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-25 16:24:09 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-25 16:24:09 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-07-25 16:24:09 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-25 16:24:09 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-25 16:24:09 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-07-25 16:24:09 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-25 16:24:09 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-25 16:24:09 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-25 16:24:09 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-25 16:24:09 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-25 16:24:09 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-25 16:24:09 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-25 16:24:09 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-25 16:24:10 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-07-25 16:24:10 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-25 16:24:10 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-25 16:24:10 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-25 16:24:10 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-25 16:24:10 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-25 16:24:10 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-25 16:24:10 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-25 16:24:10 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-07-25 16:24:11 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-07-25 16:24:12 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-07-25 16:24:13 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-07-25 16:24:14 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-07-25 16:24:14 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-07-25 16:24:14 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-07-25 16:24:14 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-07-25 16:24:14 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-07-25 16:24:14 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-07-25 16:24:14 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-07-25 16:24:14 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-07-25 16:24:14 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-07-25 16:24:14 - DEBUG UnitTestFramework: '#run: 'basic''

2017-07-25 16:24:15 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-07-25 16:24:15 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-07-25 16:24:16 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-07-25 16:24:16 - DEBUG UnitTestFramework: '#setup: 'another''

2017-07-25 16:24:16 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-07-25 16:24:16 - DEBUG UnitTestFramework: '#run: 'another''

2017-07-25 16:24:16 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-07-25 16:24:16 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#run: 'skip''

2017-07-25 16:24:17 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-25 16:24:17 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-25 16:24:17 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-07-25 16:24:17 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-25 16:24:17 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-25 16:24:17 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-07-25 16:24:17 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-07-25 16:24:18 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-07-25 16:24:18 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-07-25 16:24:18 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-07-25 16:24:18 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-07-25 16:24:18 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-07-25 16:24:18 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-07-25 16:24:18 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-07-25 16:24:18 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-07-25 16:24:18 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-07-25 16:24:18 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-07-25 16:24:19 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-07-25 16:24:19 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-07-25 16:24:19 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-07-25 16:24:19 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-07-25 16:24:19 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-07-25 16:24:19 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-07-25 16:24:19 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-07-25 16:24:19 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-07-25 16:24:20 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-07-25 16:24:21 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-25 16:24:21 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-25 16:24:21 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-07-25 16:24:21 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-25 16:24:21 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-25 16:24:21 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-07-25 16:24:21 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-07-25 16:24:22 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-07-25 16:24:22 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-07-25 16:24:22 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-07-25 16:24:22 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-07-25 16:24:23 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''
2017-07-25 16:24:23 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-25 16:24:23 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-25 16:24:23 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-25 16:24:23 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-25 16:24:23 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-25 16:24:24 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-07-25 16:24:24 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-25 16:24:24 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-25 16:24:24 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-25 16:24:25 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-25 16:24:25 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-25 16:24:26 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-25 16:24:27 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-07-25 16:24:27 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-25 16:24:27 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-25 16:24:27 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-25 16:24:30 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-25 16:24:30 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-25 16:24:30 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-07-25 16:24:30 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-07-25 16:24:31 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-07-25 16:24:31 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-07-25 16:24:32 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-07-25 16:24:32 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-07-25 16:24:44 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-07-25 16:24:44 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-07-25 16:24:44 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-07-25 16:24:44 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-07-25 16:24:50 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-07-25 16:24:50 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-07-25 16:24:51 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-07-25 16:24:51 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-07-25 16:24:52 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-07-25 16:24:52 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-07-25 16:25:08 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-07-25 16:25:08 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-07-25 16:25:09 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-07-25 16:25:09 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-07-25 16:25:09 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-07-25 16:25:09 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-07-25 16:25:27 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-07-25 16:25:27 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-07-25 16:25:28 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-07-25 16:25:28 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-07-25 16:25:28 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-07-25 16:25:28 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-07-25 16:25:39 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '00ac3742-4342-4758-b027-486a6e49ce4d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-25 16:25:39 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-25 16:25:52 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-07-25 16:25:52 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-07-25 16:25:53 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-07-25 16:25:53 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-07-25 16:25:53 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-07-25 16:25:53 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-07-25 16:26:15 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-07-25 16:26:15 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-07-25 16:26:15 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-07-25 16:26:15 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-25 16:26:15 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-25 16:26:15 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-25 16:26:20 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-25 16:26:20 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-25 16:26:20 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-07-25 16:26:20 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-07-25 16:26:21 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-25 16:26:21 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-25 16:26:21 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-07-25 16:26:21 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-07-25 16:26:21 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-07-25 16:26:21 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-07-25 16:26:21 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-07-25 16:26:21 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-25 16:26:22 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-25 16:26:22 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-25 16:26:22 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-25 16:26:22 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-25 16:26:22 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-25 16:26:22 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-25 16:26:22 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-25 16:26:22 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-25 16:26:22 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-25 16:26:22 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-25 16:26:22 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-25 16:26:23 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect with illegal peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect with illegal peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect with illegal peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect with illegal peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect with illegal peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect with illegal peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#setup: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#setup ok: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#run: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-25 16:26:24 - INFO Socket: 'run skipped, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID''

2017-07-25 16:26:24 - INFO Socket: 'run skipped, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID''

2017-07-25 16:26:24 - INFO Socket: 'run skipped, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#run ok: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#teardown: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#teardown ok: 'multiConnect properly fails on legal but non-existent peerID''

2017-07-25 16:26:24 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect with invalid syncValue''

2017-07-25 16:26:25 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect with invalid syncValue''

2017-07-25 16:26:25 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect with invalid syncValue''

2017-07-25 16:26:25 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect with invalid syncValue''

2017-07-25 16:26:25 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect with invalid syncValue''

2017-07-25 16:26:25 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect with invalid syncValue''

2017-07-25 16:26:25 - DEBUG UnitTestFramework: '#setup: 'cannot call disconnect with invalid peer id''

2017-07-25 16:26:25 - DEBUG UnitTestFramework: '#setup ok: 'cannot call disconnect with invalid peer id''

2017-07-25 16:26:25 - DEBUG UnitTestFramework: '#run: 'cannot call disconnect with invalid peer id''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#run ok: 'cannot call disconnect with invalid peer id''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#teardown: 'cannot call disconnect with invalid peer id''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call disconnect with invalid peer id''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#setup: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#setup ok: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#run: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#run ok: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#teardown: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#teardown ok: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#setup: 'Get same port when trying to connect multiple times on iOS''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#setup ok: 'Get same port when trying to connect multiple times on iOS''

2017-07-25 16:26:26 - DEBUG UnitTestFramework: '#run: 'Get same port when trying to connect multiple times on iOS''

2017-07-25 16:26:41 - DEBUG UnitTestFramework: '#run ok: 'Get same port when trying to connect multiple times on iOS''

2017-07-25 16:26:41 - DEBUG UnitTestFramework: '#teardown: 'Get same port when trying to connect multiple times on iOS''

2017-07-25 16:26:42 - DEBUG UnitTestFramework: '#teardown ok: 'Get same port when trying to connect multiple times on iOS''

2017-07-25 16:26:42 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-07-25 16:26:42 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-07-25 16:26:42 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-07-25 16:26:42 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-25 16:26:42 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-25 16:26:43 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-07-25 16:26:43 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-07-25 16:26:43 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-07-25 16:26:44 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-07-25 16:26:44 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-07-25 16:26:44 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-07-25 16:26:44 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-07-25 16:26:44 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-25 16:26:44 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-25 16:26:44 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-07-25 16:26:44 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-07-25 16:26:44 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-07-25 16:26:44 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-07-25 16:26:44 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-07-25 16:26:44 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-07-25 16:26:45 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-25 16:26:45 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-25 16:26:45 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-07-25 16:26:45 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-25 16:26:45 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-25 16:26:45 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-07-25 16:26:45 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-07-25 16:26:46 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-25 16:26:46 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-25 16:26:46 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-07-25 16:26:46 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''

2017-07-25 16:26:46 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-07-25 16:26:46 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-07-25 16:26:46 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-07-25 16:26:46 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-07-25 16:26:46 - DEBUG UnitTestFramework: '#run: 'no peer discovery''

2017-07-25 16:26:46 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-25 16:26:46 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-25 16:26:46 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-07-25 16:26:46 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''

2017-07-25 16:26:46 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-07-25 16:26:46 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-07-25 16:26:46 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-07-25 16:26:49 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-07-25 16:26:49 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-07-25 16:26:49 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-07-25 16:26:49 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-07-25 16:26:49 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-07-25 16:26:49 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-25 16:26:50 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-25 16:26:51 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-25 16:26:52 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-25 16:26:53 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-07-25 16:26:53 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-25 16:26:54 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-25 16:26:54 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-25 16:26:54 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-25 16:26:54 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''
2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-07-25 16:26:55 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-07-25 16:26:56 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-07-25 16:26:57 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-07-25 16:26:57 - DEBUG UnitTestFramework: '#setup: 'Single local http request''

2017-07-25 16:26:57 - DEBUG UnitTestFramework: '#setup ok: 'Single local http request''

2017-07-25 16:26:57 - DEBUG UnitTestFramework: '#run: 'Single local http request''

2017-07-25 16:26:57 - DEBUG UnitTestFramework: '#run ok: 'Single local http request''

2017-07-25 16:26:57 - DEBUG UnitTestFramework: '#teardown: 'Single local http request''

2017-07-25 16:26:57 - DEBUG UnitTestFramework: '#teardown ok: 'Single local http request''

2017-07-25 16:26:57 - DEBUG UnitTestFramework: '#setup: 'Single coordinated request ios native''

2017-07-25 16:26:57 - DEBUG UnitTestFramework: '#setup ok: 'Single coordinated request ios native''

2017-07-25 16:26:57 - DEBUG UnitTestFramework: '#run: 'Single coordinated request ios native''

2017-07-25 16:27:04 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '5130bc92-79b3-46c1-9f89-25b73a617405', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-25 16:27:04 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-25 16:27:04 - INFO TestFramework: 'all required 2 devices are present for platformName: 'android''

2017-07-25 16:27:04 - ERROR HttpServer: 'unexpected server error: 'undefined''

2017-07-25 16:27:04 - ERROR TestServerProcess: 'uncaught exception, error: 'Error', stack: 'Error
    at Server._error (/home/pi/Test/server_13228325722939a4/test/TestServer/HttpServer.js:78:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at Socket.onerror (/home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/lib/socket.js:401:10)
    at Client.onerror (/home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/lib/client.js:210:24)
    at Client.ondata (/home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/lib/client.js:177:10)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)
    at Receiver.ontext (/home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/WebSocket.js:841:10)
    at /home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:536:18
    at /home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:368:7
    at /home/pi/Test/server_13228325722939a4/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/PerMessageDeflate.js:249:5''

2017-07-25 16:27:04 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-07-25 16:27:04 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-07-25 16:27:04 - INFO HttpServer: 'Socket to device name: 'Apple-Iphone6sPlus-1' disconnected, reason: 'undefined''

2017-07-25 16:27:04 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-07-25 16:27:04 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: copying android script192.168.1.52
copying android script192.168.1.53
Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: 25/7/2017@18:20:48 Getting the list of iOS devices 
25/7/2017@18:20:53 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
25/7/2017@18:20:53 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
25/7/2017@18:20:53 ios: device name: Iphone6sPlus-1 , device identifier:  f70cda60583ea0f895d05ea355cd125983c27594
25/7/2017@18:20:53 Deploying iOS test app 
25/7/2017@18:20:53 uninstalling the application 
25/7/2017@18:20:53 installing the application 
25/7/2017@18:20:54 ios.run: bffa901fefdea07f59339a6737776943349f5077 /Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app
25/7/2017@18:20:54 ios.run: 00b2e2c1b30013159b62125fe7f097bdcc055c10 /Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app
25/7/2017@18:20:54 ios.run: f70cda60583ea0f895d05ea355cd125983c27594 /Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app

```
###Android Logs
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

Error! Unexpected exit on device ce061606c181d71003 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce061606c181d71003 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/13228325722939a4_Updated_versions_of_3rd_party_libraries_jareksl/thali03_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce0616068b9f212302 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
Stopping App:com.thaliproject.thalitest ce0616068b9f212302 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/13228325722939a4_Updated_versions_of_3rd_party_libraries_jareksl/thali04_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/13228325722939a4_Updated_versions_of_3rd_party_libraries_jareksl/iOS_iphone-5s-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/13228325722939a4_Updated_versions_of_3rd_party_libraries_jareksl/iOS_iphone-5s-1.md)

[Iphone6sPlus-1](https://github.com/ThaliTester/TestResults/blob/13228325722939a4_Updated_versions_of_3rd_party_libraries_jareksl/iOS_Iphone6sPlus-1.md)





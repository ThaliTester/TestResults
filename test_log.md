#### Test 113351851b596518 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-22 06:55:38 - INFO HttpServer: 'listening on *:3000'

2017-06-22 06:55:43 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'ea0576ad-2b78-42b0-a0cc-d37f2de8d8a9', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-22 06:55:43 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-22 06:55:44 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '15d53771-f113-4f45-b999-4855cb280346', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-22 06:55:44 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-22 06:55:45 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'ea0576ad-2b78-42b0-a0cc-d37f2de8d8a9', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-22 06:55:45 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: 'ea0576ad-2b78-42b0-a0cc-d37f2de8d8a9', platformName: 'ios''

2017-06-22 06:55:46 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '15d53771-f113-4f45-b999-4855cb280346', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-22 06:55:46 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: '15d53771-f113-4f45-b999-4855cb280346', platformName: 'ios''

2017-06-22 06:55:47 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '33e04107-f15f-4eff-b893-1a0c9f51a2b0', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-22 06:55:47 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-22 06:55:47 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-22 06:55:47 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-22 06:55:47 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-22 06:55:48 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '33e04107-f15f-4eff-b893-1a0c9f51a2b0', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-22 06:55:48 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '33e04107-f15f-4eff-b893-1a0c9f51a2b0', platformName: 'ios''

2017-06-22 06:55:58 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-22 06:55:59 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-22 06:56:00 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-22 06:56:00 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-22 06:56:01 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-22 06:56:01 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-22 06:56:02 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-22 06:56:02 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-22 06:56:03 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-22 06:56:03 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-22 06:56:03 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-22 06:56:03 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-22 06:56:05 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-22 06:56:05 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:56:06 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:56:06 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:56:08 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:56:08 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:56:09 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:56:09 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:56:23 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:56:23 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:56:33 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:56:33 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:56:33 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:56:33 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:56:34 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:56:34 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:56:34 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-22 06:56:34 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-22 06:56:34 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-22 06:56:34 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:56:34 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:56:35 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:56:35 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:56:36 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:56:36 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:56:37 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:56:37 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:56:37 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:56:37 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:56:37 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:56:37 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:56:37 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:56:38 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:56:38 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:56:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:56:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:56:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:56:38 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:56:38 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:56:38 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:56:38 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:56:40 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:56:40 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:56:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:56:41 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:56:41 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:56:41 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:56:41 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:56:42 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:56:42 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-22 06:56:42 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-22 06:56:42 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-22 06:56:42 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-22 06:56:42 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-22 06:56:43 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-22 06:56:43 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-22 06:56:44 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-22 06:56:44 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-22 06:56:51 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-22 06:56:51 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-22 06:56:53 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-22 06:56:53 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-22 06:56:58 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-22 06:56:58 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-22 06:57:00 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-22 06:57:00 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-22 06:57:07 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-22 06:57:07 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-22 06:57:08 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'c3c81f3b-059f-4dd5-a73c-8c203e52be1b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-22 06:57:08 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-22 06:57:15 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-22 06:57:15 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-22 06:57:18 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-22 06:57:18 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-22 06:57:19 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-22 06:57:19 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-22 06:57:20 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '5e9c94b3-134d-4ac9-8e5f-5b6c705280db', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-22 06:57:20 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-22 06:57:23 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-22 06:57:23 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-22 06:57:25 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-22 06:57:25 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-22 06:57:27 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-22 06:57:27 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-22 06:57:27 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-22 06:57:27 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-22 06:57:27 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-22 06:57:27 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-22 06:57:28 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-22 06:57:28 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-22 06:57:31 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-22 06:57:31 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-22 06:57:35 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-22 06:57:35 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-22 06:57:36 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-22 06:57:36 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-22 06:57:37 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-22 06:57:37 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-22 06:57:37 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-22 06:57:37 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-22 06:57:37 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-22 06:57:37 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-22 06:57:39 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-22 06:57:39 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-22 06:57:48 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-22 06:57:48 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-22 06:57:50 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-22 06:57:50 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-22 06:57:51 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-22 06:57:51 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-22 06:57:51 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-22 06:57:51 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-22 06:57:51 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-22 06:57:51 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-06-22 06:57:52 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-06-22 06:57:52 - DEBUG UnitTestFramework: '#run: 'skip''

2017-06-22 06:57:53 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-22 06:57:53 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-22 06:57:53 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-22 06:57:53 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-06-22 06:57:53 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-06-22 06:57:57 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-06-22 06:57:57 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-06-22 06:58:03 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-06-22 06:58:03 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-06-22 06:58:03 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-22 06:58:04 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-22 06:58:15 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-22 06:58:15 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-06-22 06:58:15 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-06-22 06:58:20 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-06-22 06:58:20 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-22 06:58:21 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-22 06:58:21 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-22 06:58:21 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-22 06:58:21 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-22 06:58:23 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-22 06:58:23 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-22 06:58:39 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-22 06:58:39 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-22 06:58:41 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-22 06:58:41 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-22 06:58:47 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '628466ff-3e25-4729-9137-f180d46cc430', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-22 06:58:47 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-22 06:58:47 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-06-22 06:58:47 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-06-22 06:58:47 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-22 06:58:48 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-22 06:58:48 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-22 06:58:48 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-22 06:58:48 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-22 06:58:49 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-22 06:58:49 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-22 06:58:49 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-22 06:58:49 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-22 06:58:49 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-22 06:58:49 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:58:50 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:58:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-22 06:58:51 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-22 06:58:52 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run: 'skip''

2017-06-22 06:58:53 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-22 06:58:53 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-22 06:58:53 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-06-22 06:58:53 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-22 06:58:53 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-22 06:58:53 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-22 06:58:53 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-22 06:58:54 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''
2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-22 06:58:55 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-22 06:58:56 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-22 06:58:56 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-22 06:58:56 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-22 06:58:56 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 06:58:56 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 06:58:56 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 06:58:57 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 06:58:57 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 06:58:58 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 06:58:58 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 06:58:58 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 06:58:58 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 06:58:58 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 06:58:58 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 06:58:58 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 06:58:58 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 06:58:58 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 06:58:58 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 06:58:59 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 06:58:59 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 06:58:59 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 06:58:59 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 06:58:59 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 06:58:59 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-22 06:59:00 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-22 06:59:02 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-22 06:59:02 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-22 06:59:03 - INFO Socket: 'run skipped, test: 'Can connect to a remote peer', event: 'run_Can connect to a remote peer''

2017-06-22 06:59:03 - INFO Socket: 'run skipped, test: 'Can connect to a remote peer', event: 'run_Can connect to a remote peer''

2017-06-22 06:59:03 - INFO Socket: 'run skipped, test: 'Can connect to a remote peer', event: 'run_Can connect to a remote peer''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-06-22 06:59:03 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift data', event: 'run_Can shift data''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift data', event: 'run_Can shift data''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift data', event: 'run_Can shift data''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift data securely', event: 'run_Can shift data securely''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift data securely', event: 'run_Can shift data securely''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift data securely', event: 'run_Can shift data securely''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift large amounts of data', event: 'run_Can shift large amounts of data''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift large amounts of data', event: 'run_Can shift large amounts of data''

2017-06-22 06:59:04 - INFO Socket: 'run skipped, test: 'Can shift large amounts of data', event: 'run_Can shift large amounts of data''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-06-22 06:59:04 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 06:59:05 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 06:59:05 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 06:59:07 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-22 06:59:07 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-22 06:59:09 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-22 06:59:09 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-22 06:59:11 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-22 06:59:11 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-22 06:59:12 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 06:59:12 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 06:59:13 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 06:59:13 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-06-22 06:59:14 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-06-22 06:59:14 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-06-22 06:59:14 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-22 06:59:14 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-22 06:59:19 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-22 06:59:19 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-06-22 06:59:19 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-06-22 06:59:22 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-06-22 06:59:22 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 06:59:23 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-22 06:59:23 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-22 06:59:26 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 06:59:26 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 06:59:32 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 06:59:32 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 06:59:35 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 06:59:35 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 06:59:36 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-22 06:59:36 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-22 06:59:36 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 06:59:36 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 06:59:36 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 06:59:36 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 06:59:36 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 06:59:36 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-06-22 06:59:36 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-06-22 06:59:36 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-06-22 06:59:42 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-22 06:59:42 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-22 06:59:45 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-06-22 06:59:45 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-06-22 06:59:46 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-06-22 06:59:46 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 06:59:48 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 06:59:48 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 06:59:48 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-22 06:59:48 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-22 06:59:57 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-22 06:59:57 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-22 07:00:01 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-22 07:00:01 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-22 07:00:09 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-22 07:00:09 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-22 07:00:27 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-22 07:00:27 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-22 07:00:40 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-22 07:00:40 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-22 07:00:41 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-22 07:00:41 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-22 07:00:41 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-22 07:00:41 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-22 07:00:42 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-22 07:00:42 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-22 07:00:43 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-22 07:00:43 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-22 07:00:43 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-22 07:00:43 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-22 07:00:43 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-22 07:00:45 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-22 07:00:45 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-22 07:00:45 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-22 07:00:45 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-22 07:00:45 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-22 07:00:45 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-22 07:00:45 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-22 07:00:45 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-22 07:00:45 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-22 07:00:45 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-22 07:00:45 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-22 07:00:46 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-22 07:00:46 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-22 07:00:49 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-22 07:00:49 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 07:00:50 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 07:00:50 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 07:00:53 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 07:00:53 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 07:00:55 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-22 07:00:55 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 07:00:55 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 07:00:55 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 07:00:55 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 07:00:55 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 07:00:55 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-22 07:00:55 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 07:00:56 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 07:00:56 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 07:00:57 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 07:00:57 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 07:01:00 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-22 07:01:00 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 07:01:00 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 07:01:00 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 07:01:02 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 07:01:02 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 07:01:03 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-22 07:01:03 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 07:01:13 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 07:01:13 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 07:01:15 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 07:01:15 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 07:01:16 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-22 07:01:16 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-22 07:01:21 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-22 07:01:21 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-22 07:01:23 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-22 07:01:23 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-22 07:01:28 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-22 07:01:28 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-22 07:01:43 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-22 07:01:43 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-22 07:01:43 - INFO Socket: 'run skipped, test: 'Can connect to a remote peer', event: 'run_Can connect to a remote peer''

2017-06-22 07:01:43 - INFO Socket: 'run skipped, test: 'Can connect to a remote peer', event: 'run_Can connect to a remote peer''

2017-06-22 07:01:46 - INFO Socket: 'run skipped, test: 'Can connect to a remote peer', event: 'run_Can connect to a remote peer''

2017-06-22 07:01:46 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-06-22 07:01:46 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-06-22 07:01:53 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-06-22 07:01:53 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-06-22 07:01:54 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-06-22 07:01:54 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-06-22 07:01:54 - INFO Socket: 'run skipped, test: 'Can shift data', event: 'run_Can shift data''

2017-06-22 07:01:54 - INFO Socket: 'run skipped, test: 'Can shift data', event: 'run_Can shift data''

2017-06-22 07:01:58 - INFO Socket: 'run skipped, test: 'Can shift data', event: 'run_Can shift data''

2017-06-22 07:01:58 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-06-22 07:01:58 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-06-22 07:01:59 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-06-22 07:01:59 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-06-22 07:02:00 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-06-22 07:02:00 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-06-22 07:02:00 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-22 07:02:00 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-22 07:02:10 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-22 07:02:10 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-06-22 07:02:10 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-06-22 07:02:18 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-06-22 07:02:18 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-06-22 07:02:24 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-06-22 07:02:24 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-06-22 07:02:24 - INFO Socket: 'run skipped, test: 'Can shift data securely', event: 'run_Can shift data securely''

2017-06-22 07:02:25 - INFO Socket: 'run skipped, test: 'Can shift data securely', event: 'run_Can shift data securely''

2017-06-22 07:02:26 - INFO Socket: 'run skipped, test: 'Can shift data securely', event: 'run_Can shift data securely''

2017-06-22 07:02:26 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-06-22 07:02:26 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-06-22 07:02:27 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-06-22 07:02:27 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-06-22 07:02:27 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-06-22 07:02:27 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-06-22 07:02:28 - INFO Socket: 'run skipped, test: 'Can shift large amounts of data', event: 'run_Can shift large amounts of data''

2017-06-22 07:02:28 - INFO Socket: 'run skipped, test: 'Can shift large amounts of data', event: 'run_Can shift large amounts of data''

2017-06-22 07:02:29 - INFO Socket: 'run skipped, test: 'Can shift large amounts of data', event: 'run_Can shift large amounts of data''

2017-06-22 07:02:29 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-06-22 07:02:29 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-06-22 07:02:32 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-06-22 07:02:32 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 07:02:32 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 07:02:32 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 07:02:38 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 07:02:38 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 07:02:38 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-22 07:02:38 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-06-22 07:02:39 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-06-22 07:02:39 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-06-22 07:02:39 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-22 07:02:39 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-22 07:02:39 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-22 07:02:39 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-06-22 07:02:39 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-06-22 07:02:39 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-06-22 07:02:39 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 07:02:39 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 07:02:39 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 07:02:39 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 07:02:39 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 07:02:40 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-22 07:02:40 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 07:02:44 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 07:02:44 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 07:02:44 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-06-22 07:02:48 - ERROR UnitTestFramework: '#run failed: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', error: 'TimeoutError: timeout exceeded, event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection_finished', test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'', stack: 'TimeoutError: timeout exceeded, event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection_finished', test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
    at afterTimeout (/home/pi/Test/server_113351851b596518/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851b596518/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-22 07:02:48 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection_finished', test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'', stack: 'TimeoutError: timeout exceeded, event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection_finished', test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
    at afterTimeout (/home/pi/Test/server_113351851b596518/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851b596518/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-22 07:02:51 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-06-22 07:03:08 - INFO Socket: 'run skipped, test: 'cannot call connect when start listening for advertisements is not active', event: 'run_cannot call connect when start listening for advertisements is not active''

2017-06-22 07:03:08 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 07:03:08 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 07:03:26 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-22 07:03:26 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-06-22 07:03:32 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-06-22 07:03:32 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-06-22 07:03:33 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-06-22 07:03:33 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-06-22 07:03:33 - INFO Socket: 'run skipped, test: 'Get error when trying to double connect to a peer on Android', event: 'run_Get error when trying to double connect to a peer on Android''

2017-06-22 07:03:33 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-06-22 07:03:33 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-06-22 07:03:34 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-06-22 07:03:34 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 07:03:34 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 07:03:34 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 07:03:34 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 07:03:35 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 07:03:35 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 07:03:35 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 07:03:35 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 07:03:36 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-22 07:03:36 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-22 07:03:36 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-22 07:03:36 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-22 07:03:36 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-22 07:03:36 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-22 07:03:36 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-22 07:03:36 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-22 07:03:36 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-22 07:03:37 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-22 07:03:37 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-22 07:03:38 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-22 07:03:38 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-22 07:03:38 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-22 07:03:38 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-22 07:03:38 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-22 07:03:38 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-22 07:03:38 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - INFO Socket: 'run skipped, test: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer', event: 'run_#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-22 07:03:39 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect when start listening for advertisements is not active''

2017-06-22 07:03:39 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-06-22 07:03:39 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect when start listening for advertisements is not active''

2017-06-22 07:03:40 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-06-22 07:03:40 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect when start listening for advertisements is not active''

2017-06-22 07:03:52 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect when start listening for advertisements is not active''

2017-06-22 07:03:52 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect with illegal peerID''

2017-06-22 07:04:00 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect with illegal peerID''

2017-06-22 07:04:00 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect with illegal peerID''

2017-06-22 07:04:02 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect with illegal peerID''

2017-06-22 07:04:02 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect with illegal peerID''

2017-06-22 07:04:03 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect with illegal peerID''

2017-06-22 07:04:03 - DEBUG UnitTestFramework: '#setup: 'multiConnect properly fails on legal but non-existent peerID''

2017-06-22 07:04:12 - DEBUG UnitTestFramework: '#setup ok: 'multiConnect properly fails on legal but non-existent peerID''

2017-06-22 07:04:12 - DEBUG UnitTestFramework: '#run: 'multiConnect properly fails on legal but non-existent peerID''

2017-06-22 07:04:22 - DEBUG UnitTestFramework: '#run ok: 'multiConnect properly fails on legal but non-existent peerID''

2017-06-22 07:04:22 - DEBUG UnitTestFramework: '#teardown: 'multiConnect properly fails on legal but non-existent peerID''

2017-06-22 07:04:26 - DEBUG UnitTestFramework: '#teardown ok: 'multiConnect properly fails on legal but non-existent peerID''

2017-06-22 07:04:26 - DEBUG UnitTestFramework: '#setup: 'cannot call multiConnect with invalid syncValue''

2017-06-22 07:04:27 - DEBUG UnitTestFramework: '#setup ok: 'cannot call multiConnect with invalid syncValue''

2017-06-22 07:04:27 - DEBUG UnitTestFramework: '#run: 'cannot call multiConnect with invalid syncValue''

2017-06-22 07:04:31 - DEBUG UnitTestFramework: '#run ok: 'cannot call multiConnect with invalid syncValue''

2017-06-22 07:04:31 - DEBUG UnitTestFramework: '#teardown: 'cannot call multiConnect with invalid syncValue''

2017-06-22 07:04:32 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call multiConnect with invalid syncValue''

2017-06-22 07:04:32 - DEBUG UnitTestFramework: '#setup: 'disconnect doesn't fail on bad peer id''

2017-06-22 07:04:32 - DEBUG UnitTestFramework: '#setup ok: 'disconnect doesn't fail on bad peer id''

2017-06-22 07:04:32 - DEBUG UnitTestFramework: '#run: 'disconnect doesn't fail on bad peer id''

2017-06-22 07:04:35 - DEBUG UnitTestFramework: '#run ok: 'disconnect doesn't fail on bad peer id''

2017-06-22 07:04:35 - DEBUG UnitTestFramework: '#teardown: 'disconnect doesn't fail on bad peer id''

2017-06-22 07:04:36 - DEBUG UnitTestFramework: '#teardown ok: 'disconnect doesn't fail on bad peer id''

2017-06-22 07:04:36 - DEBUG UnitTestFramework: '#setup: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-06-22 07:04:43 - DEBUG UnitTestFramework: '#setup ok: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-06-22 07:04:43 - DEBUG UnitTestFramework: '#run: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-06-22 07:04:50 - DEBUG UnitTestFramework: '#run ok: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-06-22 07:04:50 - DEBUG UnitTestFramework: '#teardown: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-06-22 07:04:51 - DEBUG UnitTestFramework: '#teardown ok: 'disconnect doesn't fail on plausible but bogus peer ID''

2017-06-22 07:04:51 - DEBUG UnitTestFramework: '#setup: 'Get same port when trying to connect multiple times on iOS''

2017-06-22 07:04:54 - DEBUG UnitTestFramework: '#setup ok: 'Get same port when trying to connect multiple times on iOS''

2017-06-22 07:04:54 - DEBUG UnitTestFramework: '#run: 'Get same port when trying to connect multiple times on iOS''

2017-06-22 07:04:54 - INFO Socket: 'run skipped, test: 'Get same port when trying to connect multiple times on iOS', event: 'run_Get same port when trying to connect multiple times on iOS''

2017-06-22 07:04:55 - INFO Socket: 'run skipped, test: 'Get same port when trying to connect multiple times on iOS', event: 'run_Get same port when trying to connect multiple times on iOS''

2017-06-22 07:05:06 - INFO Socket: 'run skipped, test: 'Get same port when trying to connect multiple times on iOS', event: 'run_Get same port when trying to connect multiple times on iOS''

2017-06-22 07:05:06 - DEBUG UnitTestFramework: '#run ok: 'Get same port when trying to connect multiple times on iOS''

2017-06-22 07:05:06 - DEBUG UnitTestFramework: '#teardown: 'Get same port when trying to connect multiple times on iOS''

2017-06-22 07:05:07 - DEBUG UnitTestFramework: '#teardown ok: 'Get same port when trying to connect multiple times on iOS''

2017-06-22 07:05:07 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-06-22 07:05:08 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-06-22 07:05:08 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-06-22 07:05:09 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-06-22 07:05:09 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-06-22 07:05:11 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-06-22 07:05:11 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-06-22 07:05:11 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-06-22 07:05:13 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-06-22 07:05:13 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-06-22 07:05:14 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-06-22 07:05:14 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-06-22 07:05:15 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-06-22 07:05:15 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-06-22 07:05:15 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-06-22 07:05:15 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-06-22 07:05:15 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-06-22 07:05:16 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-06-22 07:05:16 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-06-22 07:05:16 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-06-22 07:05:16 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-06-22 07:05:16 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-06-22 07:05:16 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-06-22 07:05:16 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-06-22 07:05:16 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-06-22 07:05:16 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-06-22 07:05:17 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-06-22 07:05:17 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-06-22 07:05:18 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-06-22 07:05:18 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-06-22 07:05:19 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-06-22 07:05:19 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-06-22 07:05:19 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-06-22 07:05:19 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-06-22 07:05:19 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-06-22 07:05:20 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-06-22 07:05:20 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-06-22 07:05:40 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-06-22 07:05:40 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-06-22 07:05:40 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-06-22 07:05:40 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-06-22 07:05:46 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-06-22 07:05:46 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''

2017-06-22 07:05:46 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-06-22 07:05:48 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-06-22 07:05:48 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-06-22 07:05:54 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-06-22 07:05:54 - DEBUG UnitTestFramework: '#run: 'no peer discovery''

2017-06-22 07:05:54 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-06-22 07:05:55 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-06-22 07:06:02 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-06-22 07:06:02 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''

2017-06-22 07:06:02 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-06-22 07:06:06 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-06-22 07:06:06 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-06-22 07:06:11 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-06-22 07:06:11 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-06-22 07:06:14 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-06-22 07:06:14 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-06-22 07:06:16 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-06-22 07:06:16 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-06-22 07:06:25 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-06-22 07:06:25 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-06-22 07:06:27 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-06-22 07:06:27 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-06-22 07:06:31 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-06-22 07:06:31 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-06-22 07:06:33 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-06-22 07:06:33 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-06-22 07:06:35 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-06-22 07:06:35 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-06-22 07:06:38 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-06-22 07:06:38 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-06-22 07:06:52 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-06-22 07:06:52 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-06-22 07:07:18 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-06-22 07:07:18 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-06-22 07:07:22 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-06-22 07:07:22 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-06-22 07:07:25 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-06-22 07:07:25 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-06-22 07:07:30 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-06-22 07:07:30 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-06-22 07:07:33 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-06-22 07:07:33 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-06-22 07:07:34 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-06-22 07:07:34 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-06-22 07:07:35 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-06-22 07:07:35 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-06-22 07:07:37 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-06-22 07:07:37 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-22 07:07:37 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-22 07:07:37 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-22 07:07:38 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-22 07:07:38 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-22 07:07:41 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-22 07:07:41 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-06-22 07:07:45 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-06-22 07:07:45 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-06-22 07:07:47 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-06-22 07:07:47 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-06-22 07:07:47 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-06-22 07:07:47 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-22 07:07:51 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-22 07:07:51 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-22 07:07:52 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-22 07:07:52 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-22 07:08:10 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-22 07:08:10 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-22 07:08:13 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-22 07:08:13 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-22 07:08:13 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-22 07:08:13 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-22 07:08:14 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-22 07:08:14 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-06-22 07:08:23 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-06-22 07:08:23 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-06-22 07:08:29 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-06-22 07:08:29 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-06-22 07:08:38 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-06-22 07:08:38 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-06-22 07:08:39 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-06-22 07:08:39 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-06-22 07:08:39 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-06-22 07:08:39 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-06-22 07:08:40 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''

2017-06-22 07:08:40 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-06-22 07:08:41 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-06-22 07:08:41 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-06-22 07:08:45 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-06-22 07:08:45 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-06-22 07:08:49 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-06-22 07:08:49 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-06-22 07:08:56 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-06-22 07:08:56 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-06-22 07:09:04 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-06-22 07:09:04 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-06-22 07:09:05 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-06-22 07:09:05 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-06-22 07:09:06 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-06-22 07:09:06 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-06-22 07:09:08 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-06-22 07:09:08 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-06-22 07:09:17 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-06-22 07:09:17 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-06-22 07:09:22 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-06-22 07:09:22 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-06-22 07:09:29 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-06-22 07:09:29 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-06-22 07:09:47 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-06-22 07:09:47 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-06-22 07:09:55 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-06-22 07:09:55 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-06-22 07:10:19 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-06-22 07:10:19 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-06-22 07:10:20 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-06-22 07:10:20 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-06-22 07:10:22 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-22 07:10:22 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-06-22 07:10:22 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-22 07:10:22 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-06-22 07:10:23 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-22 07:10:23 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-22 07:10:24 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-22 07:10:24 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-22 07:10:24 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-22 07:10:25 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-22 07:10:27 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-22 07:10:27 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-22 07:10:39 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-22 07:10:39 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-22 07:10:45 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-22 07:10:45 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-22 07:10:46 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-22 07:10:46 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-06-22 07:10:46 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-06-22 07:10:46 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-06-22 07:10:47 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-06-22 07:10:47 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-06-22 07:10:49 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-06-22 07:10:49 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-22 07:11:04 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-22 07:11:04 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-22 07:11:07 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-22 07:11:07 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-22 07:11:08 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-22 07:11:08 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-22 07:11:08 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-22 07:11:08 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-22 07:11:10 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-22 07:11:10 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-22 07:11:14 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-22 07:11:14 - DEBUG UnitTestFramework: '#setup: 'can get the network status before starting''

2017-06-22 07:11:21 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status before starting''

2017-06-22 07:11:21 - DEBUG UnitTestFramework: '#run: 'can get the network status before starting''

2017-06-22 07:11:39 - DEBUG UnitTestFramework: '#run ok: 'can get the network status before starting''

2017-06-22 07:11:39 - DEBUG UnitTestFramework: '#teardown: 'can get the network status before starting''

2017-06-22 07:11:46 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status before starting''

2017-06-22 07:11:46 - DEBUG UnitTestFramework: '#setup: 'error returned with bad router''

2017-06-22 07:12:03 - DEBUG UnitTestFramework: '#setup ok: 'error returned with bad router''

2017-06-22 07:12:03 - DEBUG UnitTestFramework: '#run: 'error returned with bad router''

2017-06-22 07:12:13 - DEBUG UnitTestFramework: '#run ok: 'error returned with bad router''

2017-06-22 07:12:13 - DEBUG UnitTestFramework: '#teardown: 'error returned with bad router''

2017-06-22 07:12:13 - DEBUG UnitTestFramework: '#teardown ok: 'error returned with bad router''

2017-06-22 07:12:13 - DEBUG UnitTestFramework: '#setup: 'all services are started when we call start''

2017-06-22 07:12:14 - DEBUG UnitTestFramework: '#setup ok: 'all services are started when we call start''

2017-06-22 07:12:14 - DEBUG UnitTestFramework: '#run: 'all services are started when we call start''

2017-06-22 07:12:16 - DEBUG UnitTestFramework: '#run ok: 'all services are started when we call start''

2017-06-22 07:12:16 - DEBUG UnitTestFramework: '#teardown: 'all services are started when we call start''

2017-06-22 07:12:16 - DEBUG UnitTestFramework: '#teardown ok: 'all services are started when we call start''

2017-06-22 07:12:16 - DEBUG UnitTestFramework: '#setup: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-22 07:12:18 - DEBUG UnitTestFramework: '#setup ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-22 07:12:18 - DEBUG UnitTestFramework: '#run: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-22 07:12:18 - DEBUG UnitTestFramework: '#run ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-22 07:12:18 - DEBUG UnitTestFramework: '#teardown: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-22 07:12:19 - DEBUG UnitTestFramework: '#teardown ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-22 07:12:19 - DEBUG UnitTestFramework: '#setup: 'all services are stopped when we call stop''

2017-06-22 07:12:19 - DEBUG UnitTestFramework: '#setup ok: 'all services are stopped when we call stop''

2017-06-22 07:12:19 - DEBUG UnitTestFramework: '#run: 'all services are stopped when we call stop''

2017-06-22 07:12:22 - DEBUG UnitTestFramework: '#run ok: 'all services are stopped when we call stop''

2017-06-22 07:12:22 - DEBUG UnitTestFramework: '#teardown: 'all services are stopped when we call stop''

2017-06-22 07:12:26 - DEBUG UnitTestFramework: '#teardown ok: 'all services are stopped when we call stop''

2017-06-22 07:12:26 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is properly hooked up''

2017-06-22 07:12:30 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is properly hooked up''

2017-06-22 07:12:30 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is properly hooked up''

2017-06-22 07:12:30 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is properly hooked up', event: 'run_make sure terminateConnection is properly hooked up''

2017-06-22 07:12:30 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is properly hooked up', event: 'run_make sure terminateConnection is properly hooked up''

2017-06-22 07:12:42 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is properly hooked up', event: 'run_make sure terminateConnection is properly hooked up''

2017-06-22 07:12:42 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is properly hooked up''

2017-06-22 07:12:42 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is properly hooked up''

2017-06-22 07:12:42 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is properly hooked up''

2017-06-22 07:12:42 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-22 07:12:42 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-22 07:12:42 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-22 07:12:44 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-22 07:12:44 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-22 07:12:54 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-22 07:12:54 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is properly hooked up''

2017-06-22 07:12:57 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is properly hooked up''

2017-06-22 07:12:57 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is properly hooked up''

2017-06-22 07:12:57 - INFO Socket: 'run skipped, test: 'make sure terminateListener is properly hooked up', event: 'run_make sure terminateListener is properly hooked up''

2017-06-22 07:12:57 - INFO Socket: 'run skipped, test: 'make sure terminateListener is properly hooked up', event: 'run_make sure terminateListener is properly hooked up''

2017-06-22 07:13:13 - INFO Socket: 'run skipped, test: 'make sure terminateListener is properly hooked up', event: 'run_make sure terminateListener is properly hooked up''

2017-06-22 07:13:13 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is properly hooked up''

2017-06-22 07:13:13 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is properly hooked up''

2017-06-22 07:13:17 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is properly hooked up''

2017-06-22 07:13:17 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is return error if we get called on iOS''

2017-06-22 07:13:18 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is return error if we get called on iOS''

2017-06-22 07:13:18 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is return error if we get called on iOS''

2017-06-22 07:13:25 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is return error if we get called on iOS''

2017-06-22 07:13:25 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is return error if we get called on iOS''

2017-06-22 07:13:33 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is return error if we get called on iOS''

2017-06-22 07:13:33 - DEBUG UnitTestFramework: '#setup: 'make sure we actually call kill connections properly''

2017-06-22 07:13:37 - DEBUG UnitTestFramework: '#setup ok: 'make sure we actually call kill connections properly''

2017-06-22 07:13:37 - DEBUG UnitTestFramework: '#run: 'make sure we actually call kill connections properly''

2017-06-22 07:13:38 - DEBUG UnitTestFramework: '#run ok: 'make sure we actually call kill connections properly''

2017-06-22 07:13:38 - DEBUG UnitTestFramework: '#teardown: 'make sure we actually call kill connections properly''

2017-06-22 07:13:40 - DEBUG UnitTestFramework: '#teardown ok: 'make sure we actually call kill connections properly''

2017-06-22 07:13:40 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-22 07:13:40 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-22 07:13:40 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-22 07:13:40 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-22 07:13:41 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-22 07:13:41 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-22 07:13:41 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-22 07:13:41 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-22 07:13:41 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-22 07:13:41 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-22 07:13:43 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-22 07:13:43 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-22 07:13:43 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager', event: 'run_We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-22 07:13:43 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager', event: 'run_We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-22 07:13:43 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager', event: 'run_We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-22 07:13:43 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-22 07:13:43 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-22 07:13:43 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-22 07:13:43 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:44 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:44 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:44 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:45 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:45 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:45 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:45 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:45 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:45 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:47 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:47 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:47 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:48 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:51 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:51 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:51 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:53 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-22 07:13:53 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-22 07:14:11 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-22 07:14:11 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-22 07:14:12 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-22 07:14:12 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-22 07:14:18 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-22 07:14:18 - DEBUG UnitTestFramework: '#setup: 'make sure bad PSK connections fail''

2017-06-22 07:14:33 - DEBUG UnitTestFramework: '#setup ok: 'make sure bad PSK connections fail''

2017-06-22 07:14:33 - DEBUG UnitTestFramework: '#run: 'make sure bad PSK connections fail''

2017-06-22 07:14:33 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-06-22 07:14:33 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-06-22 07:14:34 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-06-22 07:14:34 - DEBUG UnitTestFramework: '#run ok: 'make sure bad PSK connections fail''

2017-06-22 07:14:34 - DEBUG UnitTestFramework: '#teardown: 'make sure bad PSK connections fail''

2017-06-22 07:14:35 - DEBUG UnitTestFramework: '#teardown ok: 'make sure bad PSK connections fail''

2017-06-22 07:14:35 - DEBUG UnitTestFramework: '#setup: 'peer changes handled from a queue''

2017-06-22 07:14:37 - DEBUG UnitTestFramework: '#setup ok: 'peer changes handled from a queue''

2017-06-22 07:14:37 - DEBUG UnitTestFramework: '#run: 'peer changes handled from a queue''

2017-06-22 07:14:37 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-06-22 07:14:39 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-06-22 07:14:39 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-06-22 07:14:39 - DEBUG UnitTestFramework: '#run ok: 'peer changes handled from a queue''

2017-06-22 07:14:39 - DEBUG UnitTestFramework: '#teardown: 'peer changes handled from a queue''

2017-06-22 07:14:42 - DEBUG UnitTestFramework: '#teardown ok: 'peer changes handled from a queue''

2017-06-22 07:14:42 - DEBUG UnitTestFramework: '#setup: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-22 07:14:49 - DEBUG UnitTestFramework: '#setup ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-22 07:14:49 - DEBUG UnitTestFramework: '#run: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-22 07:14:49 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-22 07:14:49 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-22 07:14:58 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-22 07:14:58 - DEBUG UnitTestFramework: '#run ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-22 07:14:58 - DEBUG UnitTestFramework: '#teardown: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-22 07:15:02 - DEBUG UnitTestFramework: '#teardown ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-22 07:15:02 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-22 07:15:10 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-22 07:15:10 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-22 07:15:11 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-22 07:15:11 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-22 07:15:27 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-22 07:15:27 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-22 07:15:27 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-22 07:15:30 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'transport close''

2017-06-22 07:15:30 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'transport close''

2017-06-22 07:15:30 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'transport close''

2017-06-22 07:16:27 - ERROR UnitTestFramework: '#run failed: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', error: 'TimeoutError: timeout exceeded, event: 'teardown_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received_finished', test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received_finished', test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
    at afterTimeout (/home/pi/Test/server_113351851b596518/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851b596518/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-22 07:16:27 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'teardown_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received_finished', test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received_finished', test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
    at afterTimeout (/home/pi/Test/server_113351851b596518/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851b596518/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-22 07:17:27 - ERROR Socket: 'unexpected error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_113351851b596518/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-22 07:18:27 - ERROR UnitTestFramework: 'unexpected error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_113351851b596518/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-22 07:18:27 - ERROR UnitTestFramework: 'unexpected error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_113351851b596518/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-22 07:18:27 - ERROR UnitTestFramework: 'unexpected error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_113351851b596518/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-22 07:18:27 - DEBUG TestServer: 'completed'

2017-06-22 07:18:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-22 07:18:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-22 07:18:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : Error: Command failed: true
22/6/2017@08:52:10 Getting the list of iOS devices 
22/6/2017@08:52:11 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
22/6/2017@08:52:11 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
22/6/2017@08:52:11 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
22/6/2017@08:52:11 Deploying iOS test app 
22/6/2017@08:52:11 uninstalling the application 
22/6/2017@08:52:11 installing the application 
22/6/2017@09:15:30 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
22/6/2017@09:15:30 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
22/6/2017@09:15:30 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/113351851b596518_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/113351851b596518_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/113351851b596518_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/113351851b596518_CI_sanity_check_jareksl/iOS_server.md)


###Android Logs
####Node name: thali03
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

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851b596518_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851b596518_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)

####Node name: thali05
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

App was succesfully started on ce061606c181d71003

STOP log received from ce061606c181d71003
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851b596518_CI_sanity_check_jareksl/thali05_samsung-SM-G930F.md)





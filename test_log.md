#### Test 1133518510f7eefa Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-05-31 09:56:56 - INFO HttpServer: 'listening on *:3000'

2017-05-31 09:56:58 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '2171239f-a14e-4b44-b561-5c1ef2348159', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 09:56:58 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-05-31 09:57:00 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '2171239f-a14e-4b44-b561-5c1ef2348159', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 09:57:00 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '2171239f-a14e-4b44-b561-5c1ef2348159', platformName: 'ios''

2017-05-31 09:57:01 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'ea09c790-9270-4629-b3c1-db32f92528fc', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 09:57:01 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-05-31 09:57:02 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'ea09c790-9270-4629-b3c1-db32f92528fc', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 09:57:02 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: 'ea09c790-9270-4629-b3c1-db32f92528fc', platformName: 'ios''

2017-05-31 09:57:05 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '795ef283-ac09-4b33-91ec-7832aad2e5b4', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 09:57:05 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-05-31 09:57:05 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-05-31 09:57:05 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-05-31 09:57:05 - DEBUG UnitTestFramework: 'scheduling tests'

2017-05-31 09:57:07 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '795ef283-ac09-4b33-91ec-7832aad2e5b4', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 09:57:07 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: '795ef283-ac09-4b33-91ec-7832aad2e5b4', platformName: 'ios''

2017-05-31 09:57:09 - DEBUG UnitTestFramework: 'tests scheduled'

2017-05-31 09:57:09 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-05-31 09:57:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-05-31 09:57:14 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-05-31 09:57:15 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-05-31 09:57:15 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-05-31 09:57:16 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-05-31 09:57:16 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-05-31 09:57:19 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-05-31 09:57:19 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-05-31 09:57:30 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-05-31 09:57:30 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-05-31 09:57:42 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-05-31 09:57:42 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 09:57:55 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 09:57:55 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 09:57:56 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 09:57:56 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 09:57:57 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 09:57:57 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 09:57:57 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 09:57:57 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 09:57:57 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 09:57:57 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 09:57:58 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 09:57:58 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 09:57:58 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 09:57:58 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 09:57:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 09:57:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 09:57:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 09:57:58 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 09:57:58 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 09:57:59 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 09:57:59 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 09:57:59 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 09:57:59 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 09:58:00 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 09:58:00 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 09:58:00 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 09:58:00 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 09:58:00 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 09:58:01 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 09:58:01 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 09:58:01 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 09:58:01 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 09:58:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 09:58:02 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 09:58:02 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 09:58:02 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 09:58:02 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 09:58:02 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'a5629696-8627-41ff-bb76-c350d9ecc906', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 09:58:02 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-05-31 09:58:02 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 09:58:02 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 09:58:02 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 09:58:02 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 09:58:02 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 09:58:02 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 09:58:02 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 09:58:02 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 09:58:02 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 09:58:02 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 09:58:02 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-05-31 09:58:03 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-05-31 09:58:03 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-05-31 09:58:03 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-05-31 09:58:03 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-05-31 09:58:03 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-05-31 09:58:03 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-05-31 09:58:04 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-05-31 09:58:04 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-05-31 09:58:05 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-05-31 09:58:05 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-05-31 09:58:09 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '50e23d6d-f517-44bb-a6fb-79e4164c1107', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 09:58:09 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-05-31 09:58:13 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-05-31 09:58:13 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-05-31 09:58:20 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-05-31 09:58:20 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-05-31 09:58:26 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-05-31 09:58:26 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-05-31 09:58:35 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-05-31 09:58:35 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-05-31 09:58:36 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-05-31 09:58:36 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-05-31 09:58:37 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-05-31 09:58:40 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-05-31 09:58:40 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-05-31 09:58:42 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-05-31 09:58:42 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-05-31 09:58:46 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-05-31 09:58:46 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-05-31 09:59:07 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-05-31 09:59:07 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-05-31 09:59:10 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-05-31 09:59:10 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-05-31 09:59:11 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-05-31 09:59:11 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-05-31 09:59:11 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-05-31 09:59:11 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-05-31 09:59:11 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-05-31 09:59:11 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-05-31 09:59:15 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-05-31 09:59:15 - DEBUG UnitTestFramework: '#run: 'basic''

2017-05-31 09:59:18 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-05-31 09:59:18 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-05-31 09:59:28 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-05-31 09:59:28 - DEBUG UnitTestFramework: '#setup: 'another''

2017-05-31 09:59:29 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-05-31 09:59:29 - DEBUG UnitTestFramework: '#run: 'another''

2017-05-31 09:59:31 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-05-31 09:59:31 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-05-31 09:59:33 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-05-31 09:59:33 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-05-31 09:59:35 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-05-31 09:59:35 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-05-31 09:59:35 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-05-31 09:59:35 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-05-31 09:59:35 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-05-31 09:59:35 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-05-31 09:59:35 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-05-31 09:59:35 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-05-31 10:00:00 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-05-31 10:00:00 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-05-31 10:00:27 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'bcdfc85f-5756-4cda-88ff-5ae1931c710a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 10:00:27 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-05-31 10:00:27 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-05-31 10:00:27 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-05-31 10:00:27 - DEBUG UnitTestFramework: 'scheduling tests'

2017-05-31 10:00:28 - DEBUG UnitTestFramework: 'tests scheduled'

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 10:00:28 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''
2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''
2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 10:00:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 10:00:29 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-05-31 10:00:30 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-05-31 10:00:31 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-05-31 10:00:31 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-05-31 10:00:32 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-05-31 10:00:32 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-05-31 10:00:32 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-05-31 10:00:32 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-05-31 10:00:32 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-05-31 10:00:32 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-05-31 10:00:33 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run: 'basic''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup: 'another''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run: 'another''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-05-31 10:00:34 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-05-31 10:00:35 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-05-31 10:00:35 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-05-31 10:00:36 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-05-31 10:00:36 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-05-31 10:00:36 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-05-31 10:00:36 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-05-31 10:00:36 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-05-31 10:00:36 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-05-31 10:00:36 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-05-31 10:00:36 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-05-31 10:00:36 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-05-31 10:00:36 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-05-31 10:00:37 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-05-31 10:00:37 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-05-31 10:00:38 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-05-31 10:00:39 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-05-31 10:00:39 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-05-31 10:00:39 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-05-31 10:00:39 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-05-31 10:00:39 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-05-31 10:00:39 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:00:39 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:00:39 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:00:40 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-05-31 10:00:40 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-05-31 10:00:40 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:00:40 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:00:40 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:00:40 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:00:41 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:00:41 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:00:41 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:00:41 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:00:42 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:00:42 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:00:42 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:00:42 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:00:42 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:00:42 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:00:42 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:00:42 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:00:42 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:00:42 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:00:43 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:00:43 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:00:43 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:00:43 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:00:43 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:00:43 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:00:44 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:00:44 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:00:45 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:00:45 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:00:45 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:00:45 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:00:45 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:00:45 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:00:45 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:00:45 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-05-31 10:00:45 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-05-31 10:00:45 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-05-31 10:00:47 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-05-31 10:00:47 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-05-31 10:00:48 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-05-31 10:00:48 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-05-31 10:00:48 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-05-31 10:00:48 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-05-31 10:00:51 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-05-31 10:00:51 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-05-31 10:00:55 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-05-31 10:00:55 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-05-31 10:01:00 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-05-31 10:01:00 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-05-31 10:01:17 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-05-31 10:01:17 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-05-31 10:01:31 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-05-31 10:01:31 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-05-31 10:01:31 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-05-31 10:01:31 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-05-31 10:01:31 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-05-31 10:01:31 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-05-31 10:01:31 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-05-31 10:01:31 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-05-31 10:01:33 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-05-31 10:01:33 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-05-31 10:01:34 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-05-31 10:01:34 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-05-31 10:01:36 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-05-31 10:01:36 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-05-31 10:01:36 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-05-31 10:01:36 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-05-31 10:01:44 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-05-31 10:01:44 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-05-31 10:01:46 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-05-31 10:01:46 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-05-31 10:01:46 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-05-31 10:01:46 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-05-31 10:01:54 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-05-31 10:01:54 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-05-31 10:01:55 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-05-31 10:01:55 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-05-31 10:01:58 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-05-31 10:01:58 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-05-31 10:02:00 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-05-31 10:02:00 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-05-31 10:02:00 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-05-31 10:02:00 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-05-31 10:02:01 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-05-31 10:02:01 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-05-31 10:02:02 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-31 10:02:03 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-31 10:02:10 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-31 10:02:10 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-05-31 10:02:10 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-05-31 10:02:11 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-05-31 10:02:11 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-05-31 10:02:12 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-05-31 10:02:12 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-05-31 10:02:13 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-31 10:02:13 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-31 10:02:14 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-31 10:02:14 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-05-31 10:02:14 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-05-31 10:02:14 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-05-31 10:02:14 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:02:15 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:02:15 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:02:16 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:02:16 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:02:17 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 10:02:17 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:02:18 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:02:18 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:02:21 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:02:21 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:02:23 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 10:02:23 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:02:39 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:02:39 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:02:44 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:02:44 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:02:53 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 10:02:53 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:02:56 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:02:56 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:03:11 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:03:11 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:03:33 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 10:03:33 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:03:35 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:03:35 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:03:40 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:03:40 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:03:46 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 10:03:46 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:03:50 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:03:50 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:03:56 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:03:56 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:03:56 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 10:03:56 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-05-31 10:03:56 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-05-31 10:03:56 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-05-31 10:04:08 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-05-31 10:04:08 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-05-31 10:04:19 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-05-31 10:04:19 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-05-31 10:04:26 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-05-31 10:04:26 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-05-31 10:04:46 - ERROR UnitTestFramework: '#run failed: 'Can shift data via parallel connections', error: 'TimeoutError: timeout exceeded, event: 'run_Can shift data via parallel connections_finished', test: 'Can shift data via parallel connections'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can shift data via parallel connections_finished', test: 'Can shift data via parallel connections'
    at afterTimeout (/home/pi/Test/server_1133518510f7eefa/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518510f7eefa/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-31 10:04:46 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_Can shift data via parallel connections_finished', test: 'Can shift data via parallel connections'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can shift data via parallel connections_finished', test: 'Can shift data via parallel connections'
    at afterTimeout (/home/pi/Test/server_1133518510f7eefa/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518510f7eefa/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-31 10:07:26 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_1133518510f7eefa/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518510f7eefa/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-31 10:07:26 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_1133518510f7eefa/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518510f7eefa/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-31 10:07:43 - DEBUG TestServer: 'completed'

2017-05-31 10:07:43 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-05-31 10:07:43 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-05-31 10:07:43 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-05-31 10:07:43 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-05-31 10:07:43 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-05-31 10:07:43 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
31/5/2017@11:53:17 Getting the list of iOS devices 
31/5/2017@11:53:18 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
31/5/2017@11:53:18 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
31/5/2017@11:53:18 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
31/5/2017@11:53:18 Deploying iOS test app 
31/5/2017@11:53:18 uninstalling the application 
31/5/2017@11:53:19 installing the application 
31/5/2017@12:16:37 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
31/5/2017@12:16:37 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
31/5/2017@12:16:37 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
true

```
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1133518510f7eefa_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518510f7eefa_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518510f7eefa_CI_sanity_check_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1133518510f7eefa_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1133518510f7eefa_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1133518510f7eefa_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/1133518510f7eefa_CI_sanity_check_jareksl/iOS_server.md)





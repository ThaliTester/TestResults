#### Test 1133518514d49fb2 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-05-31 11:53:16 - INFO HttpServer: 'listening on *:3000'

2017-05-31 11:53:20 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '52c78015-2c8c-4b28-ae81-c40f0ed5612d', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:53:20 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-05-31 11:53:21 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'a81f6b4c-e185-4350-b068-cdaa0d61c365', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:53:21 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-05-31 11:53:22 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '52c78015-2c8c-4b28-ae81-c40f0ed5612d', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:53:22 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: '52c78015-2c8c-4b28-ae81-c40f0ed5612d', platformName: 'ios''

2017-05-31 11:53:23 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '7e24c699-5e87-4b0e-8c36-b9f78fee0fda', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:53:23 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-05-31 11:53:23 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-05-31 11:53:23 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-05-31 11:53:23 - DEBUG UnitTestFramework: 'scheduling tests'

2017-05-31 11:53:23 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'a81f6b4c-e185-4350-b068-cdaa0d61c365', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:53:23 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'a81f6b4c-e185-4350-b068-cdaa0d61c365', platformName: 'ios''

2017-05-31 11:53:25 - DEBUG UnitTestFramework: 'tests scheduled'

2017-05-31 11:53:25 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-05-31 11:53:25 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '7e24c699-5e87-4b0e-8c36-b9f78fee0fda', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:53:25 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '7e24c699-5e87-4b0e-8c36-b9f78fee0fda', platformName: 'ios''

2017-05-31 11:53:25 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-05-31 11:53:25 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-05-31 11:53:47 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-05-31 11:53:47 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-05-31 11:53:49 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-05-31 11:53:49 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-05-31 11:53:50 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-05-31 11:53:50 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-05-31 11:53:51 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-05-31 11:53:51 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-05-31 11:53:52 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-05-31 11:53:52 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:53:53 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:53:53 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:54:01 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:54:01 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:54:02 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:54:02 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:54:03 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:54:04 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:54:05 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:54:05 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:54:08 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:54:08 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:54:09 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:54:09 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:54:09 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 11:54:09 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 11:54:09 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 11:54:09 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:54:09 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:54:10 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:54:10 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:54:12 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:54:12 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:54:12 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:54:12 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:54:13 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:54:13 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:54:13 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:54:15 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:54:15 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:54:16 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:54:16 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:54:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:54:17 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:54:25 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:54:25 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:54:25 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:54:25 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:54:25 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:54:26 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:54:26 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:54:27 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:54:27 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:54:27 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:54:27 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:54:27 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:54:29 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:54:29 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-05-31 11:54:35 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-05-31 11:54:35 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-05-31 11:54:35 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-05-31 11:54:35 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-05-31 11:54:36 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-05-31 11:54:36 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-05-31 11:54:37 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-05-31 11:54:37 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-05-31 11:54:37 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-05-31 11:54:37 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-05-31 11:54:38 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-05-31 11:54:38 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-05-31 11:54:38 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-05-31 11:54:38 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-05-31 11:54:39 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-05-31 11:54:39 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-05-31 11:54:39 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-05-31 11:54:39 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-05-31 11:54:40 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-05-31 11:54:40 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-05-31 11:54:40 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-05-31 11:54:40 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-05-31 11:54:41 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-05-31 11:54:41 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-05-31 11:54:45 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '5072ad2a-8bc1-458a-998d-2fb60931c3a7', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:54:45 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-05-31 11:54:48 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-05-31 11:54:48 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-05-31 11:54:49 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-05-31 11:54:49 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-05-31 11:54:49 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'aedc4f50-31e7-418c-ba2f-fd3ec2fd297e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:54:49 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-05-31 11:54:52 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-05-31 11:54:52 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-05-31 11:54:54 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-05-31 11:54:54 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-05-31 11:54:56 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-05-31 11:54:56 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-05-31 11:54:57 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-05-31 11:54:57 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-05-31 11:54:58 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-05-31 11:54:58 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-05-31 11:54:58 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-05-31 11:54:58 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-05-31 11:54:59 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-05-31 11:54:59 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-05-31 11:54:59 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-05-31 11:54:59 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-05-31 11:55:01 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-05-31 11:55:01 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-05-31 11:55:02 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-05-31 11:55:02 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-05-31 11:55:02 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-05-31 11:55:02 - DEBUG UnitTestFramework: '#run: 'basic''

2017-05-31 11:55:02 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-05-31 11:55:02 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-05-31 11:55:05 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-05-31 11:55:05 - DEBUG UnitTestFramework: '#setup: 'another''

2017-05-31 11:55:07 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-05-31 11:55:07 - DEBUG UnitTestFramework: '#run: 'another''

2017-05-31 11:55:08 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-05-31 11:55:08 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-05-31 11:55:09 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-05-31 11:55:09 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-05-31 11:55:13 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-05-31 11:55:13 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-05-31 11:55:13 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-05-31 11:55:13 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-05-31 11:55:15 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-05-31 11:55:15 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-05-31 11:55:17 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-05-31 11:55:17 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-05-31 11:55:27 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-05-31 11:55:27 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-05-31 11:55:29 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-05-31 11:55:29 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-05-31 11:55:33 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-05-31 11:55:33 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-05-31 11:55:34 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-05-31 11:55:34 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-05-31 11:55:43 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-05-31 11:55:43 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-05-31 11:55:46 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-05-31 11:55:46 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-05-31 11:55:47 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-05-31 11:55:47 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-05-31 11:55:48 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-05-31 11:55:48 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-05-31 11:55:50 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-05-31 11:55:50 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-05-31 11:55:51 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-05-31 11:55:51 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-05-31 11:55:53 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-05-31 11:55:53 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-05-31 11:55:55 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-05-31 11:55:55 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-05-31 11:55:59 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-05-31 11:55:59 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-05-31 11:56:16 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-05-31 11:56:16 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-05-31 11:56:19 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-05-31 11:56:19 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-05-31 11:56:24 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'ee4b7266-0a1a-4bea-80d1-30f98481d483', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:56:24 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-05-31 11:56:24 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-05-31 11:56:24 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-05-31 11:56:24 - DEBUG UnitTestFramework: 'scheduling tests'

2017-05-31 11:56:26 - DEBUG UnitTestFramework: 'tests scheduled'

2017-05-31 11:56:26 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-05-31 11:56:27 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-05-31 11:56:27 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-05-31 11:56:27 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-05-31 11:56:27 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-05-31 11:56:29 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-05-31 11:56:29 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-05-31 11:56:30 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-05-31 11:56:30 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-05-31 11:56:30 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-05-31 11:56:30 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-05-31 11:56:32 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-05-31 11:56:32 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-05-31 11:56:39 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-05-31 11:56:39 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:56:40 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:56:40 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:56:41 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:56:41 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:56:44 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-31 11:56:44 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:56:44 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:56:44 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:56:45 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:56:45 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:56:46 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-31 11:56:46 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:56:46 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-05-31 11:56:46 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-05-31 11:56:52 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:56:52 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:56:53 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 11:56:54 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 11:56:59 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-31 11:56:59 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:56:59 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:57:00 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-31 11:57:00 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:57:00 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:57:00 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:57:00 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:57:00 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:57:00 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:57:00 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:57:00 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:57:00 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-31 11:57:00 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:57:01 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:57:01 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:57:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:57:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:57:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:57:01 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:57:01 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:57:01 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-31 11:57:01 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:57:02 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-05-31 11:57:02 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-05-31 11:57:02 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:57:02 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:57:03 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-31 11:57:03 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:57:03 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:57:03 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-05-31 11:57:03 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-05-31 11:57:03 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-05-31 11:57:04 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-05-31 11:57:04 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-05-31 11:57:04 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-05-31 11:57:04 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-05-31 11:57:04 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-05-31 11:57:04 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-05-31 11:57:05 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run: 'basic''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup: 'another''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run: 'another''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-05-31 11:57:06 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-05-31 11:57:07 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-05-31 11:57:07 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:08 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:09 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-05-31 11:57:09 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:09 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:09 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:10 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:10 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:57:10 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:57:10 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:57:10 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:57:10 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:57:11 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:57:11 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 11:57:11 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 11:57:11 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 11:57:11 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 11:57:11 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 11:57:11 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-31 11:57:11 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 11:57:11 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 11:57:11 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 11:57:13 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 11:57:13 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 11:57:13 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-31 11:57:13 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 11:57:13 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 11:57:13 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-05-31 11:57:14 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-05-31 11:57:16 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-05-31 11:57:16 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-05-31 11:57:17 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-05-31 11:57:17 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-05-31 11:57:17 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-05-31 11:57:17 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-05-31 11:57:17 - INFO Socket: 'run skipped, test: 'Can connect to a remote peer', event: 'run_Can connect to a remote peer''

2017-05-31 11:57:17 - INFO Socket: 'run skipped, test: 'Can connect to a remote peer', event: 'run_Can connect to a remote peer''

2017-05-31 11:57:17 - INFO Socket: 'run skipped, test: 'Can connect to a remote peer', event: 'run_Can connect to a remote peer''

2017-05-31 11:57:17 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-05-31 11:57:17 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-05-31 11:57:17 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-05-31 11:57:17 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-05-31 11:57:18 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:18 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:19 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-31 11:57:19 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-05-31 11:57:19 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-05-31 11:57:19 - INFO Socket: 'run skipped, test: 'Can shift data', event: 'run_Can shift data''

2017-05-31 11:57:19 - INFO Socket: 'run skipped, test: 'Can shift data', event: 'run_Can shift data''

2017-05-31 11:57:19 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-31 11:57:19 - INFO Socket: 'run skipped, test: 'Can shift data', event: 'run_Can shift data''

2017-05-31 11:57:19 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-05-31 11:57:19 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-05-31 11:57:19 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-31 11:57:19 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:19 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:19 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-05-31 11:57:19 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-05-31 11:57:19 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-05-31 11:57:19 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-05-31 11:57:19 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-05-31 11:57:19 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-05-31 11:57:20 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-05-31 11:57:20 - INFO Socket: 'run skipped, test: 'Can shift data securely', event: 'run_Can shift data securely''

2017-05-31 11:57:20 - INFO Socket: 'run skipped, test: 'Can shift data securely', event: 'run_Can shift data securely''

2017-05-31 11:57:20 - INFO Socket: 'run skipped, test: 'Can shift data securely', event: 'run_Can shift data securely''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-05-31 11:57:20 - INFO Socket: 'run skipped, test: 'Can shift large amounts of data', event: 'run_Can shift large amounts of data''

2017-05-31 11:57:20 - INFO Socket: 'run skipped, test: 'Can shift large amounts of data', event: 'run_Can shift large amounts of data''

2017-05-31 11:57:20 - INFO Socket: 'run skipped, test: 'Can shift large amounts of data', event: 'run_Can shift large amounts of data''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-31 11:57:20 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-31 11:57:21 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:21 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:22 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:22 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:24 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-05-31 11:57:24 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:57:26 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:57:26 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:57:28 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-31 11:57:28 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-31 11:57:30 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-31 11:57:30 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-05-31 11:57:35 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-05-31 11:57:35 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-05-31 11:57:36 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-05-31 11:57:36 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-05-31 11:57:41 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-05-31 11:57:41 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-05-31 11:57:41 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-05-31 11:57:42 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-05-31 11:57:42 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-31 11:57:52 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-31 11:57:52 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-31 11:58:48 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'transport error''

2017-05-31 11:58:51 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport error''

2017-05-31 11:58:56 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'aedc4f50-31e7-418c-ba2f-fd3ec2fd297e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:58:56 - INFO TestFramework: 'updating existing device, name: 'samsung-SM-G930F', uuid: 'aedc4f50-31e7-418c-ba2f-fd3ec2fd297e', platformName: 'android''

2017-05-31 11:58:59 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'aedc4f50-31e7-418c-ba2f-fd3ec2fd297e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:58:59 - INFO TestFramework: 'updating existing device, name: 'samsung-SM-G930F', uuid: 'aedc4f50-31e7-418c-ba2f-fd3ec2fd297e', platformName: 'android''

2017-05-31 11:59:02 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-31 11:59:02 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-31 11:59:21 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'a81f6b4c-e185-4350-b068-cdaa0d61c365', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:59:21 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'a81f6b4c-e185-4350-b068-cdaa0d61c365', platformName: 'ios''

2017-05-31 11:59:22 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:59:22 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-31 11:59:24 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'a81f6b4c-e185-4350-b068-cdaa0d61c365', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-31 11:59:24 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'a81f6b4c-e185-4350-b068-cdaa0d61c365', platformName: 'ios''

2017-05-31 12:00:02 - ERROR UnitTestFramework: '#run failed: 'discoveryAdvertisingStateUpdateNonTCP is called', error: 'TimeoutError: timeout exceeded, event: 'teardown_discoveryAdvertisingStateUpdateNonTCP is called_finished', test: 'discoveryAdvertisingStateUpdateNonTCP is called'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_discoveryAdvertisingStateUpdateNonTCP is called_finished', test: 'discoveryAdvertisingStateUpdateNonTCP is called'
    at afterTimeout (/home/pi/Test/server_1133518514d49fb2/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518514d49fb2/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-31 12:00:02 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'teardown_discoveryAdvertisingStateUpdateNonTCP is called_finished', test: 'discoveryAdvertisingStateUpdateNonTCP is called'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_discoveryAdvertisingStateUpdateNonTCP is called_finished', test: 'discoveryAdvertisingStateUpdateNonTCP is called'
    at afterTimeout (/home/pi/Test/server_1133518514d49fb2/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518514d49fb2/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-31 12:00:22 - ERROR UnitTestFramework: '#run failed: 'Calling startListeningForAdvertisements twice is NOT an error', error: 'TimeoutError: timeout exceeded, event: 'teardown_Calling startListeningForAdvertisements twice is NOT an error_finished', test: 'Calling startListeningForAdvertisements twice is NOT an error'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_Calling startListeningForAdvertisements twice is NOT an error_finished', test: 'Calling startListeningForAdvertisements twice is NOT an error'
    at afterTimeout (/home/pi/Test/server_1133518514d49fb2/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518514d49fb2/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-31 12:00:22 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'teardown_Calling startListeningForAdvertisements twice is NOT an error_finished', test: 'Calling startListeningForAdvertisements twice is NOT an error'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_Calling startListeningForAdvertisements twice is NOT an error_finished', test: 'Calling startListeningForAdvertisements twice is NOT an error'
    at afterTimeout (/home/pi/Test/server_1133518514d49fb2/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1133518514d49fb2/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-31 12:00:22 - DEBUG TestServer: 'completed'

2017-05-31 12:00:22 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-05-31 12:00:22 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-05-31 12:00:22 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-05-31 12:00:22 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-05-31 12:00:22 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-05-31 12:00:22 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

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
31/5/2017@13:49:53 Getting the list of iOS devices 
31/5/2017@13:49:54 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
31/5/2017@13:49:54 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
31/5/2017@13:49:54 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
31/5/2017@13:49:54 Deploying iOS test app 
31/5/2017@13:49:54 uninstalling the application 
31/5/2017@13:49:54 installing the application 
31/5/2017@14:13:13 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
31/5/2017@14:13:13 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
31/5/2017@14:13:13 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
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
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1133518514d49fb2_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518514d49fb2_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)

####Node name: thali05
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

STOP log received from ce061606c181d71003
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518514d49fb2_CI_sanity_check_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1133518514d49fb2_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1133518514d49fb2_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1133518514d49fb2_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/1133518514d49fb2_CI_sanity_check_jareksl/iOS_server.md)





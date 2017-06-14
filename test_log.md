#### Test 1248535469caf7c1 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 2 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-14 07:55:44 - INFO HttpServer: 'listening on *:3000'

2017-06-14 07:55:46 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '88e00947-1795-41d7-83ee-02e4d320c81f', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-14 07:55:46 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-14 07:55:48 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '88e00947-1795-41d7-83ee-02e4d320c81f', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-14 07:55:48 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '88e00947-1795-41d7-83ee-02e4d320c81f', platformName: 'ios''

2017-06-14 07:55:49 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'ed0afb68-b609-4885-b394-704cb7c3127e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-14 07:55:49 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-14 07:55:52 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '0c05b064-17a4-4269-941f-59d2198b80cb', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-14 07:55:52 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-14 07:55:52 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-14 07:55:52 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-14 07:55:52 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-14 07:55:59 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-14 07:55:59 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-14 07:56:03 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-14 07:56:03 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-14 07:56:09 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-14 07:56:09 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-14 07:56:11 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-14 07:56:11 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-14 07:56:16 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-14 07:56:16 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-14 07:56:17 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-14 07:56:17 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-14 07:56:21 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-14 07:56:21 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:56:25 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:56:25 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:56:30 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:56:30 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:56:31 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:56:31 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:56:32 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:56:32 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:56:34 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:56:34 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:56:34 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:56:34 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:56:34 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:56:34 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:56:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-14 07:56:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-14 07:56:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-14 07:56:35 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:56:35 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:56:35 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:56:35 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:56:36 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:56:36 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:56:36 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:56:36 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:56:36 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:56:36 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:56:36 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:56:37 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:56:37 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:56:38 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:56:38 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:56:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:56:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:56:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:56:38 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:56:38 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:56:39 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:56:39 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:56:40 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:56:40 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:56:40 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:56:41 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:56:41 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:56:41 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:56:41 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:56:41 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:56:41 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-14 07:56:42 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-14 07:56:42 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-14 07:56:43 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-14 07:56:43 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-14 07:56:49 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-14 07:56:49 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-14 07:56:49 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-14 07:56:49 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-14 07:56:49 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-14 07:56:49 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-14 07:56:50 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-14 07:56:50 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-14 07:56:50 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-14 07:56:50 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-14 07:56:51 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-14 07:56:51 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-14 07:56:51 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-14 07:56:51 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-14 07:56:51 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-14 07:56:51 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-14 07:56:52 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-14 07:56:52 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-14 07:56:52 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-14 07:56:52 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-14 07:56:53 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-14 07:56:53 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-14 07:56:54 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-14 07:56:54 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-14 07:56:57 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-14 07:56:57 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-14 07:56:59 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-14 07:56:59 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-14 07:57:00 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-14 07:57:00 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-14 07:57:03 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-14 07:57:03 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-14 07:57:03 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-14 07:57:03 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-14 07:57:03 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-14 07:57:03 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-14 07:57:03 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-14 07:57:03 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-14 07:57:03 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-14 07:57:03 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-14 07:57:06 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-14 07:57:06 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-14 07:57:10 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-14 07:57:10 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-14 07:57:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '912b0e43-7550-4b39-9af6-c9c61a5e9aaa', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-14 07:57:18 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-14 07:57:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '10aa9a42-59a3-4aa3-a4b2-8707914a8fda', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-14 07:57:18 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-14 07:57:18 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-14 07:57:18 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-14 07:57:20 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-14 07:57:20 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-14 07:57:23 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-14 07:57:23 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-14 07:57:28 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-14 07:57:28 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-14 07:57:30 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-14 07:57:30 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-14 07:57:32 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-14 07:57:32 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-14 07:57:32 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-14 07:57:32 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-14 07:57:35 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-14 07:57:35 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-14 07:57:37 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-14 07:57:37 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-14 07:57:44 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-14 07:57:44 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-14 07:57:44 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-14 07:57:44 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-14 07:57:46 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-14 07:57:46 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-14 07:57:46 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-14 07:57:46 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-14 07:57:47 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-14 07:57:48 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-14 07:57:48 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-14 07:57:54 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-14 07:57:54 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-14 07:58:04 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-14 07:58:04 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-14 07:58:06 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-14 07:58:06 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-14 07:58:08 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-14 07:58:08 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-14 07:58:10 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-14 07:58:10 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-14 07:58:13 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-14 07:58:13 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-14 07:58:14 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-14 07:58:14 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-14 07:58:15 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-14 07:58:16 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-14 07:58:24 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-14 07:58:24 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-14 07:58:24 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-14 07:58:29 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-14 07:58:29 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-14 07:58:31 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-14 07:58:31 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-14 07:58:31 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-14 07:58:31 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-14 07:58:33 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-14 07:58:33 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-14 07:58:33 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-14 07:58:36 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-14 07:58:36 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:58:38 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:58:38 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:58:40 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:58:40 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:58:40 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:58:40 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:58:42 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:58:42 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:58:45 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:58:45 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:58:47 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:58:47 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:58:49 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:58:49 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:58:50 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:58:50 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:58:50 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:58:50 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:58:50 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:58:50 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:58:50 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'cde2898a-19c5-4c6b-9be7-200f281db809', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-14 07:58:50 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-14 07:58:50 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-06-14 07:58:50 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-06-14 07:58:50 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-14 07:58:51 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:58:51 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:58:52 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:58:52 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:58:52 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-14 07:58:52 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-14 07:58:52 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-14 07:58:52 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-14 07:58:55 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-14 07:58:55 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-14 07:58:57 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-14 07:58:57 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-14 07:58:59 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-14 07:58:59 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-14 07:58:59 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:58:59 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:59:00 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-14 07:59:00 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:59:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-14 07:59:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-14 07:59:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-14 07:59:01 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:59:02 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:59:02 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:59:02 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:59:02 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:02 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:59:02 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:59:02 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:59:02 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:59:02 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:59:02 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:02 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:02 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-14 07:59:02 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:59:07 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:59:07 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:59:07 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:59:07 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:59:07 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:59:07 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:59:07 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:59:08 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-14 07:59:08 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:59:12 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:59:12 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:59:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:59:14 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:59:14 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:59:14 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:59:14 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:59:17 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-14 07:59:17 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-14 07:59:22 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-14 07:59:22 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-14 07:59:22 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-14 07:59:22 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-14 07:59:33 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-14 07:59:33 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-14 07:59:34 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-14 07:59:34 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-14 07:59:35 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-14 07:59:36 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-14 07:59:36 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-14 07:59:38 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-14 07:59:38 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-14 07:59:38 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-14 07:59:38 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-14 07:59:39 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-14 07:59:39 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-14 07:59:41 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-14 07:59:42 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-14 07:59:43 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-14 07:59:44 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-14 07:59:44 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:59:44 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:59:44 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:59:45 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:59:45 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:59:45 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-14 07:59:45 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:59:45 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:59:45 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:59:46 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:59:46 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:59:46 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-14 07:59:46 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:59:46 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:59:46 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:59:47 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:59:47 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:59:47 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-14 07:59:47 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:59:47 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''
2017-06-14 07:59:47 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:59:48 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:59:48 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:59:49 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-14 07:59:49 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:59:49 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:59:49 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:59:51 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:59:51 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:59:52 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-14 07:59:52 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:52 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:52 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:54 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:54 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:56 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:56 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:59 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-14 07:59:59 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-14 08:00:06 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-14 08:00:06 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-14 08:00:54 - ERROR UnitTestFramework: '#run failed: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error', error: 'TimeoutError: timeout exceeded, event: 'teardown_Can call stopUpdateAdvertisingAndListening twice without start and it is not an error_finished', test: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_Can call stopUpdateAdvertisingAndListening twice without start and it is not an error_finished', test: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
    at afterTimeout (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-14 08:00:54 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'teardown_Can call stopUpdateAdvertisingAndListening twice without start and it is not an error_finished', test: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_Can call stopUpdateAdvertisingAndListening twice without start and it is not an error_finished', test: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
    at afterTimeout (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-14 08:00:56 - ERROR TestServerProcess: 'uncaught promise rejection, error: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'', stack: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_1248535469caf7c1/test/TestServer/utils/asserts.js:69:3)
    at UnitTestFramework.unbindSync (/home/pi/Test/server_1248535469caf7c1/test/TestServer/UnitTestFramework.js:233:11)
    at /home/pi/Test/server_1248535469caf7c1/test/TestServer/UnitTestFramework.js:100:10
    at PassThroughHandlerContext.finallyHandler (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/finally.js:55:23)
    at PassThroughHandlerContext.tryCatcher (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/promise.js:510:31)
    at Promise._settlePromise (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/promise.js:567:18)
    at Promise._settlePromise0 (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Promise._fulfill (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/promise.js:636:18)
    at PromiseArray._resolve (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/promise_array.js:125:19)
    at PromiseArray._promiseFulfilled (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/promise_array.js:143:14)
    at Promise._settlePromise (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/promise.js:572:26)
    at Promise._settlePromise0 (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Async._drainQueue (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/home/pi/Test/server_1248535469caf7c1/test/TestServer/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:917:13)''

2017-06-14 08:00:56 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-06-14 08:00:56 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-06-14 08:00:56 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-06-14 08:00:56 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-14 08:00:56 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-14 08:00:56 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 2 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
14/6/2017@09:52:29 Getting the list of iOS devices 
14/6/2017@09:52:30 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
14/6/2017@09:52:30 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
14/6/2017@09:52:30 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
14/6/2017@09:52:30 Deploying iOS test app 
14/6/2017@09:52:30 uninstalling the application 
14/6/2017@09:52:30 installing the application 
14/6/2017@10:15:49 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
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

Error! Unexpected exit on device ce061606e320561102 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1248535469caf7c1_Make_tests_zombie_proof_jareksl/thali03_samsung-SM-G935F.md)

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

Error! Unexpected exit on device ce0616068b9f212302 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1248535469caf7c1_Make_tests_zombie_proof_jareksl/thali04_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606c181d71003 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1248535469caf7c1_Make_tests_zombie_proof_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1248535469caf7c1_Make_tests_zombie_proof_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1248535469caf7c1_Make_tests_zombie_proof_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1248535469caf7c1_Make_tests_zombie_proof_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/1248535469caf7c1_Make_tests_zombie_proof_jareksl/iOS_server.md)





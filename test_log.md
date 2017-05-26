#### Test 113351851b637cfc Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 2 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-05-26 10:55:20 - INFO HttpServer: 'listening on *:3000'

2017-05-26 10:55:21 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '65ade75e-be88-4685-9e99-ebce60bfe761', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 10:55:21 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-05-26 10:55:28 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '3e68c602-609b-4e5c-9384-4df552ff0b73', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 10:55:28 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-05-26 10:55:30 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'c7c749cb-01e7-4b95-a4b6-f4dc08b329b0', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 10:55:30 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-05-26 10:55:30 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-05-26 10:55:30 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-05-26 10:55:30 - DEBUG UnitTestFramework: 'scheduling tests'

2017-05-26 10:55:32 - DEBUG UnitTestFramework: 'tests scheduled'

2017-05-26 10:55:32 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-05-26 10:55:33 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-05-26 10:55:33 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-05-26 10:55:34 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-05-26 10:55:34 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-05-26 10:55:36 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-05-26 10:55:36 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-05-26 10:55:36 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-05-26 10:55:36 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-05-26 10:55:37 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-05-26 10:55:37 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-05-26 10:55:37 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-05-26 10:55:37 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:55:37 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:55:37 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:55:38 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:55:38 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:55:40 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:55:40 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:55:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:55:41 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:55:41 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:55:41 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:55:41 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:55:41 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:55:42 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:55:42 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:55:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-26 10:55:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-26 10:55:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-26 10:55:42 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:55:42 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:55:43 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:55:43 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:55:44 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:55:44 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:55:45 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:55:46 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:55:46 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:55:46 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:55:46 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:55:46 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:55:46 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:55:46 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:55:46 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:55:46 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:55:46 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:55:46 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:55:46 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:55:46 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:55:47 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:55:47 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:55:47 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:55:47 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:55:47 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:55:48 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:55:48 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:55:48 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:55:48 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:55:49 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:55:49 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-05-26 10:55:50 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-05-26 10:55:50 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-05-26 10:55:51 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-05-26 10:55:52 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-05-26 10:55:52 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-05-26 10:55:52 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-05-26 10:55:52 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-05-26 10:55:52 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-05-26 10:55:52 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-05-26 10:55:52 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-05-26 10:55:52 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-05-26 10:55:53 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-05-26 10:55:53 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-05-26 10:55:54 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-05-26 10:55:54 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-05-26 10:55:54 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-05-26 10:55:54 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-05-26 10:55:55 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-05-26 10:55:55 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-05-26 10:55:55 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-05-26 10:55:55 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-05-26 10:55:56 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-05-26 10:55:56 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-05-26 10:55:56 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-05-26 10:55:56 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-05-26 10:55:56 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-05-26 10:55:56 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-05-26 10:55:56 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-05-26 10:55:56 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-05-26 10:55:57 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-05-26 10:55:57 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-05-26 10:55:58 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-05-26 10:55:58 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-05-26 10:55:59 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-05-26 10:55:59 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-05-26 10:56:00 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-05-26 10:56:00 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-05-26 10:56:01 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-05-26 10:56:01 - DEBUG UnitTestFramework: '#run: 'basic''

2017-05-26 10:56:01 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-05-26 10:56:01 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-05-26 10:56:01 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-05-26 10:56:01 - DEBUG UnitTestFramework: '#setup: 'another''

2017-05-26 10:56:01 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-05-26 10:56:01 - DEBUG UnitTestFramework: '#run: 'another''

2017-05-26 10:56:02 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-05-26 10:56:02 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-05-26 10:56:04 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-05-26 10:56:04 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-05-26 10:56:05 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-05-26 10:56:05 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-05-26 10:56:05 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-05-26 10:56:05 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-05-26 10:56:06 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-05-26 10:56:06 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-05-26 10:56:08 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-05-26 10:56:08 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-05-26 10:56:10 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-05-26 10:56:10 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-05-26 10:56:10 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-05-26 10:56:10 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-05-26 10:56:10 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-05-26 10:56:10 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-05-26 10:56:11 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-05-26 10:56:11 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-05-26 10:56:13 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-05-26 10:56:13 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-05-26 10:56:14 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-05-26 10:56:14 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-05-26 10:56:15 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-05-26 10:56:15 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-05-26 10:56:16 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-05-26 10:56:16 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-05-26 10:56:16 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-05-26 10:56:16 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-05-26 10:56:17 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-05-26 10:56:17 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-05-26 10:56:18 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-05-26 10:56:18 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-05-26 10:56:18 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-05-26 10:56:18 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-05-26 10:56:19 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-05-26 10:56:19 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-05-26 10:56:20 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-05-26 10:56:20 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-05-26 10:56:20 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-05-26 10:56:20 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-05-26 10:56:20 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-05-26 10:56:20 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-05-26 10:56:20 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-05-26 10:56:20 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-05-26 10:56:20 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-05-26 10:56:20 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-05-26 10:56:20 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-26 10:56:20 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-26 10:56:21 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-26 10:56:21 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-05-26 10:56:21 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-05-26 10:56:21 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-05-26 10:56:21 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-05-26 10:56:21 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-05-26 10:56:21 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-05-26 10:56:21 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-26 10:56:23 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-26 10:56:23 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-26 10:56:23 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-05-26 10:56:23 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-05-26 10:56:31 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-05-26 10:56:31 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:56:35 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:56:35 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:56:35 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:56:35 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:56:36 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:56:36 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:56:38 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:56:38 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:56:39 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:56:39 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:56:39 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:56:39 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:56:39 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:56:39 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:56:40 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:56:40 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:56:40 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:56:40 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:56:41 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:56:41 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:56:41 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:56:41 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:56:43 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:56:43 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:56:44 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:56:44 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:56:46 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:56:46 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:56:54 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:56:54 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:56:54 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'f9df8cf8-1c68-411c-ad4f-7158f47cc93e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 10:56:54 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-05-26 10:57:00 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '99b30b96-e59e-4a18-8de5-a210b0bbb528', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 10:57:00 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-05-26 10:57:03 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:57:03 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:57:04 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:57:04 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:57:05 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:57:05 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-05-26 10:57:05 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-05-26 10:57:05 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-05-26 10:57:07 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-05-26 10:57:07 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-05-26 10:57:08 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-05-26 10:57:08 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-05-26 10:57:09 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-05-26 10:57:09 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-05-26 10:58:40 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '55876022-d6f6-4375-8184-677b0819e741', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 10:58:40 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-05-26 10:58:40 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-05-26 10:58:40 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-05-26 10:58:40 - DEBUG UnitTestFramework: 'scheduling tests'

2017-05-26 10:58:41 - DEBUG UnitTestFramework: 'tests scheduled'

2017-05-26 10:58:41 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-05-26 10:58:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-05-26 10:58:41 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-05-26 10:58:41 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-05-26 10:58:41 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-05-26 10:58:41 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-05-26 10:58:41 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-05-26 10:58:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-05-26 10:58:41 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:58:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-26 10:58:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-26 10:58:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 10:58:42 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:58:43 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:58:43 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:58:43 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:58:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:58:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:58:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:58:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:58:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:58:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-05-26 10:58:43 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-05-26 10:58:44 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#run: 'basic''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-05-26 10:58:45 - DEBUG UnitTestFramework: '#setup: 'another''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#run: 'another''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-05-26 10:58:46 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-05-26 10:58:47 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:58:48 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:58:50 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:58:50 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:58:50 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-05-26 10:58:50 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:58:50 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:58:50 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:58:51 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:58:51 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:58:52 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 10:58:52 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:58:52 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:58:52 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:58:52 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:58:52 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:58:52 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 10:58:52 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:58:52 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:58:52 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:58:53 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:58:53 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:58:53 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 10:58:53 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:58:53 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:58:53 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:58:54 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:58:54 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:58:54 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 10:58:54 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:58:54 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:58:54 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:58:54 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:58:54 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:58:55 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 10:58:55 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-05-26 10:58:55 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-05-26 10:58:55 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-05-26 10:58:58 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-05-26 10:58:58 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-05-26 10:58:59 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-05-26 10:58:59 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-05-26 10:58:59 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-05-26 10:58:59 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-05-26 10:59:12 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-05-26 10:59:12 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-05-26 10:59:13 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-05-26 10:59:13 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-05-26 10:59:13 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-05-26 10:59:13 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-05-26 10:59:20 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-05-26 10:59:20 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-05-26 10:59:21 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-05-26 10:59:21 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-05-26 10:59:22 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-05-26 10:59:22 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-05-26 10:59:22 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-05-26 10:59:22 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-05-26 10:59:22 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-05-26 10:59:22 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-05-26 10:59:22 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-05-26 10:59:22 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-05-26 10:59:22 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-05-26 10:59:22 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-05-26 10:59:22 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-05-26 10:59:45 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-05-26 10:59:45 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-05-26 10:59:46 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-05-26 10:59:46 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-05-26 10:59:46 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-05-26 10:59:46 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-05-26 10:59:56 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-05-26 10:59:56 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-05-26 10:59:57 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-05-26 10:59:57 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 10:59:57 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 10:59:57 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 11:00:05 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 11:00:05 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 11:00:05 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 11:00:05 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-05-26 11:00:06 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-05-26 11:00:06 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-05-26 11:00:06 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-05-26 11:00:06 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-05-26 11:00:06 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-05-26 11:00:06 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-05-26 11:00:06 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-05-26 11:00:06 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-05-26 11:00:06 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-26 11:00:06 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-26 11:00:06 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-26 11:00:08 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-26 11:00:08 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-26 11:00:09 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-26 11:00:09 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-05-26 11:00:09 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-05-26 11:00:09 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-05-26 11:00:09 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-05-26 11:00:09 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-05-26 11:00:09 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-05-26 11:00:09 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-05-26 11:00:09 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-05-26 11:00:09 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-05-26 11:00:09 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-26 11:00:09 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-26 11:00:10 - ERROR TestServerProcess: 'uncaught promise rejection, error: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'', stack: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_113351851b637cfc/test/TestServer/utils/asserts.js:69:3)
    at UnitTestFramework.unbindSync (/home/pi/Test/server_113351851b637cfc/test/TestServer/UnitTestFramework.js:233:11)
    at /home/pi/Test/server_113351851b637cfc/test/TestServer/UnitTestFramework.js:100:10
    at PassThroughHandlerContext.finallyHandler (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/finally.js:55:23)
    at PassThroughHandlerContext.tryCatcher (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/promise.js:510:31)
    at Promise._settlePromise (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/promise.js:567:18)
    at Promise._settlePromise0 (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Promise._fulfill (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/promise.js:636:18)
    at PromiseArray._resolve (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/promise_array.js:125:19)
    at PromiseArray._promiseFulfilled (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/promise_array.js:143:14)
    at Promise._settlePromise (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/promise.js:572:26)
    at Promise._settlePromise0 (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Async._drainQueue (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/home/pi/Test/server_113351851b637cfc/test/TestServer/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:917:13)''

2017-05-26 11:00:10 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-05-26 11:00:10 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-05-26 11:00:10 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-05-26 11:00:10 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-05-26 11:00:10 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-05-26 11:00:10 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

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
26/5/2017@12:52:08 Getting the list of iOS devices 
26/5/2017@12:52:09 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
26/5/2017@12:52:09 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
26/5/2017@12:52:09 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
26/5/2017@12:52:09 Deploying iOS test app 
26/5/2017@12:52:09 uninstalling the application 
26/5/2017@12:52:10 installing the application 
26/5/2017@13:15:28 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
26/5/2017@13:15:28 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
26/5/2017@13:15:28 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851b637cfc_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851b637cfc_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851b637cfc_CI_sanity_check_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/113351851b637cfc_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/113351851b637cfc_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/113351851b637cfc_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/113351851b637cfc_CI_sanity_check_jareksl/iOS_server.md)





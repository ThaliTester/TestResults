#### Test 113351851e8898ca Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-05-23 08:50:06 - INFO HttpServer: 'listening on *:3000'

2017-05-23 08:50:10 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c75b63bf-e1b5-47f2-9656-3047c53281e9', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-23 08:50:10 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-05-23 08:50:11 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '6cb2c14d-f244-4036-b5fd-f99540f77a4d', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-23 08:50:11 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-05-23 08:50:12 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c75b63bf-e1b5-47f2-9656-3047c53281e9', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-23 08:50:12 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'c75b63bf-e1b5-47f2-9656-3047c53281e9', platformName: 'ios''

2017-05-23 08:50:16 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'c7ad1d2e-92f3-4bb2-ab19-9c44047f720f', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-23 08:50:16 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-05-23 08:50:16 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-05-23 08:50:16 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-05-23 08:50:16 - DEBUG UnitTestFramework: 'scheduling tests'

2017-05-23 08:50:17 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'c7ad1d2e-92f3-4bb2-ab19-9c44047f720f', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-23 08:50:17 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: 'c7ad1d2e-92f3-4bb2-ab19-9c44047f720f', platformName: 'ios''

2017-05-23 08:50:19 - DEBUG UnitTestFramework: 'tests scheduled'

2017-05-23 08:50:19 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-05-23 08:50:20 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-05-23 08:50:20 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-05-23 08:50:20 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-05-23 08:50:20 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-05-23 08:50:21 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-05-23 08:50:21 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-05-23 08:50:21 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-05-23 08:50:21 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-05-23 08:50:22 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-05-23 08:50:22 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-05-23 08:50:22 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-05-23 08:50:22 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-23 08:50:23 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-23 08:50:23 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-23 08:50:24 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-23 08:50:24 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-23 08:50:24 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-23 08:50:24 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-23 08:50:25 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-23 08:50:25 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-23 08:50:26 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-23 08:50:26 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-23 08:50:26 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-23 08:50:26 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-05-23 08:50:26 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-23 08:50:26 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-05-23 08:50:26 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-23 08:50:27 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-23 08:50:27 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-23 08:50:27 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-23 08:50:27 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-05-23 08:50:28 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-23 08:50:28 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-23 08:50:29 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-23 08:50:29 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-23 08:50:29 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-23 08:50:29 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-23 08:50:29 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-23 08:50:29 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''
2017-05-23 08:50:29 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-23 08:50:30 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-23 08:50:30 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-23 08:50:31 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-23 08:50:31 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-23 08:50:31 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-23 08:50:31 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-23 08:50:31 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-23 08:50:31 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-23 08:50:31 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-23 08:50:32 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-23 08:50:32 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-23 08:50:33 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-23 08:50:33 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-23 08:50:33 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-23 08:50:33 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-23 08:50:34 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-23 08:50:34 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-23 08:50:34 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-23 08:50:34 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-23 08:50:34 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-05-23 08:50:34 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-05-23 08:50:34 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-05-23 08:50:35 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-05-23 08:50:35 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-05-23 08:50:35 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-05-23 08:50:35 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-05-23 08:50:36 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-05-23 08:50:36 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-05-23 08:50:36 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-05-23 08:50:36 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-05-23 08:50:36 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-05-23 08:50:36 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-05-23 08:50:38 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-05-23 08:50:38 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-05-23 08:50:39 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-05-23 08:50:39 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-05-23 08:50:40 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-05-23 08:50:40 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-05-23 08:50:40 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-05-23 08:50:40 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-05-23 08:50:41 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-05-23 08:50:41 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-05-23 08:50:42 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-05-23 08:50:42 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-05-23 08:50:42 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-05-23 08:50:42 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-05-23 08:50:44 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-05-23 08:50:44 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-05-23 08:50:45 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-05-23 08:50:45 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-05-23 08:50:45 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-05-23 08:50:45 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-05-23 08:50:45 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-05-23 08:50:45 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-05-23 08:50:46 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-05-23 08:50:46 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-05-23 08:50:47 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-05-23 08:50:47 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-05-23 08:50:47 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-05-23 08:50:47 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-05-23 08:50:47 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-05-23 08:50:47 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-05-23 08:50:49 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-05-23 08:50:49 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-05-23 08:50:50 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-05-23 08:50:50 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-05-23 08:50:50 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-05-23 08:50:50 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-05-23 08:50:50 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-05-23 08:50:50 - DEBUG UnitTestFramework: '#run: 'basic''

2017-05-23 08:50:52 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-05-23 08:50:52 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-05-23 08:50:55 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-05-23 08:50:55 - DEBUG UnitTestFramework: '#setup: 'another''

2017-05-23 08:50:56 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-05-23 08:50:56 - DEBUG UnitTestFramework: '#run: 'another''

2017-05-23 08:50:58 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-05-23 08:50:58 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-05-23 08:50:58 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-05-23 08:50:58 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-05-23 08:50:58 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-05-23 08:50:58 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-05-23 08:50:59 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-05-23 08:50:59 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-05-23 08:50:59 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-05-23 08:50:59 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-05-23 08:51:00 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-05-23 08:51:00 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-05-23 08:51:00 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-05-23 08:51:00 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-05-23 08:51:01 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-05-23 08:51:01 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-05-23 08:51:01 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-05-23 08:51:01 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-05-23 08:51:03 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-05-23 08:51:03 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-05-23 08:51:04 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-05-23 08:51:04 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-05-23 08:51:05 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-05-23 08:51:05 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-05-23 08:51:09 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-05-23 08:51:09 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-05-23 08:51:13 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-05-23 08:51:13 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-05-23 08:51:15 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-05-23 08:51:15 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-05-23 08:51:17 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-05-23 08:51:17 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-05-23 08:51:21 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-05-23 08:51:21 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-05-23 08:51:27 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-05-23 08:51:27 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-05-23 08:51:29 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-05-23 08:51:29 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-05-23 08:51:29 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-05-23 08:51:29 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-05-23 08:51:31 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-05-23 08:51:31 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-05-23 08:51:31 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-05-23 08:51:31 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-05-23 08:51:33 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-05-23 08:51:33 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-05-23 08:51:34 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-05-23 08:51:34 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-05-23 08:51:37 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-23 08:51:38 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-23 08:51:39 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-23 08:51:39 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-05-23 08:51:39 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-05-23 08:51:41 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-05-23 08:51:41 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-05-23 08:51:42 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-05-23 08:51:42 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-05-23 08:51:43 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-23 08:51:43 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-23 08:51:43 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-23 08:51:43 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-05-23 08:51:43 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-05-23 08:51:44 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-05-23 08:51:44 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-05-23 08:51:45 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-05-23 08:51:45 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-05-23 08:51:47 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-05-23 08:51:47 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-05-23 08:51:48 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-05-23 08:51:48 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-23 08:51:49 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-23 08:51:49 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-23 08:51:52 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-23 08:51:52 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-23 08:51:57 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-23 08:51:57 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-23 08:52:04 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-23 08:52:04 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-23 08:52:23 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-23 08:52:23 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-23 08:52:45 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-23 08:52:45 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-23 08:52:45 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-23 08:52:45 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-23 08:52:47 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-23 08:52:47 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-23 08:52:49 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-23 08:52:49 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-23 08:52:50 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-23 08:52:50 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-23 08:52:51 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-23 08:52:51 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-23 08:52:52 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-23 08:52:52 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-23 08:52:52 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-23 08:52:52 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-23 08:52:53 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-23 08:52:53 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-23 08:52:55 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-23 08:52:55 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-05-23 08:52:55 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-05-23 08:52:55 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-05-23 08:52:57 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-05-23 08:52:57 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-05-23 08:53:00 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-05-23 08:53:00 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-05-23 08:53:02 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-05-23 08:53:02 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-05-23 08:53:20 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-05-23 08:53:20 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-05-23 08:53:21 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-05-23 08:53:21 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-05-23 08:53:21 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-05-23 08:53:21 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-05-23 08:55:06 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_113351851e8898ca/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-23 08:55:06 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-05-23 08:55:06 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-05-23 08:55:06 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
23/5/2017@10:46:43 Getting the list of iOS devices 
23/5/2017@10:46:44 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
23/5/2017@10:46:44 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
23/5/2017@10:46:44 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
23/5/2017@10:46:44 Deploying iOS test app 
23/5/2017@10:46:44 uninstalling the application 
23/5/2017@10:46:44 installing the application 
23/5/2017@11:10:03 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
23/5/2017@11:10:03 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
23/5/2017@11:10:03 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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

Error: problem running Android apk(org.thaliproject.thalitest) on device samsung-SM-G935F 
Starting: Intent { cmp=org.thaliproject.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {org.thaliproject.thalitest/org.thaliproject.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606e320561102 app:org.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851e8898ca_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

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

Error: problem running Android apk(org.thaliproject.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=org.thaliproject.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {org.thaliproject.thalitest/org.thaliproject.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce0616068b9f212302 app:org.thaliproject.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851e8898ca_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)

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

Error: problem running Android apk(org.thaliproject.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=org.thaliproject.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {org.thaliproject.thalitest/org.thaliproject.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606c181d71003 app:org.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851e8898ca_CI_sanity_check_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/113351851e8898ca_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/113351851e8898ca_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/113351851e8898ca_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/113351851e8898ca_CI_sanity_check_jareksl/iOS_server.md)





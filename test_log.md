#### Test 113351851a786003 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
Enter ____.js
Targets defined
http required
Creating internal server
Got request
URL:  [ 'nodes', '3' ]
Got request
URL:  [ 'ios', '3' ]
Enter checkIt
Got request
URL:  [ 'droid', '1' ]
Got request
URL:  [ 'droid', '1' ]
Got request
URL:  [ 'droid', '1' ]
Enter checkIt
checkIt do the job
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-04-04 19:31:53 - INFO HttpServer: 'listening on *:3000'

2017-04-04 19:31:56 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '32b26071-6f5d-4d93-96d4-462e0a7bda50', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 19:31:56 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-04-04 19:32:04 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '10a361a0-dbcc-4374-bf51-735d1f4f8b8f', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 19:32:04 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-04-04 19:32:06 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '10a361a0-dbcc-4374-bf51-735d1f4f8b8f', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 19:32:06 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '10a361a0-dbcc-4374-bf51-735d1f4f8b8f', platformName: 'ios''

2017-04-04 19:32:09 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'b0c9fe64-3710-4d97-a8f4-b8ce5920e090', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 19:32:09 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-04-04 19:32:09 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-04-04 19:32:09 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-04-04 19:32:09 - DEBUG UnitTestFramework: 'scheduling tests'

2017-04-04 19:32:13 - DEBUG UnitTestFramework: 'tests scheduled'

2017-04-04 19:32:13 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-04-04 19:32:16 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-04-04 19:32:16 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-04-04 19:32:17 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-04-04 19:32:17 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-04-04 19:32:18 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-04-04 19:32:18 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-04-04 19:32:19 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-04-04 19:32:19 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-04-04 19:32:20 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-04-04 19:32:20 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-04-04 19:32:21 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-04-04 19:32:21 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:32:21 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:32:21 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:32:21 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:32:21 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:32:23 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:32:23 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:32:23 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:32:23 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:32:24 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:32:24 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:32:25 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:32:25 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:32:26 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:32:26 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:32:26 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-04-04 19:32:26 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-04-04 19:32:26 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-04-04 19:32:26 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:32:26 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:32:27 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:32:27 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:32:30 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:32:30 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:32:30 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:32:30 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:32:31 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:32:31 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:32:31 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:32:31 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:32:31 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:32:31 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:32:31 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:32:32 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:32:32 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:32:32 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:32:32 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:32:32 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:32:32 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:32:32 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:32:33 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:32:33 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:32:33 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:32:34 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:32:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:32:35 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:32:35 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:32:35 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:32:35 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-04-04 19:32:36 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-04-04 19:32:36 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-04-04 19:32:36 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-04-04 19:32:36 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-04-04 19:32:37 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-04-04 19:32:37 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-04-04 19:32:38 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-04-04 19:32:38 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-04-04 19:32:40 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-04-04 19:32:40 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-04-04 19:32:42 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-04-04 19:32:42 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-04-04 19:32:44 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-04-04 19:32:44 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-04-04 19:32:45 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-04-04 19:32:45 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-04-04 19:32:45 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-04-04 19:32:45 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-04-04 19:32:46 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-04-04 19:32:46 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-04-04 19:32:46 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-04-04 19:32:46 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-04-04 19:32:49 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-04-04 19:32:49 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-04-04 19:32:49 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-04-04 19:32:49 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-04-04 19:32:51 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-04-04 19:32:51 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-04-04 19:32:52 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-04-04 19:32:52 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-04-04 19:32:53 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-04-04 19:32:53 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-04-04 19:32:54 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-04-04 19:32:54 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-04-04 19:32:56 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-04-04 19:32:56 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-04-04 19:32:56 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-04-04 19:32:56 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-04-04 19:32:58 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-04-04 19:32:58 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-04-04 19:32:58 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-04-04 19:32:58 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-04-04 19:32:59 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-04-04 19:32:59 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-04-04 19:32:59 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-04-04 19:32:59 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-04-04 19:33:00 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-04-04 19:33:00 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-04-04 19:33:00 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-04-04 19:33:00 - DEBUG UnitTestFramework: '#run: 'basic''

2017-04-04 19:33:01 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-04-04 19:33:01 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-04-04 19:33:01 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-04-04 19:33:01 - DEBUG UnitTestFramework: '#setup: 'another''

2017-04-04 19:33:03 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-04-04 19:33:03 - DEBUG UnitTestFramework: '#run: 'another''

2017-04-04 19:33:03 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-04-04 19:33:03 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-04-04 19:33:03 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-04-04 19:33:03 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-04-04 19:33:05 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-04-04 19:33:05 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-04-04 19:33:05 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-04-04 19:33:05 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-04-04 19:33:06 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-04-04 19:33:06 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-04-04 19:33:08 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-04-04 19:33:08 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-04-04 19:33:10 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-04-04 19:33:10 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-04-04 19:33:10 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-04-04 19:33:10 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-04-04 19:33:11 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-04-04 19:33:11 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-04-04 19:33:12 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-04-04 19:33:12 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-04-04 19:33:12 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-04-04 19:33:12 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-04-04 19:33:12 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-04-04 19:33:12 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-04-04 19:33:13 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-04-04 19:33:13 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-04-04 19:33:13 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '4890d6f3-aff3-45f1-bd49-ab3945501353', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 19:33:13 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-04-04 19:33:13 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-04-04 19:33:13 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-04-04 19:33:14 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-04-04 19:33:14 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-04-04 19:33:15 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-04-04 19:33:15 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-04-04 19:33:16 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-04-04 19:33:16 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-04-04 19:33:17 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-04-04 19:33:17 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-04-04 19:33:17 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-04-04 19:33:17 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-04-04 19:33:17 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-04-04 19:33:17 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-04-04 19:33:18 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-04-04 19:33:18 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-04-04 19:33:20 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-04-04 19:33:20 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-04-04 19:33:21 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-04-04 19:33:21 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-04-04 19:33:22 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-04-04 19:33:22 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-04-04 19:33:23 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-04-04 19:33:23 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-04-04 19:33:23 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-04-04 19:33:23 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-04-04 19:33:23 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-04-04 19:33:24 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-04-04 19:33:24 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-04-04 19:33:25 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-04-04 19:33:25 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-04-04 19:33:25 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-04-04 19:33:25 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-04-04 19:33:26 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-04-04 19:33:26 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-04-04 19:33:26 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-04-04 19:33:27 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-04-04 19:33:27 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:33:27 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:33:27 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:33:27 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '4590be55-f6bf-4eab-85e7-d3e503fe1568', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 19:33:27 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-04-04 19:33:28 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:33:28 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:33:28 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:33:28 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:33:29 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:33:29 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:33:29 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:33:29 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:33:31 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:33:31 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:33:31 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:33:31 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:33:32 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:33:32 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:33:33 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:33:33 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:33:34 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:33:34 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:33:39 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:33:39 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:33:41 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:33:41 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:33:43 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:33:43 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:33:44 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:33:44 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:33:54 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:33:54 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:34:06 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:34:06 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:34:10 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:34:10 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:34:10 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:34:10 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-04-04 19:34:11 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-04-04 19:34:11 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-04-04 19:34:13 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-04-04 19:34:13 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-04-04 19:34:16 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-04-04 19:34:16 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-04-04 19:34:24 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-04-04 19:34:24 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-04-04 19:34:54 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'bec74be7-06d6-479c-b155-5ed0cabe6685', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 19:34:54 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-04-04 19:34:54 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-04-04 19:34:54 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-04-04 19:34:54 - DEBUG UnitTestFramework: 'scheduling tests'

2017-04-04 19:34:55 - DEBUG UnitTestFramework: 'tests scheduled'

2017-04-04 19:34:55 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-04-04 19:34:55 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-04-04 19:34:55 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-04-04 19:34:55 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-04-04 19:34:55 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-04-04 19:34:55 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-04-04 19:34:55 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 19:34:56 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:34:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-04-04 19:34:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-04-04 19:34:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:34:57 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:34:57 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:34:57 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:34:57 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:34:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:34:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:34:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:34:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:34:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:34:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-04-04 19:34:58 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-04-04 19:34:59 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run: 'basic''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup: 'another''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run: 'another''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-04-04 19:35:00 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-04-04 19:35:03 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-04-04 19:35:03 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-04-04 19:35:04 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-04-04 19:35:05 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-04-04 19:35:05 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-04-04 19:35:05 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-04-04 19:35:05 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-04-04 19:35:05 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-04-04 19:35:05 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:35:05 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:35:05 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:35:06 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:35:06 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:35:06 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-04-04 19:35:06 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:35:06 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:35:06 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:35:07 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:35:07 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:35:08 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 19:35:08 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:35:08 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:35:08 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:35:09 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:35:09 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:35:09 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 19:35:09 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:35:09 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:35:09 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:35:09 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:35:09 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:35:10 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 19:35:10 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:35:10 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:35:10 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-04-04 19:35:11 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-04-04 19:35:13 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-04-04 19:35:13 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-04-04 19:35:14 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-04-04 19:35:14 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-04-04 19:35:14 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-04-04 19:35:14 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-04-04 19:35:27 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-04-04 19:35:27 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-04-04 19:35:27 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-04-04 19:35:27 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-04-04 19:35:28 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-04-04 19:35:28 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-04-04 19:35:34 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-04-04 19:35:34 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-04-04 19:35:35 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-04-04 19:35:35 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-04-04 19:35:36 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-04-04 19:35:36 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-04-04 19:35:43 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-04-04 19:35:43 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-04-04 19:35:44 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-04-04 19:35:44 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-04-04 19:35:44 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-04-04 19:35:44 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-04-04 19:35:44 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-04-04 19:35:44 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-04-04 19:35:44 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-04-04 19:35:44 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-04-04 19:35:44 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-04-04 19:35:44 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-04-04 19:35:44 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-04-04 19:35:44 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-04-04 19:35:44 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-04-04 19:35:46 - ERROR UnitTestFramework: '#run failed: 'discoveryAdvertisingStateUpdateNonTCP is called', error: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"4890d6f3-aff3-45f1-bd49-ab3945501353"},{"uuid":"4590be55-f6bf-4eab-85e7-d3e503fe1568"},{"uuid":"bec74be7-06d6-479c-b155-5ed0cabe6685"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"4890d6f3-aff3-45f1-bd49-ab3945501353"},{"uuid":"4590be55-f6bf-4eab-85e7-d3e503fe1568"},{"uuid":"bec74be7-06d6-479c-b155-5ed0cabe6685"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_113351851a786003/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_113351851a786003/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-04-04 19:35:46 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"4890d6f3-aff3-45f1-bd49-ab3945501353"},{"uuid":"4590be55-f6bf-4eab-85e7-d3e503fe1568"},{"uuid":"bec74be7-06d6-479c-b155-5ed0cabe6685"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"4890d6f3-aff3-45f1-bd49-ab3945501353"},{"uuid":"4590be55-f6bf-4eab-85e7-d3e503fe1568"},{"uuid":"bec74be7-06d6-479c-b155-5ed0cabe6685"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_113351851a786003/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_113351851a786003/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-04-04 19:37:24 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-04-04 19:37:24 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_113351851a786003/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-04-04 19:37:25 - DEBUG TestServer: 'completed'

2017-04-04 19:37:25 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-04-04 19:37:25 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-04-04 19:37:25 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-04-04 19:37:25 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-04-04 19:37:25 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-04-04 19:37:25 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: job.nodes [ { name: 'thali03', ip: '192.168.1.52' },
  { name: 'thali05', ip: '192.168.1.54' },
  { name: 'thali04', ip: '192.168.1.53' } ]
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk pi@192.168.1.52:~/test/builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk pi@192.168.1.54:~/test/builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk pi@192.168.1.53:~/test/builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk
copyCmd scp pi@192.168.1.52:~/*.json /Users/thali/Github/CI/tasker/results/113351851a786003/thali03/
copyCmd scp pi@192.168.1.54:~/*.json /Users/thali/Github/CI/tasker/results/113351851a786003/thali05/
copyCmd scp pi@192.168.1.53:~/*.json /Users/thali/Github/CI/tasker/results/113351851a786003/thali04/
Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!job.nodes [ { name: 'thali03', ip: '192.168.1.52' },
  { name: 'thali05', ip: '192.168.1.54' },
  { name: 'thali04', ip: '192.168.1.53' } ]
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk pi@192.168.1.52:~/test/builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk pi@192.168.1.54:~/test/builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk pi@192.168.1.53:~/test/builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk
copyCmd scp pi@192.168.1.52:~/*.json /Users/thali/Github/CI/tasker/results/113351851a786003/thali03/
copyCmd scp pi@192.168.1.54:~/*.json /Users/thali/Github/CI/tasker/results/113351851a786003/thali05/
copyCmd scp pi@192.168.1.53:~/*.json /Users/thali/Github/CI/tasker/results/113351851a786003/thali04/


ios : Error: Command failed: true
4/4/2017@21:28:29 Getting the list of iOS devices 
4/4/2017@21:28:30 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
4/4/2017@21:28:30 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
4/4/2017@21:28:30 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
4/4/2017@21:28:30 Deploying iOS test app 
4/4/2017@21:28:30 uninstalling the application 
4/4/2017@21:28:31 installing the application 
4/4/2017@21:51:49 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
4/4/2017@21:51:49 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
4/4/2017@21:51:49 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
deploy command: adb -s ce061606e320561102 install -r /home/pi/test/builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk&& adb -s ce061606e320561102 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851a786003_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce0616068b9f212302 install -r /home/pi/test/builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk&& adb -s ce0616068b9f212302 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce0616068b9f212302 install -r /home/pi/test/builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk&& adb -s ce0616068b9f212302 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851a786003_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)

####Node name: thali05
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606c181d71003 install -r /home/pi/test/builder/builds/113351851a786003/build_android/android_0_113351851a786003.apk&& adb -s ce061606c181d71003 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

App was succesfully started on ce061606c181d71003

STOP log received from ce061606c181d71003
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851a786003_CI_sanity_check_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/113351851a786003_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/113351851a786003_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/113351851a786003_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/113351851a786003_CI_sanity_check_jareksl/iOS_server.md)





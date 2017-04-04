#### Test 113351851d053c10 Logs

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
2017-04-04 10:48:28 - INFO HttpServer: 'listening on *:3000'

2017-04-04 10:48:32 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '3e771222-926f-474b-8ba9-28c6560ec242', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 10:48:32 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-04-04 10:48:34 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '3e771222-926f-474b-8ba9-28c6560ec242', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 10:48:34 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: '3e771222-926f-474b-8ba9-28c6560ec242', platformName: 'ios''

2017-04-04 10:48:35 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c79fa1a4-4259-4622-a006-bb96428f404e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 10:48:35 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-04-04 10:48:37 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '269b0973-11ed-44e0-8a33-f0803ce772b3', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 10:48:37 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-04-04 10:48:37 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-04-04 10:48:37 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-04-04 10:48:37 - DEBUG UnitTestFramework: 'scheduling tests'

2017-04-04 10:48:37 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c79fa1a4-4259-4622-a006-bb96428f404e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 10:48:37 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'c79fa1a4-4259-4622-a006-bb96428f404e', platformName: 'ios''

2017-04-04 10:48:39 - DEBUG UnitTestFramework: 'tests scheduled'

2017-04-04 10:48:39 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-04-04 10:48:39 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '269b0973-11ed-44e0-8a33-f0803ce772b3', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-04-04 10:48:39 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '269b0973-11ed-44e0-8a33-f0803ce772b3', platformName: 'ios''

2017-04-04 10:48:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-04-04 10:48:41 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-04-04 10:48:44 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-04-04 10:48:44 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-04-04 10:48:44 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-04-04 10:48:44 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-04-04 10:48:46 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-04-04 10:48:46 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-04-04 10:48:49 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-04-04 10:48:49 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-04-04 10:48:49 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-04-04 10:48:49 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 10:48:52 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 10:48:52 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 10:48:52 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 10:48:52 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 10:48:53 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-04-04 10:48:53 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 10:49:02 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 10:49:02 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 10:49:05 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 10:49:05 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 10:49:07 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-04-04 10:49:07 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 10:49:11 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 10:49:11 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 10:49:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-04-04 10:49:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-04-04 10:49:11 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-04-04 10:49:11 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 10:49:11 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 10:49:14 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-04-04 10:49:14 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 10:49:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 10:49:15 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 10:49:16 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 10:49:16 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 10:49:18 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 10:49:18 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 10:49:18 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 10:49:21 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-04-04 10:49:21 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 10:49:28 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 10:49:28 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 10:49:28 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 10:49:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 10:49:32 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 10:49:32 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 10:49:32 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 10:49:32 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-04-04 10:49:32 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 10:49:35 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 10:49:35 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 10:49:36 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 10:49:36 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 10:49:36 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 10:49:36 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 10:49:36 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 10:49:37 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-04-04 10:49:37 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-04-04 10:49:51 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-04-04 10:49:51 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-04-04 10:49:53 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-04-04 10:49:53 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-04-04 10:49:57 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-04-04 10:49:57 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-04-04 10:50:01 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-04-04 10:50:01 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-04-04 10:50:05 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-04-04 10:50:05 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-04-04 10:50:05 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-04-04 10:50:05 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-04-04 10:50:09 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-04-04 10:50:09 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-04-04 10:50:16 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-04-04 10:50:16 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-04-04 10:50:29 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-04-04 10:50:29 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-04-04 10:50:30 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-04-04 10:50:30 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-04-04 10:50:32 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-04-04 10:50:32 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-04-04 10:50:33 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-04-04 10:50:33 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-04-04 10:50:34 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-04-04 10:50:34 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-04-04 10:50:38 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-04-04 10:50:38 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-04-04 10:50:39 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-04-04 10:50:39 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-04-04 10:50:40 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-04-04 10:50:40 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-04-04 10:50:40 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-04-04 10:50:41 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-04-04 10:50:41 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-04-04 10:50:41 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-04-04 10:50:43 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-04-04 10:50:43 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-04-04 10:50:44 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-04-04 10:50:44 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-04-04 10:50:46 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-04-04 10:50:46 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-04-04 10:50:47 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-04-04 10:50:47 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-04-04 10:50:47 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-04-04 10:50:47 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-04-04 10:50:48 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-04-04 10:50:48 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-04-04 10:50:49 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-04-04 10:50:49 - DEBUG UnitTestFramework: '#run: 'basic''

2017-04-04 10:50:49 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-04-04 10:50:49 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-04-04 10:50:51 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-04-04 10:50:51 - DEBUG UnitTestFramework: '#setup: 'another''

2017-04-04 10:50:51 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-04-04 10:50:51 - DEBUG UnitTestFramework: '#run: 'another''

2017-04-04 10:50:52 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-04-04 10:50:52 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-04-04 10:50:53 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-04-04 10:50:53 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-04-04 10:50:53 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-04-04 10:50:53 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-04-04 10:50:55 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-04-04 10:50:55 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-04-04 10:50:55 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-04-04 10:50:55 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-04-04 10:50:56 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-04-04 10:50:56 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-04-04 10:50:59 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-04-04 10:50:59 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-04-04 10:50:59 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-04-04 10:50:59 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-04-04 10:51:00 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-04-04 10:51:00 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-04-04 10:51:02 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-04-04 10:51:02 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-04-04 10:51:03 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-04-04 10:51:03 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-04-04 10:51:03 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-04-04 10:51:03 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-04-04 10:51:03 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-04-04 10:51:03 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-04-04 10:51:04 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-04-04 10:51:04 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-04-04 10:51:07 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-04-04 10:51:07 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-04-04 10:51:09 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-04-04 10:51:09 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-04-04 10:51:12 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-04-04 10:51:12 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-04-04 10:51:14 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-04-04 10:51:14 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-04-04 10:51:15 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-04-04 10:51:15 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-04-04 10:51:19 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-04-04 10:51:19 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-04-04 10:51:32 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-04-04 10:51:32 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-04-04 10:51:48 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-04-04 10:51:48 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-04-04 10:51:49 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-04-04 10:51:49 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-04-04 10:52:01 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-04-04 10:52:01 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-04-04 10:52:02 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-04-04 10:52:02 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-04-04 10:52:02 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-04-04 10:52:02 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-04-04 10:52:02 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-04-04 10:52:03 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-04-04 10:52:03 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-04-04 10:52:04 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-04-04 10:52:04 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-04-04 10:52:05 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-04-04 10:52:06 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-04-04 10:52:06 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-04-04 10:52:06 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-04-04 10:52:06 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-04-04 10:52:07 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-04-04 10:52:07 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-04-04 10:52:08 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-04-04 10:52:08 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-04-04 10:52:10 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-04-04 10:52:10 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-04-04 10:52:12 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-04-04 10:52:12 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 10:52:13 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 10:52:13 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 10:52:16 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 10:52:16 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 10:52:16 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-04-04 10:52:16 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 10:52:17 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 10:52:17 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 10:52:18 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 10:52:18 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 10:52:20 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-04-04 10:52:20 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 10:52:21 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 10:52:21 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 10:52:22 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 10:52:22 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 10:52:23 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-04-04 10:52:23 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 10:52:24 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 10:52:24 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 10:52:25 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 10:52:25 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 10:52:26 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-04-04 10:52:26 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 10:52:27 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 10:52:27 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 10:52:27 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 10:52:27 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 10:52:30 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-04-04 10:52:30 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-04-04 10:52:30 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-04-04 10:52:30 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-04-04 10:52:32 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-04-04 10:52:32 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-04-04 10:52:35 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-04-04 10:52:35 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-04-04 10:52:58 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-04-04 10:52:58 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-04-04 10:53:28 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_113351851d053c10/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-04-04 10:53:28 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-04-04 10:53:28 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-04-04 10:53:28 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: job.nodes [ { name: 'thali03', ip: '192.168.1.52' },
  { name: 'thali01', ip: '192.168.1.50' },
  { name: 'thali04', ip: '192.168.1.53' } ]
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk pi@192.168.1.52:~/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk pi@192.168.1.50:~/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk pi@192.168.1.53:~/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk
copyCmd scp pi@192.168.1.52:~/*.json /Users/thali/Github/CI/tasker/results/113351851d053c10/thali03/
copyCmd scp pi@192.168.1.50:~/*.json /Users/thali/Github/CI/tasker/results/113351851d053c10/thali01/
copyCmd scp pi@192.168.1.53:~/*.json /Users/thali/Github/CI/tasker/results/113351851d053c10/thali04/
Error: Command failed: Android testing process has failed
 [0m

job.nodes [ { name: 'thali03', ip: '192.168.1.52' },
  { name: 'thali01', ip: '192.168.1.50' },
  { name: 'thali04', ip: '192.168.1.53' } ]
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk pi@192.168.1.52:~/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk pi@192.168.1.50:~/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk pi@192.168.1.53:~/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk
copyCmd scp pi@192.168.1.52:~/*.json /Users/thali/Github/CI/tasker/results/113351851d053c10/thali03/
copyCmd scp pi@192.168.1.50:~/*.json /Users/thali/Github/CI/tasker/results/113351851d053c10/thali01/
copyCmd scp pi@192.168.1.53:~/*.json /Users/thali/Github/CI/tasker/results/113351851d053c10/thali04/


ios : Error: Command failed: true
4/4/2017@12:44:41 Getting the list of iOS devices 
4/4/2017@12:44:42 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
4/4/2017@12:44:42 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
4/4/2017@12:44:42 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
4/4/2017@12:44:42 Deploying iOS test app 
4/4/2017@12:44:42 uninstalling the application 
4/4/2017@12:44:42 installing the application 
4/4/2017@13:08:01 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
4/4/2017@13:08:01 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
4/4/2017@13:08:01 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
true

```
###Android Logs
####Node name: thali01
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606c181d71003 install -r /home/pi/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk&& adb -s ce061606c181d71003 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851d053c10_CI_sanity_check_jareksl/thali01_samsung-SM-G930F.md)

####Node name: thali03
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606e320561102 install -r /home/pi/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk&& adb -s ce061606e320561102 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606e320561102 install -r /home/pi/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk&& adb -s ce061606e320561102 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G935F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851d053c10_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce0616068b9f212302 install -r /home/pi/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk&& adb -s ce0616068b9f212302 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce0616068b9f212302 install -r /home/pi/test/builder/builds/113351851d053c10/build_android/android_0_113351851d053c10.apk&& adb -s ce0616068b9f212302 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851d053c10_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/113351851d053c10_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/113351851d053c10_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/113351851d053c10_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/113351851d053c10_CI_sanity_check_jareksl/iOS_server.md)





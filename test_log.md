#### Test 11335185108be6d0 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":2,"android":0}}
2017-05-25 11:48:52 - INFO HttpServer: 'listening on *:3000'

2017-05-25 11:48:56 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'bce3d831-3dab-4b08-8487-823715dc5b41', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-25 11:48:56 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-05-25 11:48:59 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '9774306b-7e05-463f-b075-9ef100e4c31b', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-25 11:48:59 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-05-25 11:48:59 - INFO TestFramework: 'all required 2 devices are present for platformName: 'ios''

2017-05-25 11:48:59 - DEBUG UnitTestFramework: 'starting unit tests on 2 devices, platformName: 'ios''

2017-05-25 11:48:59 - DEBUG UnitTestFramework: 'scheduling tests'

2017-05-25 11:48:59 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'bce3d831-3dab-4b08-8487-823715dc5b41', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-25 11:48:59 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'bce3d831-3dab-4b08-8487-823715dc5b41', platformName: 'ios''

2017-05-25 11:49:00 - DEBUG UnitTestFramework: 'tests scheduled'

2017-05-25 11:49:00 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-05-25 11:49:00 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-05-25 11:49:00 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-05-25 11:49:00 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-05-25 11:49:00 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-05-25 11:49:01 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '9774306b-7e05-463f-b075-9ef100e4c31b', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-25 11:49:01 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '9774306b-7e05-463f-b075-9ef100e4c31b', platformName: 'ios''

2017-05-25 11:49:01 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-05-25 11:49:01 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-05-25 11:49:01 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-05-25 11:49:01 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-05-25 11:49:02 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-05-25 11:49:02 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-05-25 11:49:02 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-05-25 11:49:02 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-25 11:49:02 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-25 11:49:02 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-25 11:49:03 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-25 11:49:03 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-25 11:49:04 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-25 11:49:04 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-25 11:49:04 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-25 11:49:04 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-25 11:49:04 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-25 11:49:04 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-25 11:49:05 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-25 11:49:05 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-05-25 11:49:05 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-25 11:49:05 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-05-25 11:49:05 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-25 11:49:05 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-25 11:49:05 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-25 11:49:05 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-05-25 11:49:05 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-25 11:49:05 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-25 11:49:05 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-25 11:49:05 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-25 11:49:06 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-25 11:49:06 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-25 11:49:06 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-25 11:49:06 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-25 11:49:07 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-25 11:49:07 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-25 11:49:08 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-25 11:49:08 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-25 11:49:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-25 11:49:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-25 11:49:08 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-25 11:49:08 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-25 11:49:08 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-25 11:49:08 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-25 11:49:08 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-25 11:49:08 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-25 11:49:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-25 11:49:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-25 11:49:08 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-25 11:49:08 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-25 11:49:09 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-25 11:49:09 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-05-25 11:49:09 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-05-25 11:49:09 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-05-25 11:49:09 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-05-25 11:49:09 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-05-25 11:49:11 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-05-25 11:49:11 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-05-25 11:49:11 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-05-25 11:49:11 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-05-25 11:49:11 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-05-25 11:49:11 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-05-25 11:49:12 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-05-25 11:49:12 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-05-25 11:49:13 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-05-25 11:49:13 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-05-25 11:49:14 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-05-25 11:49:14 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-05-25 11:49:14 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-05-25 11:49:14 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-05-25 11:49:14 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-05-25 11:49:14 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-05-25 11:49:14 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-05-25 11:49:14 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-05-25 11:49:15 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-05-25 11:49:15 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-05-25 11:49:15 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-05-25 11:49:15 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-05-25 11:49:15 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-05-25 11:49:15 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-05-25 11:49:16 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-05-25 11:49:16 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-05-25 11:49:17 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-05-25 11:49:17 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-05-25 11:49:18 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-05-25 11:49:18 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-05-25 11:49:18 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-05-25 11:49:18 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-05-25 11:49:18 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-05-25 11:49:18 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-05-25 11:49:18 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-05-25 11:49:18 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-05-25 11:49:18 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-05-25 11:49:18 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-05-25 11:49:19 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-05-25 11:49:19 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-05-25 11:49:19 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-05-25 11:49:19 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-05-25 11:49:19 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-05-25 11:49:19 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-05-25 11:49:19 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-05-25 11:49:19 - DEBUG UnitTestFramework: '#run: 'basic''

2017-05-25 11:49:21 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-05-25 11:49:21 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-05-25 11:49:22 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-05-25 11:49:22 - DEBUG UnitTestFramework: '#setup: 'another''

2017-05-25 11:49:23 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-05-25 11:49:23 - DEBUG UnitTestFramework: '#run: 'another''

2017-05-25 11:49:24 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-05-25 11:49:24 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-05-25 11:49:25 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-05-25 11:49:25 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-05-25 11:49:25 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-05-25 11:49:25 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-05-25 11:49:25 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-05-25 11:49:25 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-05-25 11:49:27 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-05-25 11:49:27 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-05-25 11:49:27 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-05-25 11:49:27 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-05-25 11:49:28 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-05-25 11:49:28 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-05-25 11:49:28 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-05-25 11:49:28 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-05-25 11:49:28 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-05-25 11:49:28 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-05-25 11:49:28 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-05-25 11:49:28 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-05-25 11:49:29 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-05-25 11:49:29 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-05-25 11:49:29 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-05-25 11:49:29 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-05-25 11:49:30 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-05-25 11:49:30 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-05-25 11:49:31 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-05-25 11:49:31 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-05-25 11:49:31 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-05-25 11:49:31 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-05-25 11:49:32 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-05-25 11:49:32 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-05-25 11:49:32 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-05-25 11:49:32 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-05-25 11:49:33 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-05-25 11:49:33 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-05-25 11:49:33 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-05-25 11:49:33 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-05-25 11:49:33 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-05-25 11:49:33 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-05-25 11:49:33 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-05-25 11:49:33 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-05-25 11:49:34 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-05-25 11:49:34 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-05-25 11:49:34 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-05-25 11:49:34 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-05-25 11:49:36 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-05-25 11:49:36 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-05-25 11:49:36 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-25 11:49:37 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-05-25 11:49:37 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-05-25 11:49:37 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-05-25 11:49:37 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-05-25 11:49:37 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-05-25 11:49:40 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-05-25 11:49:40 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-05-25 11:49:40 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-25 11:49:40 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-05-25 11:49:40 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-05-25 11:49:40 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-05-25 11:49:41 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-05-25 11:49:41 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-05-25 11:49:41 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-05-25 11:49:41 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-05-25 11:49:41 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-05-25 11:49:41 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-25 11:49:43 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-25 11:49:44 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-25 11:49:44 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-25 11:49:46 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-25 11:49:46 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-25 11:49:46 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-25 11:49:46 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-25 11:49:46 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-25 11:49:46 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-25 11:49:47 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-25 11:49:47 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-25 11:49:47 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-25 11:49:47 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-25 11:49:47 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-25 11:49:47 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-25 11:49:47 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-25 11:49:47 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-25 11:49:48 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-25 11:49:48 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-25 11:49:48 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-25 11:49:48 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-05-25 11:49:48 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-05-25 11:49:48 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-05-25 11:49:50 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-05-25 11:49:50 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-05-25 11:49:52 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-05-25 11:49:52 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-05-25 11:49:52 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-05-25 11:49:52 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-05-25 11:50:02 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-05-25 11:50:02 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-05-25 11:50:03 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-05-25 11:50:03 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-05-25 11:50:03 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-05-25 11:50:03 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-05-25 11:50:27 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '1ef8dd98-e4f4-436c-ad24-22cfc67a4f2d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-25 11:50:27 - ERROR HttpServer: 'unexpected server error: 'undefined''

2017-05-25 11:50:27 - ERROR TestServerProcess: 'uncaught exception, error: 'Error', stack: 'Error
    at Server._error (/home/pi/Test/server_11335185108be6d0/test/TestServer/HttpServer.js:78:9)
    at Socket.emit (events.js:82:17)
    at Socket.emit (/home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/lib/socket.js:128:10)
    at Socket.onerror (/home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/lib/socket.js:401:10)
    at Client.onerror (/home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/lib/client.js:210:24)
    at Client.ondata (/home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/lib/client.js:177:10)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)
    at Receiver.ontext (/home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/WebSocket.js:841:10)
    at /home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:536:18
    at /home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/Receiver.js:368:7
    at /home/pi/Test/server_11335185108be6d0/test/TestServer/node_modules/socket.io/node_modules/engine.io/node_modules/ws/lib/PerMessageDeflate.js:249:5''

2017-05-25 11:50:27 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-05-25 11:50:27 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-05-25 11:50:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

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
25/5/2017@13:45:29 Getting the list of iOS devices 
25/5/2017@13:45:30 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
25/5/2017@13:45:30 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
25/5/2017@13:45:30 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
25/5/2017@13:45:30 Deploying iOS test app 
25/5/2017@13:45:30 uninstalling the application 
25/5/2017@13:45:30 installing the application 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/11335185108be6d0_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/11335185108be6d0_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/11335185108be6d0_CI_sanity_check_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/11335185108be6d0_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/11335185108be6d0_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/11335185108be6d0_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)





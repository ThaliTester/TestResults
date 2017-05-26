#### Test 11335185121bd3e3 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-05-26 13:40:39 - INFO HttpServer: 'listening on *:3000'

2017-05-26 13:40:44 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'ce907a85-5c85-47e8-a0a5-0b3a055eb086', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 13:40:44 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-05-26 13:40:45 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'ce907a85-5c85-47e8-a0a5-0b3a055eb086', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 13:40:45 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: 'ce907a85-5c85-47e8-a0a5-0b3a055eb086', platformName: 'ios''

2017-05-26 13:40:52 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'd83a81ef-5c64-4227-a61c-8f5f248afed9', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 13:40:52 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-05-26 13:42:13 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '299e3e18-1259-4b87-8312-39f570c29347', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 13:42:13 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-05-26 13:42:17 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '341e3aa8-96a3-41e8-b618-a2f723a64c8f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 13:42:17 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-05-26 13:44:01 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '3da4b12a-8807-4b03-aca6-70d20dd8477e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-26 13:44:01 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-05-26 13:44:01 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-05-26 13:44:01 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-05-26 13:44:01 - DEBUG UnitTestFramework: 'scheduling tests'

2017-05-26 13:44:02 - DEBUG UnitTestFramework: 'tests scheduled'

2017-05-26 13:44:02 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-05-26 13:44:02 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-05-26 13:44:02 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-05-26 13:44:02 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-05-26 13:44:02 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-05-26 13:44:02 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-05-26 13:44:02 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-05-26 13:44:02 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-05-26 13:44:02 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 13:44:03 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-26 13:44:03 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-26 13:44:03 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 13:44:03 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 13:44:04 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 13:44:04 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 13:44:04 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 13:44:04 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 13:44:04 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 13:44:04 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 13:44:04 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 13:44:04 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 13:44:04 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-05-26 13:44:04 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-05-26 13:44:05 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#run: 'basic''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#setup: 'another''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#run: 'another''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-05-26 13:44:06 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-05-26 13:44:07 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-05-26 13:44:11 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-05-26 13:44:12 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-05-26 13:44:13 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-05-26 13:44:13 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-05-26 13:44:13 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-05-26 13:44:13 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 13:44:14 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 13:44:14 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 13:44:15 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 13:44:15 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 13:44:15 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-05-26 13:44:15 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 13:44:15 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 13:44:15 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 13:44:15 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 13:44:15 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 13:44:16 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-05-26 13:44:16 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 13:44:16 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 13:44:16 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 13:44:16 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 13:44:16 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 13:44:16 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-05-26 13:44:16 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 13:44:17 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 13:44:17 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 13:44:17 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 13:44:17 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 13:44:18 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-05-26 13:44:18 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 13:44:18 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 13:44:18 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 13:44:18 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 13:44:18 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 13:44:18 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-05-26 13:44:18 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-05-26 13:44:18 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-05-26 13:44:18 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-05-26 13:44:20 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-05-26 13:44:20 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-05-26 13:44:21 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-05-26 13:44:21 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-05-26 13:44:21 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-05-26 13:44:21 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-05-26 13:44:38 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-05-26 13:44:38 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-05-26 13:44:39 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-05-26 13:44:39 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-05-26 13:44:39 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-05-26 13:44:39 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-05-26 13:44:47 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-05-26 13:44:47 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-05-26 13:44:48 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-05-26 13:44:48 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-05-26 13:44:48 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-05-26 13:44:48 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-05-26 13:44:48 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-05-26 13:44:48 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-05-26 13:44:48 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-05-26 13:44:48 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-05-26 13:44:48 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-05-26 13:44:48 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-05-26 13:44:48 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-05-26 13:44:48 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-05-26 13:44:48 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-05-26 13:45:02 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-05-26 13:45:02 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-05-26 13:45:02 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-05-26 13:45:02 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-05-26 13:45:03 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-05-26 13:45:03 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-05-26 13:45:26 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-05-26 13:45:26 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-05-26 13:45:27 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-05-26 13:45:27 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 13:45:27 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 13:45:27 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 13:45:34 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 13:45:34 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 13:45:35 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-05-26 13:45:35 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-05-26 13:45:35 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-05-26 13:45:35 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-05-26 13:45:35 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-05-26 13:45:36 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-05-26 13:45:36 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-05-26 13:45:36 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-05-26 13:45:36 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-05-26 13:45:36 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-05-26 13:45:36 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-26 13:45:37 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-26 13:45:37 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-05-26 13:45:39 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_11335185121bd3e3/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-26 13:45:39 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-05-26 13:45:39 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-05-26 13:45:39 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-05-26 13:45:39 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-05-26 13:45:39 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
26/5/2017@15:37:25 Getting the list of iOS devices 
26/5/2017@15:37:26 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
26/5/2017@15:37:26 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
26/5/2017@15:37:26 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
26/5/2017@15:37:26 Deploying iOS test app 
26/5/2017@15:37:26 uninstalling the application 
26/5/2017@15:37:27 installing the application 
26/5/2017@15:39:46 ios: child process exited with code 253 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
26/5/2017@16:00:45 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
26/5/2017@16:00:45 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/11335185121bd3e3_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/11335185121bd3e3_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/11335185121bd3e3_CI_sanity_check_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/11335185121bd3e3_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/11335185121bd3e3_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/11335185121bd3e3_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/11335185121bd3e3_CI_sanity_check_jareksl/iOS_server.md)





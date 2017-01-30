#### Test 103691986c90445e Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2017-01-30 08:37:01 - INFO HttpServer: 'listening on *:3000'

2017-01-30 08:38:31 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '79bc83ab-b38d-4d01-bb09-d9b917672205', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-30 08:38:31 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-30 08:38:31 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '50a4a1f0-2894-40f3-adb0-4b5d1256a24d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-30 08:38:31 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-30 08:40:08 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'b549fd82-87ee-4125-bdbf-3e2cc50159b4', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-30 08:40:08 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-01-30 08:40:08 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-01-30 08:40:08 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-01-30 08:40:08 - DEBUG UnitTestFramework: 'scheduling tests'

2017-01-30 08:40:09 - DEBUG UnitTestFramework: 'tests scheduled'

2017-01-30 08:40:09 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-01-30 08:40:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-01-30 08:40:09 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-30 08:40:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-30 08:40:12 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-30 08:40:12 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-01-30 08:40:12 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-01-30 08:40:12 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-30 08:40:13 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-30 08:40:16 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-30 08:40:16 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-30 08:40:16 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-30 08:40:16 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-30 08:40:16 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-30 08:40:16 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-01-30 08:40:17 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run: 'basic''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup: 'another''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run: 'another''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-01-30 08:40:18 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-01-30 08:40:19 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-01-30 08:40:21 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-01-30 08:40:21 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-01-30 08:40:21 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-01-30 08:40:21 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-01-30 08:40:21 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-01-30 08:40:21 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-01-30 08:40:22 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-01-30 08:40:22 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-01-30 08:40:23 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-01-30 08:40:23 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-01-30 08:40:23 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-01-30 08:40:23 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-01-30 08:40:23 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-01-30 08:40:23 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-01-30 08:40:23 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-01-30 08:40:23 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-01-30 08:40:23 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-01-30 08:40:23 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-01-30 08:40:24 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-01-30 08:40:24 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-01-30 08:40:24 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-01-30 08:40:24 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-01-30 08:40:24 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-01-30 08:40:24 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-01-30 08:40:25 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-01-30 08:40:28 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-01-30 08:40:28 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-01-30 08:40:28 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-01-30 08:40:28 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-01-30 08:40:28 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-01-30 08:40:28 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-01-30 08:40:43 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-01-30 08:40:43 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-01-30 08:40:45 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-01-30 08:40:45 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-01-30 08:40:45 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-01-30 08:40:45 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-01-30 08:40:52 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-01-30 08:40:52 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-01-30 08:40:52 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-01-30 08:40:52 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-01-30 08:40:52 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-01-30 08:40:52 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-01-30 08:41:00 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-01-30 08:41:00 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-01-30 08:41:00 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-01-30 08:41:00 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-01-30 08:41:01 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-01-30 08:41:01 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-01-30 08:41:01 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-01-30 08:41:01 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-01-30 08:41:08 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-01-30 08:41:08 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-01-30 08:41:09 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-01-30 08:41:09 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-01-30 08:41:09 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-01-30 08:41:09 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-01-30 08:41:17 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-01-30 08:41:17 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-01-30 08:41:18 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-01-30 08:41:18 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-01-30 08:41:18 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-01-30 08:41:18 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-01-30 08:41:44 - ERROR UnitTestFramework: '#run failed: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', error: 'Error: run failed, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', sent data: '[{"uuid":"79bc83ab-b38d-4d01-bb09-d9b917672205"},{"uuid":"50a4a1f0-2894-40f3-adb0-4b5d1256a24d"},{"uuid":"b549fd82-87ee-4125-bdbf-3e2cc50159b4"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', sent data: '[{"uuid":"79bc83ab-b38d-4d01-bb09-d9b917672205"},{"uuid":"50a4a1f0-2894-40f3-adb0-4b5d1256a24d"},{"uuid":"b549fd82-87ee-4125-bdbf-3e2cc50159b4"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_103691986c90445e/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_103691986c90445e/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-01-30 08:41:44 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: run failed, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', sent data: '[{"uuid":"79bc83ab-b38d-4d01-bb09-d9b917672205"},{"uuid":"50a4a1f0-2894-40f3-adb0-4b5d1256a24d"},{"uuid":"b549fd82-87ee-4125-bdbf-3e2cc50159b4"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', event: 'run_#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection', sent data: '[{"uuid":"79bc83ab-b38d-4d01-bb09-d9b917672205"},{"uuid":"50a4a1f0-2894-40f3-adb0-4b5d1256a24d"},{"uuid":"b549fd82-87ee-4125-bdbf-3e2cc50159b4"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_103691986c90445e/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_103691986c90445e/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_103691986c90445e/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-01-30 08:42:01 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_103691986c90445e/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-30 08:42:01 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-01-30 08:42:01 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-01-30 08:42:01 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali02
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

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/103691986c90445e_Update_Android_tools_versions_czyzm/thali02_samsung-SM-G930F.md)

####Node name: thali03
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/103691986c90445e_Update_Android_tools_versions_czyzm/thali03_samsung-SM-G930F.md)

####Node name: thali04
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/103691986c90445e_Update_Android_tools_versions_czyzm/thali04_samsung-SM-G935F.md)




###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/103691986c90445e_Update_Android_tools_versions_czyzm/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/103691986c90445e_Update_Android_tools_versions_czyzm/iOS_iphone-5s-mfts.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/103691986c90445e_Update_Android_tools_versions_czyzm/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/103691986c90445e_Update_Android_tools_versions_czyzm/iOS_iphone-5s-1.md)



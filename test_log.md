#### Test 109247054fc76087 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
Enter ____.js
Targets defined
http required
Creating internal server
Got request
URL:  [ 'ios', '3' ]
Enter checkIt
Got request
URL:  [ 'nodes', '2' ]
Got request
URL:  [ 'droid', '1' ]
Got request
URL:  [ 'droid', '1' ]
Enter checkIt
checkIt do the job
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":2}}
2017-03-27 12:27:25 - INFO HttpServer: 'listening on *:3000'

2017-03-27 12:27:26 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '995e2512-89e8-4db3-b82a-34229503dbeb', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-27 12:27:26 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-03-27 12:27:32 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'd79c4f76-4b4e-4eb1-863a-5949e17d9373', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-27 12:27:32 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-03-27 12:27:34 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'd79c4f76-4b4e-4eb1-863a-5949e17d9373', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-27 12:27:34 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: 'd79c4f76-4b4e-4eb1-863a-5949e17d9373', platformName: 'ios''

2017-03-27 12:27:58 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'a5c05263-ea38-4c16-b403-29bc3f037892', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-27 12:27:58 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-03-27 12:27:58 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-03-27 12:27:58 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-03-27 12:27:58 - DEBUG UnitTestFramework: 'scheduling tests'

2017-03-27 12:28:00 - DEBUG UnitTestFramework: 'tests scheduled'

2017-03-27 12:28:00 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-03-27 12:28:01 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-03-27 12:28:01 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-03-27 12:28:01 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-03-27 12:28:01 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-03-27 12:28:02 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-03-27 12:28:02 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-03-27 12:28:04 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-03-27 12:28:04 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-03-27 12:28:06 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-03-27 12:28:06 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-03-27 12:28:08 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-03-27 12:28:08 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-27 12:28:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-27 12:28:09 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-27 12:28:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-27 12:28:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-27 12:28:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-27 12:28:10 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-27 12:28:11 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-27 12:28:11 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-27 12:28:14 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-27 12:28:14 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-27 12:28:14 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-27 12:28:14 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-03-27 12:28:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-03-27 12:28:15 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-03-27 12:28:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-03-27 12:28:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-03-27 12:28:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-03-27 12:28:16 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-03-27 12:28:16 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-03-27 12:28:18 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-03-27 12:28:18 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-27 12:28:19 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-27 12:28:19 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-27 12:28:20 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-03-27 12:28:20 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-03-27 12:28:21 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-03-27 12:28:21 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-27 12:28:21 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-27 12:28:25 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-27 12:28:25 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-27 12:28:29 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-27 12:28:29 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-27 12:28:30 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-27 12:28:31 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-27 12:28:33 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-27 12:28:33 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-27 12:28:33 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-27 12:28:35 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-27 12:28:35 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-27 12:28:38 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-27 12:28:38 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-27 12:28:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-27 12:28:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-27 12:28:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-27 12:28:38 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-27 12:28:38 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-27 12:28:41 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-27 12:28:41 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-03-27 12:28:43 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-03-27 12:28:43 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-03-27 12:28:45 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-03-27 12:28:45 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-03-27 12:28:49 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-03-27 12:28:49 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-03-27 12:28:52 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-03-27 12:28:52 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-03-27 12:28:55 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-03-27 12:28:55 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-03-27 12:28:56 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-03-27 12:28:56 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-03-27 12:28:57 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-03-27 12:28:57 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-03-27 12:28:58 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-03-27 12:28:58 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-03-27 12:28:59 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-03-27 12:28:59 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-03-27 12:29:00 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-03-27 12:29:00 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-03-27 12:29:01 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-03-27 12:29:01 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-03-27 12:29:03 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-03-27 12:29:03 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-03-27 12:29:04 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-03-27 12:29:04 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-03-27 12:29:06 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-03-27 12:29:06 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-03-27 12:29:07 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-03-27 12:29:07 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-03-27 12:29:08 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-03-27 12:29:08 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-03-27 12:29:09 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-03-27 12:29:09 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-03-27 12:29:09 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-03-27 12:29:09 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-03-27 12:29:10 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-03-27 12:29:10 - DEBUG UnitTestFramework: '#run: 'basic''

2017-03-27 12:29:12 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-03-27 12:29:12 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-03-27 12:29:13 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-03-27 12:29:13 - DEBUG UnitTestFramework: '#setup: 'another''

2017-03-27 12:29:15 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-03-27 12:29:15 - DEBUG UnitTestFramework: '#run: 'another''

2017-03-27 12:29:17 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-03-27 12:29:17 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-03-27 12:29:17 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-03-27 12:29:17 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-03-27 12:29:19 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-03-27 12:29:19 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-03-27 12:29:21 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-03-27 12:29:21 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-03-27 12:29:24 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-03-27 12:29:24 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-03-27 12:29:26 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-03-27 12:29:26 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-03-27 12:29:27 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-03-27 12:29:27 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-03-27 12:29:27 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-03-27 12:29:27 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-03-27 12:29:27 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-03-27 12:29:27 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-03-27 12:29:27 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-03-27 12:29:28 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-03-27 12:29:28 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-03-27 12:29:28 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-03-27 12:29:28 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-03-27 12:29:30 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-03-27 12:29:30 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-03-27 12:29:31 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-03-27 12:29:31 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-03-27 12:29:31 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-03-27 12:29:31 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-03-27 12:29:31 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-03-27 12:29:31 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-03-27 12:29:31 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-03-27 12:29:32 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-03-27 12:29:32 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-03-27 12:29:32 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-03-27 12:29:32 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-03-27 12:29:37 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-03-27 12:29:37 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-03-27 12:29:41 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-03-27 12:29:41 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-27 12:29:42 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-27 12:29:42 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-27 12:29:42 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-27 12:29:42 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-27 12:29:44 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-27 12:29:44 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-27 12:29:46 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-27 12:29:46 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-27 12:29:46 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-27 12:29:46 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-27 12:29:47 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-27 12:29:47 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-27 12:29:48 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-27 12:29:48 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-27 12:29:50 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-27 12:29:50 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-27 12:29:51 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-27 12:29:51 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-27 12:29:52 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-27 12:29:52 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-27 12:29:53 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-27 12:29:53 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-27 12:30:01 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-27 12:30:01 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-27 12:30:09 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-27 12:30:09 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-27 12:31:32 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'ping timeout''

2017-03-27 12:32:09 - ERROR Socket: 'unexpected error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_109247054fc76087/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-03-27 12:32:09 - ERROR UnitTestFramework: '#run failed: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error', error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_109247054fc76087/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-03-27 12:32:09 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'Error: retry count exceed', stack: 'Error: retry count exceed
    at emit (/home/pi/Test/server_109247054fc76087/test/TestServer/Socket.js:157:16)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-03-27 12:32:15 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'a5c05263-ea38-4c16-b403-29bc3f037892', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-27 12:32:15 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'a5c05263-ea38-4c16-b403-29bc3f037892', platformName: 'ios''

2017-03-27 12:32:17 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'a5c05263-ea38-4c16-b403-29bc3f037892', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-27 12:32:17 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'a5c05263-ea38-4c16-b403-29bc3f037892', platformName: 'ios''

2017-03-27 12:32:25 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_109247054fc76087/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-03-27 12:32:25 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-03-27 12:32:25 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-03-27 12:32:25 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

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
27/3/2017@14:23:58 Getting the list of iOS devices 
27/3/2017@14:23:59 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
27/3/2017@14:23:59 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
27/3/2017@14:23:59 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
27/3/2017@14:23:59 Deploying iOS test app 
27/3/2017@14:23:59 uninstalling the application 
27/3/2017@14:24:00 installing the application 
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

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G935F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/109247054fc76087_iOS_swift_3_0_migration_dersim-davaod/thali03_samsung-SM-G935F.md)

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

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/109247054fc76087_iOS_swift_3_0_migration_dersim-davaod/thali04_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/109247054fc76087_iOS_swift_3_0_migration_dersim-davaod/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/109247054fc76087_iOS_swift_3_0_migration_dersim-davaod/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/109247054fc76087_iOS_swift_3_0_migration_dersim-davaod/iOS_ipad-air-2-1.md)





#### Test 109247054a32d624 Logs

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
2017-03-21 11:27:35 - INFO HttpServer: 'listening on *:3000'

2017-03-21 11:27:44 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'f58c3ca3-43bb-4784-891c-e307efe95384', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-21 11:27:44 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-03-21 11:27:46 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'f58c3ca3-43bb-4784-891c-e307efe95384', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-21 11:27:46 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: 'f58c3ca3-43bb-4784-891c-e307efe95384', platformName: 'ios''

2017-03-21 11:27:48 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '167aa395-ff29-42dc-8467-56436fde00e7', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-21 11:27:48 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-03-21 11:28:12 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '6a246641-d31f-4936-9ff9-655f320a8482', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-21 11:28:12 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-03-21 11:28:12 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-03-21 11:28:12 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-03-21 11:28:12 - DEBUG UnitTestFramework: 'scheduling tests'

2017-03-21 11:28:14 - DEBUG UnitTestFramework: 'tests scheduled'

2017-03-21 11:28:14 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-03-21 11:28:15 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-03-21 11:28:15 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-03-21 11:28:15 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-03-21 11:28:15 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-03-21 11:28:15 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-03-21 11:28:15 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-03-21 11:28:16 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-03-21 11:28:16 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-03-21 11:28:16 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-03-21 11:28:16 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-03-21 11:28:16 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-03-21 11:28:16 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-21 11:28:16 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-21 11:28:16 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-21 11:28:17 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-21 11:28:17 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-21 11:28:18 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-21 11:28:18 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-21 11:28:19 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-21 11:28:19 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-21 11:28:20 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-21 11:28:20 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-21 11:28:21 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-21 11:28:21 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-03-21 11:28:21 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-03-21 11:28:21 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-03-21 11:28:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-03-21 11:28:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-03-21 11:28:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-03-21 11:28:21 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-03-21 11:28:21 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-03-21 11:28:21 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-03-21 11:28:21 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-21 11:28:24 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-21 11:28:24 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-21 11:28:24 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-03-21 11:28:25 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-03-21 11:28:26 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-03-21 11:28:26 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-21 11:28:26 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-21 11:28:26 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-21 11:28:26 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-21 11:28:27 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-21 11:28:27 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-21 11:28:27 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-21 11:28:27 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-21 11:28:28 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-21 11:28:28 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-21 11:28:28 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-21 11:28:34 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-21 11:28:34 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-21 11:28:35 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-21 11:28:35 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-21 11:28:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-21 11:28:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-21 11:28:35 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-21 11:28:35 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-21 11:28:35 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-21 11:28:36 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-21 11:28:36 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-03-21 11:28:39 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-03-21 11:28:39 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-03-21 11:28:40 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-03-21 11:28:40 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-03-21 11:28:41 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-03-21 11:28:41 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-03-21 11:28:43 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-03-21 11:28:43 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-03-21 11:28:46 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-03-21 11:28:46 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-03-21 11:28:59 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-03-21 11:28:59 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-03-21 11:29:00 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-03-21 11:29:00 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-03-21 11:29:03 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-03-21 11:29:03 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-03-21 11:29:05 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-03-21 11:29:05 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-03-21 11:29:06 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-03-21 11:29:06 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-03-21 11:29:07 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-03-21 11:29:07 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-03-21 11:29:09 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-03-21 11:29:09 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-03-21 11:29:11 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-03-21 11:29:11 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-03-21 11:29:12 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-03-21 11:29:12 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-03-21 11:29:13 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-03-21 11:29:13 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-03-21 11:29:14 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-03-21 11:29:14 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-03-21 11:29:14 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-03-21 11:29:14 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-03-21 11:29:14 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-03-21 11:29:14 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-03-21 11:29:14 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-03-21 11:29:14 - DEBUG UnitTestFramework: '#run: 'basic''

2017-03-21 11:29:14 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-03-21 11:29:14 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-03-21 11:29:15 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-03-21 11:29:15 - DEBUG UnitTestFramework: '#setup: 'another''

2017-03-21 11:29:15 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-03-21 11:29:15 - DEBUG UnitTestFramework: '#run: 'another''

2017-03-21 11:29:16 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-03-21 11:29:16 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-03-21 11:29:17 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-03-21 11:29:17 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-03-21 11:29:18 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-03-21 11:29:18 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-03-21 11:29:18 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-03-21 11:29:18 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-03-21 11:29:19 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-03-21 11:29:19 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-03-21 11:29:19 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-03-21 11:29:19 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-03-21 11:29:19 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-03-21 11:29:19 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-03-21 11:29:20 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-03-21 11:29:20 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-03-21 11:29:22 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-03-21 11:29:22 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-03-21 11:29:23 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-03-21 11:29:23 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-03-21 11:29:23 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-03-21 11:29:23 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-03-21 11:29:23 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-03-21 11:29:24 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-03-21 11:29:24 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-03-21 11:29:25 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-03-21 11:29:25 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-03-21 11:29:25 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-03-21 11:29:25 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-03-21 11:29:26 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-03-21 11:29:26 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-03-21 11:29:26 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-03-21 11:29:28 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-03-21 11:29:28 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-03-21 11:29:29 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-03-21 11:29:29 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-03-21 11:29:31 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-03-21 11:29:31 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-03-21 11:29:32 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''
2017-03-21 11:29:32 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-21 11:29:33 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-21 11:29:33 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-21 11:29:33 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-21 11:29:33 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-21 11:29:34 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-21 11:29:34 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-21 11:29:35 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-21 11:29:35 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-21 11:29:37 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-21 11:29:37 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-21 11:29:37 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-21 11:29:37 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-21 11:29:38 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-21 11:29:38 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-21 11:29:38 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-21 11:29:38 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-21 11:29:39 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-21 11:29:39 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-21 11:29:39 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-21 11:29:39 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-21 11:29:40 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-21 11:29:40 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-21 11:29:41 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-21 11:29:41 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-21 11:29:42 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-21 11:29:42 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-21 11:29:44 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-21 11:29:44 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-21 11:29:46 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-21 11:29:46 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-03-21 11:29:47 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-03-21 11:29:47 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-03-21 11:29:49 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-03-21 11:29:49 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-03-21 11:29:50 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-03-21 11:29:50 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-03-21 11:29:51 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-03-21 11:29:51 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-03-21 11:30:02 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'transport close''

2017-03-21 11:30:02 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'transport close''

2017-03-21 11:32:35 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_109247054a32d624/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-03-21 11:32:35 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

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
21/3/2017@12:24:13 Getting the list of iOS devices 
21/3/2017@12:24:14 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
21/3/2017@12:24:14 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
21/3/2017@12:24:14 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
21/3/2017@12:24:14 Deploying iOS test app 
21/3/2017@12:24:14 uninstalling the application 
21/3/2017@12:24:14 installing the application 
21/3/2017@12:30:00 ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
21/3/2017@12:30:00 ios: child process exited with code 254 on device bffa901fefdea07f59339a6737776943349f5077 
21/3/2017@12:47:33 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###Android Logs
####Node name: thali02
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

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/109247054a32d624_iOS_swift_3_0_migration_dersim-davaod/thali02_samsung-SM-G930F.md)

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

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G935F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/109247054a32d624_iOS_swift_3_0_migration_dersim-davaod/thali03_samsung-SM-G935F.md)

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

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/109247054a32d624_iOS_swift_3_0_migration_dersim-davaod/thali04_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/109247054a32d624_iOS_swift_3_0_migration_dersim-davaod/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/109247054a32d624_iOS_swift_3_0_migration_dersim-davaod/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/109247054a32d624_iOS_swift_3_0_migration_dersim-davaod/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/109247054a32d624_iOS_swift_3_0_migration_dersim-davaod/iOS_server.md)





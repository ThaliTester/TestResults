#### Test 1041482372a8f404 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 2 ]
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
2017-02-15 13:48:03 - INFO HttpServer: 'listening on *:3000'

2017-02-15 13:48:23 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: '9bbe97df-f24e-4a79-87ac-9a7c1908f4c4', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 13:48:23 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-mini-mfts''

2017-02-15 13:48:23 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'a9e0b280-91a1-41a5-81c0-b3864d5597b1', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 13:48:23 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-02-15 13:48:53 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-6-2', uuid: '378e5d2b-91a5-4524-a68b-157189cf7931', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 13:48:53 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-6-2''

2017-02-15 13:48:53 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-02-15 13:48:53 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-02-15 13:48:53 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-15 13:48:56 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-15 13:48:56 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-15 13:48:56 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-15 13:48:56 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-15 13:48:56 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-15 13:48:56 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-15 13:48:57 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-15 13:48:57 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-15 13:48:57 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-15 13:48:57 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-15 13:48:58 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-15 13:48:58 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-15 13:48:58 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-15 13:48:58 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:48:59 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:48:59 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:48:59 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:48:59 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:49:00 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:49:00 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:49:00 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:49:00 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:49:00 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:49:00 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:49:00 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:49:00 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:49:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-15 13:49:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-15 13:49:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:49:01 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:49:01 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:49:01 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:49:01 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:49:02 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:49:02 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:49:02 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:49:02 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:49:02 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:49:02 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:49:02 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:49:03 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:49:03 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:49:03 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:49:03 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:49:04 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:49:04 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:49:04 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:49:04 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:49:04 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-02-15 13:49:05 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-02-15 13:49:05 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-02-15 13:49:05 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-02-15 13:49:05 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-02-15 13:49:05 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-02-15 13:49:05 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-02-15 13:49:07 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-02-15 13:49:07 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-02-15 13:49:08 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-02-15 13:49:08 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-02-15 13:49:08 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-02-15 13:49:08 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-02-15 13:49:10 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-02-15 13:49:10 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-02-15 13:49:10 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-02-15 13:49:10 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-02-15 13:49:10 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-02-15 13:49:10 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-02-15 13:49:10 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-02-15 13:49:10 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-02-15 13:49:11 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-02-15 13:49:11 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-02-15 13:49:11 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-02-15 13:49:11 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-02-15 13:49:12 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-02-15 13:49:12 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-02-15 13:49:13 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-02-15 13:49:13 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-02-15 13:49:14 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-02-15 13:49:14 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-02-15 13:49:14 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-02-15 13:49:14 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-02-15 13:49:15 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-02-15 13:49:15 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-02-15 13:49:15 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-02-15 13:49:15 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-02-15 13:49:15 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-02-15 13:49:15 - DEBUG UnitTestFramework: '#run: 'basic''

2017-02-15 13:49:15 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-02-15 13:49:15 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-02-15 13:49:15 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-02-15 13:49:15 - DEBUG UnitTestFramework: '#setup: 'another''

2017-02-15 13:49:16 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-02-15 13:49:16 - DEBUG UnitTestFramework: '#run: 'another''

2017-02-15 13:49:16 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-02-15 13:49:16 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-02-15 13:49:16 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-02-15 13:49:16 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-02-15 13:49:17 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-02-15 13:49:17 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-02-15 13:49:18 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-02-15 13:49:18 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-02-15 13:49:18 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-02-15 13:49:18 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-02-15 13:49:19 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-02-15 13:49:19 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-02-15 13:49:19 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-02-15 13:49:19 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-02-15 13:49:19 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-02-15 13:49:19 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-02-15 13:49:20 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-02-15 13:49:20 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-02-15 13:49:20 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-02-15 13:49:20 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-02-15 13:49:20 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-02-15 13:49:20 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:49:20 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:49:21 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:49:21 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:49:22 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:49:22 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:49:24 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:49:24 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:49:24 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:49:24 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:49:24 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:49:24 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:49:24 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:49:24 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:49:25 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:49:26 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:49:26 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:49:27 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:49:27 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:49:27 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:49:27 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-02-15 13:49:28 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-02-15 13:49:28 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-02-15 13:49:30 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-02-15 13:49:30 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-02-15 13:49:31 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-02-15 13:49:31 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-02-15 13:49:31 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-02-15 13:49:31 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-02-15 13:49:51 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '721b9a88-55c2-40ad-bb67-aa037bec6e4a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 13:49:51 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-02-15 13:49:53 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '2a03ab9a-d20f-440f-9666-a83a5259e25f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 13:49:53 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-15 13:51:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '315a6e0c-a841-4f4a-9561-698da6c98a07', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 13:51:18 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-15 13:51:18 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-02-15 13:51:18 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-02-15 13:51:18 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-15 13:51:19 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-15 13:51:19 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-15 13:51:19 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-15 13:51:19 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-15 13:51:19 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-15 13:51:19 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-15 13:51:19 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-15 13:51:19 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-15 13:51:19 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-15 13:51:19 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:51:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-15 13:51:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-15 13:51:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:51:20 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:51:20 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:51:20 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:51:20 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:51:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:51:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:51:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:51:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:51:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:51:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-02-15 13:51:21 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-02-15 13:51:22 - DEBUG UnitTestFramework: '#run: 'basic''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup: 'another''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run: 'another''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-02-15 13:51:23 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:51:24 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:51:24 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:51:25 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:51:25 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:51:25 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-02-15 13:51:25 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:51:25 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:51:25 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:51:26 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:51:26 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:51:27 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 13:51:27 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:51:27 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:51:27 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:51:27 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:51:27 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:51:27 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 13:51:27 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:51:27 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:51:27 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:51:28 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:51:28 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:51:28 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 13:51:28 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:51:28 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:51:28 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:51:29 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:51:29 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:51:29 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 13:51:29 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:51:29 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:51:29 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:51:29 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:51:29 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:51:30 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 13:51:30 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-02-15 13:51:30 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-02-15 13:51:30 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-02-15 13:51:32 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-02-15 13:51:32 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-02-15 13:51:33 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-02-15 13:51:33 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-02-15 13:51:33 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-02-15 13:51:33 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-02-15 13:51:51 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-02-15 13:51:51 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-02-15 13:51:52 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-02-15 13:51:52 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-02-15 13:51:52 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-02-15 13:51:52 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-02-15 13:52:03 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-02-15 13:52:03 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-02-15 13:52:04 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-02-15 13:52:04 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 13:52:04 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 13:52:04 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 13:52:12 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 13:52:12 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 13:52:13 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 13:52:13 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-02-15 13:52:13 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-02-15 13:52:13 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-02-15 13:52:13 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-02-15 13:52:13 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-02-15 13:52:13 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-02-15 13:52:13 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-02-15 13:52:13 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-02-15 13:52:13 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-02-15 13:52:13 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 13:52:13 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 13:52:13 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 13:52:14 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 13:52:14 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 13:52:14 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 13:52:14 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-02-15 13:52:14 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-02-15 13:52:14 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-02-15 13:52:23 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-02-15 13:52:23 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-02-15 13:52:24 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-02-15 13:52:24 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-15 13:52:24 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-15 13:52:24 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-15 13:52:31 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-15 13:52:31 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-15 13:52:31 - ERROR TestServerProcess: 'uncaught promise rejection, error: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'', stack: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_1041482372a8f404/test/TestServer/utils/asserts.js:69:3)
    at UnitTestFramework.unbindSync (/home/pi/Test/server_1041482372a8f404/test/TestServer/UnitTestFramework.js:233:11)
    at /home/pi/Test/server_1041482372a8f404/test/TestServer/UnitTestFramework.js:100:10
    at PassThroughHandlerContext.finallyHandler (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/finally.js:55:23)
    at PassThroughHandlerContext.tryCatcher (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/promise.js:510:31)
    at Promise._settlePromise (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/promise.js:567:18)
    at Promise._settlePromise0 (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Promise._fulfill (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/promise.js:636:18)
    at PromiseArray._resolve (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/promise_array.js:125:19)
    at PromiseArray._promiseFulfilled (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/promise_array.js:143:14)
    at Promise._settlePromise (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/promise.js:572:26)
    at Promise._settlePromise0 (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Async._drainQueue (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/home/pi/Test/server_1041482372a8f404/test/TestServer/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:917:13)''

2017-02-15 13:52:31 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-mini-mfts' disconnected, reason: 'undefined''

2017-02-15 13:52:31 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-02-15 13:52:31 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-6-2' disconnected, reason: 'undefined''

2017-02-15 13:52:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-02-15 13:52:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-15 13:52:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
15/2/2017@14:44:52 Getting the list of iOS devices 
15/2/2017@14:44:53 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
15/2/2017@14:44:53 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
15/2/2017@14:44:53 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
15/2/2017@14:44:53 Deploying iOS test app 
15/2/2017@14:44:53 uninstalling the application 
15/2/2017@14:44:54 installing the application 
15/2/2017@15:08:12 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
15/2/2017@15:08:12 ios: child process exited with code null on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
15/2/2017@15:08:12 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
true

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
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1041482372a8f404_Clean_up_ThaliWifiInfrastructure_chapko/thali02_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1041482372a8f404_Clean_up_ThaliWifiInfrastructure_chapko/thali03_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1041482372a8f404_Clean_up_ThaliWifiInfrastructure_chapko/thali04_samsung-SM-G935F.md)


###iOS Logs
[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/1041482372a8f404_Clean_up_ThaliWifiInfrastructure_chapko/iOS_iphone-6-2.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1041482372a8f404_Clean_up_ThaliWifiInfrastructure_chapko/iOS_ipad-air-2-1.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/1041482372a8f404_Clean_up_ThaliWifiInfrastructure_chapko/iOS_ipad-mini-mfts.md)

[server](https://github.com/ThaliTester/TestResults/blob/1041482372a8f404_Clean_up_ThaliWifiInfrastructure_chapko/iOS_server.md)





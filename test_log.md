#### Test 106327918457c3ab Logs

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
2017-02-16 11:26:50 - INFO HttpServer: 'listening on *:3000'

2017-02-16 11:26:55 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-6-2', uuid: 'ed7bc5e0-7fe7-443d-b503-8c949484b2f6', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-16 11:26:55 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-6-2''

2017-02-16 11:26:57 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-6-2', uuid: 'ed7bc5e0-7fe7-443d-b503-8c949484b2f6', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-16 11:26:57 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-6-2', uuid: 'ed7bc5e0-7fe7-443d-b503-8c949484b2f6', platformName: 'ios''

2017-02-16 11:26:58 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'f01b1155-cbee-4907-bde3-a92c211a1d6e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-16 11:26:58 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-02-16 11:26:59 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: 'b0e858e3-5924-42d0-b67a-00ab8b5943ac', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-16 11:26:59 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-mini-mfts''

2017-02-16 11:26:59 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-02-16 11:26:59 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-02-16 11:26:59 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-16 11:27:00 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'f01b1155-cbee-4907-bde3-a92c211a1d6e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-16 11:27:00 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: 'f01b1155-cbee-4907-bde3-a92c211a1d6e', platformName: 'ios''

2017-02-16 11:27:01 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-16 11:27:01 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-16 11:27:01 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: 'b0e858e3-5924-42d0-b67a-00ab8b5943ac', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-16 11:27:01 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-mini-mfts', uuid: 'b0e858e3-5924-42d0-b67a-00ab8b5943ac', platformName: 'ios''

2017-02-16 11:27:01 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-16 11:27:01 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-16 11:27:02 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-16 11:27:02 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-16 11:27:03 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-16 11:27:03 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-16 11:27:03 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-16 11:27:03 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-16 11:27:03 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-16 11:27:03 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-16 11:27:04 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-16 11:27:04 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:27:04 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:27:04 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:27:05 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:27:05 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:27:05 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:27:05 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:27:06 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:27:06 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:27:06 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:27:06 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:27:07 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:27:07 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:27:08 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:27:08 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:27:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-16 11:27:08 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-16 11:27:09 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-16 11:27:09 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:27:09 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:27:10 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:27:10 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:27:10 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:27:10 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:27:10 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:27:10 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:27:10 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:27:10 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:27:10 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:27:11 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:27:11 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:27:11 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:27:11 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:27:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:27:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:27:12 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:27:12 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:27:12 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:27:15 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:27:15 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:27:16 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:27:16 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:27:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:27:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:27:17 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:27:17 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:27:17 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:27:17 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:27:17 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-02-16 11:27:18 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-02-16 11:27:18 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-02-16 11:27:18 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-02-16 11:27:18 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-02-16 11:27:19 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-02-16 11:27:19 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-02-16 11:27:19 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-02-16 11:27:19 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-02-16 11:27:20 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-02-16 11:27:20 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-02-16 11:27:21 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-02-16 11:27:21 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-02-16 11:27:22 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-02-16 11:27:22 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-02-16 11:27:23 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-02-16 11:27:23 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-02-16 11:27:24 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-02-16 11:27:24 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-02-16 11:27:26 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-02-16 11:27:26 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-02-16 11:27:30 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-02-16 11:27:30 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-02-16 11:27:31 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-02-16 11:27:31 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-02-16 11:27:31 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-02-16 11:27:31 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-02-16 11:27:34 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-02-16 11:27:34 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-02-16 11:27:34 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-02-16 11:27:34 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-02-16 11:27:34 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-02-16 11:27:34 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-02-16 11:27:42 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-02-16 11:27:42 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-02-16 11:27:43 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-02-16 11:27:43 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-02-16 11:27:43 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-02-16 11:27:43 - DEBUG UnitTestFramework: '#run: 'basic''

2017-02-16 11:27:44 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-02-16 11:27:44 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-02-16 11:27:45 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-02-16 11:27:45 - DEBUG UnitTestFramework: '#setup: 'another''

2017-02-16 11:27:45 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-02-16 11:27:45 - DEBUG UnitTestFramework: '#run: 'another''

2017-02-16 11:27:46 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-02-16 11:27:46 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-02-16 11:27:46 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-02-16 11:27:46 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-02-16 11:27:47 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-02-16 11:27:47 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-02-16 11:27:53 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-02-16 11:27:53 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-02-16 11:27:56 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-02-16 11:27:56 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-02-16 11:27:56 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-02-16 11:27:56 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-02-16 11:27:57 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-02-16 11:27:57 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-02-16 11:27:57 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-02-16 11:27:57 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-02-16 11:27:57 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-02-16 11:27:57 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-02-16 11:27:57 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-02-16 11:27:57 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-02-16 11:27:57 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-02-16 11:27:57 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-02-16 11:27:57 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-02-16 11:27:57 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-02-16 11:27:57 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-02-16 11:27:58 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-02-16 11:27:58 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-02-16 11:27:58 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-02-16 11:27:58 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-02-16 11:27:58 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-02-16 11:27:58 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-02-16 11:27:58 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-02-16 11:27:58 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-02-16 11:27:58 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:27:59 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:27:59 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:27:59 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:27:59 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:28:00 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:28:00 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:28:00 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:28:00 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:28:00 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:28:00 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:28:00 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:28:00 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:28:01 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'e8b6afc8-fe41-4501-b229-611d50ddcb04', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-16 11:28:01 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-16 11:28:01 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:28:01 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:28:01 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:28:01 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:28:01 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:28:01 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:28:02 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:28:02 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:28:02 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:28:02 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:28:02 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:28:02 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:28:03 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:28:03 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:28:03 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:28:03 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:28:04 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:28:04 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:28:04 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:28:04 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:28:05 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:28:05 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:28:05 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:28:05 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-02-16 11:28:05 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-02-16 11:28:05 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-02-16 11:28:07 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-02-16 11:28:07 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-02-16 11:28:07 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-02-16 11:28:07 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-02-16 11:28:07 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-02-16 11:28:07 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-02-16 11:28:13 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'f1d4d036-76ae-43b4-bcb7-2fc63ee81110', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-16 11:28:13 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-02-16 11:30:19 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '1c0b895f-9881-4046-80ea-fadfb68c75aa', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-16 11:30:19 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-16 11:30:19 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-02-16 11:30:19 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-02-16 11:30:19 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-16 11:30:20 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-16 11:30:20 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-16 11:30:21 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-16 11:30:21 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-16 11:30:21 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-16 11:30:21 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-16 11:30:21 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-16 11:30:21 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-16 11:30:21 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-16 11:30:21 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:30:22 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:30:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-02-16 11:30:23 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-02-16 11:30:24 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-02-16 11:30:25 - DEBUG UnitTestFramework: '#run: 'basic''

2017-02-16 11:30:32 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-02-16 11:30:32 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#setup: 'another''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#run: 'another''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-02-16 11:30:33 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-02-16 11:30:34 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-02-16 11:30:34 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:30:34 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:30:34 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:30:35 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:30:35 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:30:35 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-02-16 11:30:35 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:30:35 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:30:35 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:30:36 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:30:36 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:30:37 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-16 11:30:37 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:30:37 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:30:37 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:30:37 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:30:37 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:30:37 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-16 11:30:37 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:30:37 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:30:37 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:30:38 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:30:38 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:30:38 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-16 11:30:38 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:30:38 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:30:38 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-02-16 11:30:39 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-02-16 11:30:41 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-02-16 11:30:41 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-02-16 11:30:42 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-02-16 11:30:42 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-02-16 11:30:42 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-02-16 11:30:42 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-02-16 11:30:53 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-02-16 11:30:53 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-02-16 11:30:54 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-02-16 11:30:54 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-02-16 11:30:54 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-02-16 11:30:54 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-02-16 11:31:07 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-16 11:31:07 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-16 11:31:07 - ERROR TestServerProcess: 'uncaught promise rejection, error: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'', stack: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_106327918457c3ab/test/TestServer/utils/asserts.js:69:3)
    at UnitTestFramework.unbindSync (/home/pi/Test/server_106327918457c3ab/test/TestServer/UnitTestFramework.js:233:11)
    at /home/pi/Test/server_106327918457c3ab/test/TestServer/UnitTestFramework.js:100:10
    at PassThroughHandlerContext.finallyHandler (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/finally.js:55:23)
    at PassThroughHandlerContext.tryCatcher (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/promise.js:510:31)
    at Promise._settlePromise (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/promise.js:567:18)
    at Promise._settlePromise0 (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Promise._fulfill (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/promise.js:636:18)
    at PromiseArray._resolve (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/promise_array.js:125:19)
    at PromiseArray._promiseFulfilled (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/promise_array.js:143:14)
    at Promise._settlePromise (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/promise.js:572:26)
    at Promise._settlePromise0 (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Async._drainQueue (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/home/pi/Test/server_106327918457c3ab/test/TestServer/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:917:13)''

2017-02-16 11:31:07 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-6-2' disconnected, reason: 'undefined''

2017-02-16 11:31:07 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-02-16 11:31:07 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-mini-mfts' disconnected, reason: 'undefined''

2017-02-16 11:31:07 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-16 11:31:07 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-02-16 11:31:07 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
16/2/2017@12:23:16 Getting the list of iOS devices 
16/2/2017@12:23:17 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
16/2/2017@12:23:17 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
16/2/2017@12:23:17 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
16/2/2017@12:23:17 Deploying iOS test app 
16/2/2017@12:23:17 uninstalling the application 
16/2/2017@12:23:18 installing the application 
16/2/2017@12:46:36 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
16/2/2017@12:46:36 ios: child process exited with code null on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
16/2/2017@12:46:36 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/106327918457c3ab_Fix_null_pointer_exception__evabishchevich/thali02_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/106327918457c3ab_Fix_null_pointer_exception__evabishchevich/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/106327918457c3ab_Fix_null_pointer_exception__evabishchevich/thali04_samsung-SM-G935F.md)


###iOS Logs
[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/106327918457c3ab_Fix_null_pointer_exception__evabishchevich/iOS_iphone-6-2.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/106327918457c3ab_Fix_null_pointer_exception__evabishchevich/iOS_ipad-air-2-1.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/106327918457c3ab_Fix_null_pointer_exception__evabishchevich/iOS_ipad-mini-mfts.md)

[server](https://github.com/ThaliTester/TestResults/blob/106327918457c3ab_Fix_null_pointer_exception__evabishchevich/iOS_server.md)





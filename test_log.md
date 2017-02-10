#### Test 102271039c997935 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 2 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2017-02-10 10:44:22 - INFO HttpServer: 'listening on *:3000'

2017-02-10 10:44:27 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c71c6b97-8124-4558-bc4d-de16d11b841b', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:44:27 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-02-10 10:44:29 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c71c6b97-8124-4558-bc4d-de16d11b841b', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:44:29 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'c71c6b97-8124-4558-bc4d-de16d11b841b', platformName: 'ios''

2017-02-10 10:44:29 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '791b756f-562d-4207-ac15-e99af8846f83', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:44:29 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-02-10 10:44:29 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'e06a2b94-287f-4fff-be57-5f0cb800b6b5', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:44:29 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-02-10 10:44:30 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: 'e0991c09-7b73-40a6-8a82-63a2997d0447', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:44:30 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-mini-mfts''

2017-02-10 10:44:30 - INFO TestFramework: 'all required 4 devices are present for platformName: 'ios''

2017-02-10 10:44:30 - DEBUG UnitTestFramework: 'starting unit tests on 4 devices, platformName: 'ios''

2017-02-10 10:44:30 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-10 10:44:31 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '791b756f-562d-4207-ac15-e99af8846f83', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:44:31 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '791b756f-562d-4207-ac15-e99af8846f83', platformName: 'ios''

2017-02-10 10:44:31 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'e06a2b94-287f-4fff-be57-5f0cb800b6b5', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:44:31 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: 'e06a2b94-287f-4fff-be57-5f0cb800b6b5', platformName: 'ios''

2017-02-10 10:44:32 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: 'e0991c09-7b73-40a6-8a82-63a2997d0447', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:44:32 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-mini-mfts', uuid: 'e0991c09-7b73-40a6-8a82-63a2997d0447', platformName: 'ios''

2017-02-10 10:44:52 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-10 10:44:52 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-10 10:44:52 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-10 10:44:52 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-10 10:44:53 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-10 10:44:53 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-10 10:44:55 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-10 10:44:55 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-10 10:44:55 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-10 10:44:55 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-10 10:44:56 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-10 10:44:56 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-10 10:44:57 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-10 10:44:57 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:44:59 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:44:59 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:45:00 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:45:00 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:45:06 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:45:06 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:45:07 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:45:07 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:45:07 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:45:07 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:45:09 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:45:09 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:45:09 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:45:09 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:45:12 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:45:12 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:45:13 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:45:13 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:45:13 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:45:13 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:45:14 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:45:14 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:45:15 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:45:15 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:45:16 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:45:16 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:45:18 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:45:18 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:45:19 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:45:19 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:45:19 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:45:19 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:45:21 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:45:21 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:45:23 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:45:23 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-02-10 10:45:24 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-02-10 10:45:24 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-02-10 10:45:25 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-02-10 10:45:25 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-02-10 10:45:26 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-02-10 10:45:26 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-02-10 10:45:26 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-02-10 10:45:26 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-02-10 10:45:26 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-02-10 10:45:26 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-02-10 10:45:26 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-02-10 10:45:26 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-02-10 10:45:26 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-02-10 10:45:26 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-02-10 10:45:27 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-02-10 10:45:27 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-02-10 10:45:27 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-02-10 10:45:27 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-02-10 10:45:28 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-02-10 10:45:28 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-02-10 10:45:29 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-02-10 10:45:29 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-02-10 10:45:30 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-02-10 10:45:30 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-02-10 10:45:30 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '92a286b5-a91f-4ddf-b0c3-929725a2ed92', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:45:30 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-10 10:45:31 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-02-10 10:45:31 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-02-10 10:45:31 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-02-10 10:45:31 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-02-10 10:45:31 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-02-10 10:45:31 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-02-10 10:45:31 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-02-10 10:45:31 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-02-10 10:45:31 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-02-10 10:45:31 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-02-10 10:45:32 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-02-10 10:45:32 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-02-10 10:45:33 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-02-10 10:45:33 - DEBUG UnitTestFramework: '#run: 'basic''

2017-02-10 10:45:36 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-02-10 10:45:36 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-02-10 10:45:37 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-02-10 10:45:37 - DEBUG UnitTestFramework: '#setup: 'another''

2017-02-10 10:45:38 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-02-10 10:45:38 - DEBUG UnitTestFramework: '#run: 'another''

2017-02-10 10:45:38 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-02-10 10:45:38 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-02-10 10:45:39 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-02-10 10:45:39 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-02-10 10:45:39 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-02-10 10:45:39 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-02-10 10:45:40 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-02-10 10:45:40 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-02-10 10:45:40 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-02-10 10:45:40 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-02-10 10:45:41 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-02-10 10:45:41 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-02-10 10:45:41 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-02-10 10:45:41 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-02-10 10:45:41 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-02-10 10:45:43 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-02-10 10:45:43 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-02-10 10:45:43 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-02-10 10:45:43 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-02-10 10:45:43 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-02-10 10:45:44 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-02-10 10:45:44 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-02-10 10:45:44 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-02-10 10:45:45 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-02-10 10:45:45 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:45:45 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:45:45 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:45:45 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:45:45 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:45:46 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:45:46 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:45:49 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '2512b713-64e8-4894-9dd5-c48dcc46d9ce', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:45:49 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-10 10:45:49 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:45:49 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:45:50 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:45:50 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:45:50 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:45:50 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:45:50 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:45:50 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:45:50 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:45:50 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:45:50 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:45:50 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:45:51 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:45:51 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:45:51 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:45:51 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:45:52 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:45:52 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:45:58 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:45:58 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:46:00 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:46:00 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:46:01 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:46:01 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:46:01 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:46:01 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:46:03 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:46:03 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:46:04 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:46:04 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-02-10 10:46:05 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-02-10 10:46:05 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-02-10 10:46:06 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-02-10 10:46:06 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-02-10 10:46:08 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-02-10 10:46:08 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-02-10 10:46:12 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-02-10 10:46:12 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-02-10 10:47:41 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'a1eaa120-4fa8-481e-a0e6-ff47ec30e8a7', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-10 10:47:41 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-02-10 10:47:41 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-02-10 10:47:41 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-02-10 10:47:41 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-10 10:47:42 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-10 10:47:42 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-10 10:47:43 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-10 10:47:43 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-10 10:47:43 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-10 10:47:43 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-10 10:47:43 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-10 10:47:43 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-10 10:47:43 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-10 10:47:43 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:47:44 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:47:45 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:47:47 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:47:47 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:47:47 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-10 10:47:47 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:47:47 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:47:47 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:47:48 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:47:48 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:47:48 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-10 10:47:48 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-02-10 10:47:48 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-02-10 10:47:48 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-02-10 10:47:49 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#run: 'basic''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#setup: 'another''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-02-10 10:47:50 - DEBUG UnitTestFramework: '#run: 'another''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-02-10 10:47:51 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-02-10 10:47:52 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-02-10 10:47:52 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:47:52 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:47:52 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:47:57 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:47:57 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:47:57 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-02-10 10:47:57 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:47:57 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:47:57 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:47:58 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:47:58 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:47:59 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-10 10:47:59 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:47:59 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:47:59 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:48:00 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:48:00 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:48:00 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-10 10:48:00 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:48:00 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:48:00 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:48:01 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:48:01 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:48:01 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-10 10:48:01 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:48:01 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:48:01 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:48:02 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:48:02 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:48:02 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-10 10:48:02 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:48:02 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:48:02 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:48:02 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:48:02 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:48:03 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-10 10:48:03 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-02-10 10:48:03 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-02-10 10:48:03 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-02-10 10:48:05 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-02-10 10:48:05 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-02-10 10:48:06 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-02-10 10:48:06 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-02-10 10:48:06 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-02-10 10:48:06 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-02-10 10:48:16 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-02-10 10:48:16 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-02-10 10:48:17 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-02-10 10:48:17 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-02-10 10:48:18 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-02-10 10:48:18 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-02-10 10:48:44 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-02-10 10:48:44 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-02-10 10:48:45 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-02-10 10:48:45 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-10 10:48:45 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-10 10:48:45 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-10 10:48:53 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-10 10:48:53 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-10 10:48:54 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-10 10:48:54 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-02-10 10:48:54 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-02-10 10:48:54 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-02-10 10:48:54 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-02-10 10:48:54 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-02-10 10:48:54 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-02-10 10:48:54 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-02-10 10:48:54 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-02-10 10:48:55 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-02-10 10:48:55 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-02-10 10:48:55 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-02-10 10:48:55 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-02-10 10:48:55 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-02-10 10:48:55 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-02-10 10:48:55 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-02-10 10:48:55 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-02-10 10:48:55 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-02-10 10:48:55 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-02-10 10:49:03 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-02-10 10:49:03 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-02-10 10:49:04 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-02-10 10:49:04 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-10 10:49:05 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-10 10:49:05 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-10 10:49:12 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-10 10:49:12 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-10 10:49:12 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-10 10:49:12 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-10 10:49:14 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-10 10:49:14 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-02-10 10:49:15 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-02-10 10:49:15 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-02-10 10:49:15 - ERROR TestServerProcess: 'uncaught promise rejection, error: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'', stack: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_102271039c997935/test/TestServer/utils/asserts.js:69:3)
    at UnitTestFramework.unbindSync (/home/pi/Test/server_102271039c997935/test/TestServer/UnitTestFramework.js:233:11)
    at /home/pi/Test/server_102271039c997935/test/TestServer/UnitTestFramework.js:100:10
    at PassThroughHandlerContext.finallyHandler (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/finally.js:55:23)
    at PassThroughHandlerContext.tryCatcher (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/promise.js:510:31)
    at Promise._settlePromise (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/promise.js:567:18)
    at Promise._settlePromise0 (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Promise._fulfill (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/promise.js:636:18)
    at PromiseArray._resolve (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/promise_array.js:125:19)
    at PromiseArray._promiseFulfilled (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/promise_array.js:143:14)
    at Promise._settlePromise (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/promise.js:572:26)
    at Promise._settlePromise0 (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Async._drainQueue (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/home/pi/Test/server_102271039c997935/test/TestServer/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:917:13)''

2017-02-10 10:49:15 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-02-10 10:49:15 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-02-10 10:49:15 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-02-10 10:49:15 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-mini-mfts' disconnected, reason: 'undefined''

2017-02-10 10:49:15 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-10 10:49:15 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-10 10:49:15 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

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
10/2/2017@11:40:30 Getting the list of iOS devices 
10/2/2017@11:40:31 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
10/2/2017@11:40:31 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
10/2/2017@11:40:31 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
10/2/2017@11:40:31 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
10/2/2017@11:40:31 Deploying iOS test app 
10/2/2017@11:40:31 uninstalling the application 
10/2/2017@11:40:33 installing the application 
10/2/2017@12:03:50 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
10/2/2017@12:03:50 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
10/2/2017@12:03:50 ios: child process exited with code null on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
10/2/2017@12:03:50 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/102271039c997935_Update_BtLib_version_evabishchevich/thali02_samsung-SM-G930F.md)

####Node name: thali03
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

Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/102271039c997935_Update_BtLib_version_evabishchevich/thali03_samsung-SM-G930F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/102271039c997935_Update_BtLib_version_evabishchevich/thali04_samsung-SM-G935F.md)


###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/102271039c997935_Update_BtLib_version_evabishchevich/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/102271039c997935_Update_BtLib_version_evabishchevich/iOS_iphone-5s-mfts.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/102271039c997935_Update_BtLib_version_evabishchevich/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/102271039c997935_Update_BtLib_version_evabishchevich/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/102271039c997935_Update_BtLib_version_evabishchevich/iOS_server.md)





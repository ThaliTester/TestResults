#### Test 96918947a106de9 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 2 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2017-02-03 13:20:02 - INFO HttpServer: 'listening on *:3000'

2017-02-03 13:20:06 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: '00a37b3b-fe7b-4240-b435-54e444599e1d', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-03 13:20:06 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-mini-mfts''

2017-02-03 13:20:11 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '82fe8fab-8277-4e0c-af31-7adc5318a4bc', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-03 13:20:11 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-02-03 13:20:12 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-6-2', uuid: '671cc835-5ea8-44e5-8452-53c4ec38eb55', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-03 13:20:12 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-6-2''

2017-02-03 13:20:21 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '3a5b6f73-b5ca-486f-930c-6c85c0c18123', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-03 13:20:21 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-02-03 13:20:31 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '80c95cae-258c-4377-a90a-183aa81ded38', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-03 13:20:31 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-02-03 13:20:31 - INFO TestFramework: 'all required 5 devices are present for platformName: 'ios''

2017-02-03 13:20:32 - DEBUG UnitTestFramework: 'starting unit tests on 5 devices, platformName: 'ios''

2017-02-03 13:20:32 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-03 13:20:34 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-03 13:20:34 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-03 13:20:36 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-03 13:20:36 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-03 13:20:37 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-03 13:20:37 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-03 13:20:40 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-03 13:20:40 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-03 13:20:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-03 13:20:41 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-03 13:20:42 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-03 13:20:42 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-03 13:20:43 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-03 13:20:43 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:20:45 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:20:45 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:20:46 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:20:46 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:20:47 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:20:47 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:20:48 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:20:48 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:20:49 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:20:49 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:20:53 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:20:53 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:21:41 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:21:41 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:21:43 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '67706b52-0e95-4d8d-8c3a-a9426eb8bbf4', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-03 13:21:43 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-03 13:21:56 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'a979db18-e9a2-49a2-8520-11961b123ccf', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-03 13:21:56 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-03 13:23:11 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'f445db48-ee9e-49ac-855b-b9b78666ead7', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-03 13:23:11 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-02-03 13:23:11 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-02-03 13:23:11 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-02-03 13:23:11 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-03 13:23:11 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-6-2', uuid: '671cc835-5ea8-44e5-8452-53c4ec38eb55', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-03 13:23:11 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-6-2', uuid: '671cc835-5ea8-44e5-8452-53c4ec38eb55', platformName: 'ios''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-03 13:23:12 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:23:13 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:23:13 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:23:13 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-6-2', uuid: '671cc835-5ea8-44e5-8452-53c4ec38eb55', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-03 13:23:13 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-6-2', uuid: '671cc835-5ea8-44e5-8452-53c4ec38eb55', platformName: 'ios''

2017-02-03 13:23:13 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:23:13 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:23:14 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-03 13:23:14 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:23:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:23:14 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:23:14 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:23:14 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:23:17 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:23:17 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:23:17 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-03 13:23:17 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:23:18 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:23:18 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:23:19 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:23:19 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:23:19 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-03 13:23:19 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-03 13:23:19 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-03 13:23:19 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-03 13:23:20 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-03 13:23:20 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-03 13:23:20 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-03 13:23:20 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-03 13:23:21 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-03 13:23:21 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-03 13:23:24 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-03 13:23:24 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-03 13:23:24 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-03 13:23:24 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-03 13:23:25 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-03 13:23:25 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-03 13:23:26 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-03 13:23:26 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-02-03 13:23:28 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run: 'basic''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#setup: 'another''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run: 'another''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-02-03 13:23:29 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-02-03 13:23:30 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-02-03 13:23:31 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-6-2' disconnected, reason: 'ping timeout''

2017-02-03 13:23:33 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''
2017-02-03 13:23:33 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-02-03 13:23:33 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-02-03 13:23:33 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-03 13:23:33 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-03 13:23:33 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-03 13:23:34 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-03 13:23:34 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-03 13:23:35 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''
2017-02-03 13:23:35 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-03 13:23:35 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-03 13:23:35 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-03 13:23:35 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-03 13:23:35 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-03 13:23:35 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-03 13:23:35 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-03 13:23:35 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-03 13:23:35 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-03 13:23:36 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-03 13:23:36 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-03 13:23:36 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-03 13:23:36 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-03 13:23:36 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-03 13:23:36 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-03 13:23:37 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-03 13:23:37 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-03 13:23:37 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-03 13:23:37 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-03 13:23:37 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-03 13:23:37 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-03 13:23:37 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-03 13:23:37 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-03 13:23:38 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-03 13:23:38 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-02-03 13:23:38 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-02-03 13:23:38 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-02-03 13:23:40 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-02-03 13:23:40 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-02-03 13:23:42 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-02-03 13:23:42 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-02-03 13:23:43 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-02-03 13:23:43 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-02-03 13:24:09 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-02-03 13:24:09 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-02-03 13:24:10 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-02-03 13:24:10 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-02-03 13:24:11 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-02-03 13:24:11 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-02-03 13:24:14 - ERROR UnitTestFramework: '#run failed: 'Call of onCheckpointReached handler on a single db change', error: 'TimeoutError: timeout exceeded, event: 'teardown_Call of onCheckpointReached handler on a single db change_finished', test: 'Call of onCheckpointReached handler on a single db change'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_Call of onCheckpointReached handler on a single db change_finished', test: 'Call of onCheckpointReached handler on a single db change'
    at afterTimeout (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-03 13:24:14 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'teardown_Call of onCheckpointReached handler on a single db change_finished', test: 'Call of onCheckpointReached handler on a single db change'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_Call of onCheckpointReached handler on a single db change_finished', test: 'Call of onCheckpointReached handler on a single db change'
    at afterTimeout (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-03 13:24:41 - ERROR TestServerProcess: 'uncaught promise rejection, error: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'', stack: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_96918947a106de9/test/TestServer/utils/asserts.js:69:3)
    at UnitTestFramework.unbindSync (/home/pi/Test/server_96918947a106de9/test/TestServer/UnitTestFramework.js:233:11)
    at /home/pi/Test/server_96918947a106de9/test/TestServer/UnitTestFramework.js:100:10
    at PassThroughHandlerContext.finallyHandler (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/finally.js:55:23)
    at PassThroughHandlerContext.tryCatcher (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/promise.js:510:31)
    at Promise._settlePromise (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/promise.js:567:18)
    at Promise._settlePromise0 (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Promise._fulfill (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/promise.js:636:18)
    at PromiseArray._resolve (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/promise_array.js:125:19)
    at PromiseArray._promiseFulfilled (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/promise_array.js:143:14)
    at Promise._settlePromise (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/promise.js:572:26)
    at Promise._settlePromise0 (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Async._drainQueue (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/home/pi/Test/server_96918947a106de9/test/TestServer/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:917:13)''

2017-02-03 13:24:41 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-mini-mfts' disconnected, reason: 'undefined''

2017-02-03 13:24:41 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-02-03 13:24:41 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-02-03 13:24:41 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-02-03 13:24:41 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-03 13:24:41 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-03 13:24:41 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-6-2' disconnected, reason: 'undefined''

2017-02-03 13:24:41 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

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
3/2/2017@14:16:53 Getting the list of iOS devices 
3/2/2017@14:16:54 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
3/2/2017@14:16:54 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
3/2/2017@14:16:54 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
3/2/2017@14:16:54 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
3/2/2017@14:16:54 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
3/2/2017@14:16:54 Deploying iOS test app 
3/2/2017@14:16:54 uninstalling the application 
3/2/2017@14:16:55 installing the application 
3/2/2017@14:40:13 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
3/2/2017@14:40:13 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
3/2/2017@14:40:13 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
3/2/2017@14:40:13 ios: child process exited with code null on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/96918947a106de9_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/thali02_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/96918947a106de9_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/96918947a106de9_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/thali04_samsung-SM-G935F.md)


###iOS Logs
[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/96918947a106de9_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_iphone-6-2.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/96918947a106de9_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/96918947a106de9_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_iphone-5s-mfts.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/96918947a106de9_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/96918947a106de9_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/96918947a106de9_Implemented_iOS_native-mode_functionality__900___1585___1611_squid48/iOS_server.md)





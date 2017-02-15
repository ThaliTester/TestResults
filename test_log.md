#### Test 1062586553e7ecec Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
URL:  [ 'nodes', '3' ]
URL:  [ 'ios', '4' ]
URL:  [ 'droid', '1' ]
URL:  [ 'droid', '1' ]
URL:  [ 'droid', '1' ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2017-02-15 12:08:55 - INFO HttpServer: 'listening on *:3000'

2017-02-15 12:08:55 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '567e59b9-4edb-4435-afc0-46159bd499cf', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 12:08:55 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-02-15 12:08:57 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '567e59b9-4edb-4435-afc0-46159bd499cf', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 12:08:57 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: '567e59b9-4edb-4435-afc0-46159bd499cf', platformName: 'ios''

2017-02-15 12:08:58 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: 'a76b69a2-8591-4414-845c-8aa348b67ef7', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 12:08:58 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-mini-mfts''

2017-02-15 12:09:00 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '44ccfd3b-bd03-4520-975a-a42e662bc412', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2017-02-15 12:09:00 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Apple-iphone-5s-mfts''

2017-02-15 12:09:00 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'client namespace disconnect''

2017-02-15 12:09:01 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '4322562a-10b7-473f-acc8-b036ecf57188', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 12:09:01 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-02-15 12:09:03 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '4322562a-10b7-473f-acc8-b036ecf57188', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 12:09:03 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '4322562a-10b7-473f-acc8-b036ecf57188', platformName: 'ios''

2017-02-15 12:10:22 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '2c5287db-f413-4bb7-9556-e1f6c203e738', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 12:10:22 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-15 12:10:22 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '23610fa7-0a9a-48d2-bd1f-dafa20f7a400', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 12:10:22 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-15 12:12:03 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '9a6343c3-ee3b-497d-9c0b-d18fe950b7a7', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-15 12:12:03 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-02-15 12:12:03 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-02-15 12:12:03 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-02-15 12:12:03 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-15 12:12:04 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-15 12:12:04 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-15 12:12:04 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-15 12:12:04 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-15 12:12:04 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-15 12:12:04 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-15 12:12:04 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-15 12:12:04 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-15 12:12:04 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-15 12:12:04 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-15 12:12:05 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 12:12:06 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 12:12:06 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-02-15 12:12:07 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-02-15 12:12:08 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#run: 'basic''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#setup: 'another''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#run: 'another''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-02-15 12:12:09 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-02-15 12:12:10 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-02-15 12:12:12 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-02-15 12:12:12 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-02-15 12:12:12 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-02-15 12:12:12 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 12:12:12 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 12:12:12 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 12:12:13 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 12:12:13 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 12:12:15 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-15 12:12:15 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 12:12:15 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 12:12:15 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 12:12:16 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 12:12:16 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 12:12:16 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-15 12:12:16 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 12:12:16 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 12:12:16 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 12:12:17 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 12:12:17 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 12:12:17 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-15 12:12:17 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 12:12:17 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 12:12:17 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-02-15 12:12:18 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-02-15 12:12:21 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-02-15 12:12:21 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-02-15 12:12:22 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-02-15 12:12:22 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-02-15 12:12:22 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-02-15 12:12:22 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-02-15 12:12:28 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-02-15 12:12:28 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-02-15 12:12:29 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-02-15 12:12:29 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-02-15 12:12:29 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-02-15 12:12:29 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-02-15 12:12:40 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-02-15 12:12:40 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-02-15 12:12:42 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-02-15 12:12:42 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 12:12:42 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 12:12:42 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 12:12:49 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 12:12:49 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-02-15 12:12:50 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-02-15 12:12:50 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-02-15 12:12:50 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 12:12:50 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 12:12:51 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-02-15 12:12:51 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-02-15 12:12:51 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-02-15 12:12:51 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-02-15 12:13:00 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-02-15 12:13:00 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-02-15 12:13:00 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-02-15 12:13:00 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-15 12:13:01 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-15 12:13:01 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-15 12:13:11 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-15 12:13:11 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-15 12:13:12 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-02-15 12:13:12 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-02-15 12:13:13 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-02-15 12:13:13 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-02-15 12:13:48 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-02-15 12:13:48 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-02-15 12:13:49 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-02-15 12:13:49 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-02-15 12:13:49 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-02-15 12:13:49 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-02-15 12:13:55 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_1062586553e7ecec/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-15 12:13:55 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-02-15 12:13:55 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-mini-mfts' disconnected, reason: 'undefined''

2017-02-15 12:13:55 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-02-15 12:13:55 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-15 12:13:55 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-15 12:13:55 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

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
15/2/2017@13:05:20 Getting the list of iOS devices 
15/2/2017@13:05:21 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
15/2/2017@13:05:21 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
15/2/2017@13:05:21 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
15/2/2017@13:05:21 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
15/2/2017@13:05:21 Deploying iOS test app 
15/2/2017@13:05:21 uninstalling the application 
15/2/2017@13:05:22 installing the application 
15/2/2017@13:28:40 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
15/2/2017@13:28:40 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1062586553e7ecec_CI_iOS_sanity_check_czyzm/thali02_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1062586553e7ecec_CI_iOS_sanity_check_czyzm/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1062586553e7ecec_CI_iOS_sanity_check_czyzm/thali04_samsung-SM-G935F.md)


###iOS Logs
[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1062586553e7ecec_CI_iOS_sanity_check_czyzm/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1062586553e7ecec_CI_iOS_sanity_check_czyzm/iOS_ipad-air-2-1.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/1062586553e7ecec_CI_iOS_sanity_check_czyzm/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1062586553e7ecec_CI_iOS_sanity_check_czyzm/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/1062586553e7ecec_CI_iOS_sanity_check_czyzm/iOS_server.md)





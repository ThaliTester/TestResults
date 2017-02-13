#### Test 1041482374baf670 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2017-02-13 17:52:31 - INFO HttpServer: 'listening on *:3000'

2017-02-13 17:52:32 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '22726662-615f-45a3-9c95-3fc284b63413', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 17:52:32 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-02-13 17:52:35 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '175ed47e-e619-434a-929d-710af9b48f27', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 17:52:35 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-02-13 17:52:37 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: '35dadae6-fe0e-4f1c-93df-60403d4e228a', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 17:52:37 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-mini-mfts''

2017-02-13 17:52:37 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '175ed47e-e619-434a-929d-710af9b48f27', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 17:52:37 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '175ed47e-e619-434a-929d-710af9b48f27', platformName: 'ios''

2017-02-13 17:52:38 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '79a8a70f-00ad-4722-9ab1-adf4fa2afdcd', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2017-02-13 17:52:38 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Apple-iphone-5s-mfts''

2017-02-13 17:52:38 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'client namespace disconnect''

2017-02-13 17:52:39 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: '35dadae6-fe0e-4f1c-93df-60403d4e228a', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 17:52:39 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-mini-mfts', uuid: '35dadae6-fe0e-4f1c-93df-60403d4e228a', platformName: 'ios''

2017-02-13 17:53:54 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '4d04832f-5a38-4fed-b9ff-392ca5b19a0d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 17:53:54 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-13 17:54:12 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '8c9a875a-50c0-49f7-a86e-0c8056a838ae', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 17:54:12 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-02-13 17:55:36 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '70c226d3-e4b0-4a97-aceb-1439ce65517e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-13 17:55:36 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-13 17:55:36 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-02-13 17:55:36 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-02-13 17:55:36 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-13 17:55:37 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-13 17:55:37 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-02-13 17:55:37 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-02-13 17:55:37 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-02-13 17:55:37 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-02-13 17:55:37 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-02-13 17:55:37 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-02-13 17:55:37 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-02-13 17:55:37 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-02-13 17:55:37 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-13 17:55:38 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''
2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-13 17:55:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-02-13 17:55:39 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-02-13 17:55:40 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-02-13 17:55:42 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#run: 'basic''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#setup: 'another''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#run: 'another''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-02-13 17:55:43 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-02-13 17:55:44 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-02-13 17:55:45 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-02-13 17:55:45 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-02-13 17:55:45 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-02-13 17:55:45 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-02-13 17:55:46 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-02-13 17:55:46 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-02-13 17:55:46 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-02-13 17:55:46 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-13 17:55:46 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-13 17:55:46 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-13 17:55:47 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-13 17:55:47 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-13 17:55:48 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-02-13 17:55:48 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-13 17:55:48 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-13 17:55:48 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-13 17:55:48 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-13 17:55:48 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-13 17:55:48 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-02-13 17:55:48 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-13 17:55:48 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-13 17:55:48 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-13 17:55:49 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-13 17:55:49 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-13 17:55:49 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-02-13 17:55:49 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-13 17:55:49 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-13 17:55:49 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-13 17:55:50 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-13 17:55:50 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-13 17:55:50 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-02-13 17:55:50 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-13 17:55:50 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-13 17:55:50 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-13 17:55:50 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-13 17:55:50 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-13 17:55:51 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-02-13 17:55:51 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-02-13 17:55:51 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-02-13 17:55:51 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-02-13 17:55:53 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-02-13 17:55:53 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-02-13 17:55:54 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-02-13 17:55:54 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-02-13 17:55:54 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-02-13 17:55:54 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-02-13 17:56:04 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-02-13 17:56:04 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-02-13 17:56:07 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-02-13 17:56:07 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-02-13 17:56:07 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-02-13 17:56:07 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-02-13 17:57:31 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_1041482374baf670/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-13 17:57:31 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-02-13 17:57:31 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-02-13 17:57:31 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-mini-mfts' disconnected, reason: 'undefined''

2017-02-13 17:57:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-13 17:57:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-02-13 17:57:31 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
13/2/2017@18:49:00 Getting the list of iOS devices 
13/2/2017@18:49:01 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
13/2/2017@18:49:01 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
13/2/2017@18:49:01 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
13/2/2017@18:49:01 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
13/2/2017@18:49:01 Deploying iOS test app 
13/2/2017@18:49:01 uninstalling the application 
13/2/2017@18:49:02 installing the application 
13/2/2017@19:12:20 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
13/2/2017@19:12:20 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
13/2/2017@19:12:20 ios: child process exited with code null on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1041482374baf670_Clean_up_ThaliWifiInfrastructure_chapko/thali02_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1041482374baf670_Clean_up_ThaliWifiInfrastructure_chapko/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1041482374baf670_Clean_up_ThaliWifiInfrastructure_chapko/thali04_samsung-SM-G935F.md)


###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1041482374baf670_Clean_up_ThaliWifiInfrastructure_chapko/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1041482374baf670_Clean_up_ThaliWifiInfrastructure_chapko/iOS_iphone-5s-mfts.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/1041482374baf670_Clean_up_ThaliWifiInfrastructure_chapko/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1041482374baf670_Clean_up_ThaliWifiInfrastructure_chapko/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/1041482374baf670_Clean_up_ThaliWifiInfrastructure_chapko/iOS_server.md)





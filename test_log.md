#### Test 112800850f460826 Logs

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
2017-03-28 11:03:34 - INFO HttpServer: 'listening on *:3000'

2017-03-28 11:03:39 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '9baa6bf4-e095-4ea6-9e47-a214406b163a', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-28 11:03:39 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-03-28 11:04:05 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'efa292c9-7712-4c43-9da6-de232e67388e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-28 11:04:05 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-03-28 11:04:09 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'bac18d39-2d33-4f52-b6c0-35816250caa4', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-28 11:04:09 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-03-28 11:04:09 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-03-28 11:04:09 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-03-28 11:04:09 - DEBUG UnitTestFramework: 'scheduling tests'

2017-03-28 11:04:13 - DEBUG UnitTestFramework: 'tests scheduled'

2017-03-28 11:04:13 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-03-28 11:04:15 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-03-28 11:04:15 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-03-28 11:04:16 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-03-28 11:04:16 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-03-28 11:04:16 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-03-28 11:04:16 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-03-28 11:04:17 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-03-28 11:04:17 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-03-28 11:04:19 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-03-28 11:04:19 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-03-28 11:04:20 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-03-28 11:04:20 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-28 11:04:22 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-28 11:04:22 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-28 11:04:23 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-28 11:04:23 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-28 11:04:24 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-03-28 11:04:24 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-28 11:04:25 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-28 11:04:25 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-28 11:04:26 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-28 11:04:26 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-28 11:04:28 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-03-28 11:04:28 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-03-28 11:04:29 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-03-28 11:04:29 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-03-28 11:04:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-03-28 11:04:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-03-28 11:04:30 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-03-28 11:04:30 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-03-28 11:04:30 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-03-28 11:04:30 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-03-28 11:04:30 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-28 11:04:32 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-28 11:04:32 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-28 11:04:33 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-03-28 11:04:33 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-03-28 11:04:33 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-03-28 11:04:33 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-28 11:04:33 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-28 11:04:35 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-03-28 11:04:35 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-28 11:04:38 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-28 11:04:38 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-28 11:04:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-28 11:04:38 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-28 11:04:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-28 11:04:39 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-28 11:04:39 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-28 11:04:40 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-03-28 11:04:40 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-28 11:04:40 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-28 11:04:40 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-28 11:04:41 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-28 11:04:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-28 11:04:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-28 11:04:43 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-28 11:04:43 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-28 11:04:44 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-03-28 11:04:44 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-03-28 11:04:45 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-03-28 11:04:45 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-03-28 11:04:46 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-03-28 11:04:46 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-03-28 11:04:51 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-03-28 11:04:51 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-03-28 11:04:52 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-03-28 11:04:52 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-03-28 11:04:55 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-03-28 11:04:55 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-03-28 11:04:56 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-03-28 11:04:56 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-03-28 11:04:57 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-03-28 11:04:57 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-03-28 11:04:59 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-03-28 11:04:59 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-03-28 11:05:01 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-03-28 11:05:01 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-03-28 11:05:04 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-03-28 11:05:04 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-03-28 11:05:04 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-03-28 11:05:04 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-03-28 11:05:06 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-03-28 11:05:06 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-03-28 11:05:09 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-03-28 11:05:09 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-03-28 11:05:13 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-03-28 11:05:13 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-03-28 11:05:14 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-03-28 11:05:14 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-03-28 11:05:14 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-03-28 11:05:14 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-03-28 11:05:19 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-03-28 11:05:19 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-03-28 11:05:23 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-03-28 11:05:23 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-03-28 11:05:25 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-03-28 11:05:25 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-03-28 11:05:29 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-03-28 11:05:29 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-03-28 11:05:31 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-03-28 11:05:31 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-03-28 11:05:33 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-03-28 11:05:33 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-03-28 11:05:34 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-03-28 11:05:34 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-03-28 11:05:35 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-03-28 11:05:35 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-03-28 11:05:36 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-03-28 11:05:36 - DEBUG UnitTestFramework: '#run: 'basic''

2017-03-28 11:05:37 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-03-28 11:05:37 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-03-28 11:05:38 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-03-28 11:05:38 - DEBUG UnitTestFramework: '#setup: 'another''

2017-03-28 11:05:39 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-03-28 11:05:39 - DEBUG UnitTestFramework: '#run: 'another''

2017-03-28 11:05:40 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-03-28 11:05:40 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-03-28 11:05:40 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-03-28 11:05:40 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-03-28 11:05:42 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-03-28 11:05:42 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-03-28 11:05:43 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-03-28 11:05:43 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-03-28 11:05:44 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-03-28 11:05:44 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-03-28 11:05:45 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-03-28 11:05:45 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-03-28 11:05:48 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-03-28 11:05:48 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-03-28 11:05:49 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-03-28 11:05:49 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-03-28 11:05:50 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-03-28 11:05:50 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-03-28 11:05:50 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-03-28 11:05:50 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-03-28 11:05:51 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-03-28 11:05:51 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-03-28 11:05:51 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-03-28 11:05:52 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-03-28 11:05:52 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-03-28 11:05:53 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-03-28 11:05:53 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-03-28 11:05:54 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-03-28 11:05:54 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-03-28 11:05:54 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-03-28 11:05:54 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-03-28 11:05:54 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-03-28 11:05:57 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-03-28 11:05:57 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-03-28 11:05:58 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-03-28 11:05:58 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-03-28 11:06:00 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-03-28 11:06:00 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-03-28 11:06:02 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-03-28 11:06:02 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-28 11:06:02 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-28 11:06:02 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-28 11:06:05 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-28 11:06:05 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-28 11:06:07 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-03-28 11:06:07 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-28 11:06:07 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-28 11:06:07 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-28 11:06:08 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-28 11:06:08 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-28 11:06:09 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-03-28 11:06:09 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-28 11:06:12 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-28 11:06:12 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-28 11:06:14 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-28 11:06:14 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-28 11:06:15 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-03-28 11:06:15 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-28 11:06:16 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-28 11:06:16 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-28 11:06:19 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-28 11:06:19 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-28 11:06:20 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-03-28 11:06:20 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-28 11:06:20 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-28 11:06:20 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-28 11:06:21 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-28 11:06:21 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-28 11:06:21 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-03-28 11:06:21 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-03-28 11:06:21 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-03-28 11:06:21 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-03-28 11:06:23 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-03-28 11:06:23 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-03-28 11:06:25 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-03-28 11:06:25 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-03-28 11:06:26 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-03-28 11:06:26 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-03-28 11:06:38 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'transport close''

2017-03-28 11:08:34 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_112800850f460826/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-03-28 11:08:34 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-03-28 11:08:34 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

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
28/3/2017@13:00:20 Getting the list of iOS devices 
28/3/2017@13:00:21 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
28/3/2017@13:00:21 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
28/3/2017@13:00:21 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
28/3/2017@13:00:21 Deploying iOS test app 
28/3/2017@13:00:21 uninstalling the application 
28/3/2017@13:00:22 installing the application 
28/3/2017@13:06:36 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
28/3/2017@13:23:40 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
28/3/2017@13:23:40 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/112800850f460826_Refactor_promiseQueue_implementation_chapko/thali03_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/112800850f460826_Refactor_promiseQueue_implementation_chapko/thali04_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/112800850f460826_Refactor_promiseQueue_implementation_chapko/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/112800850f460826_Refactor_promiseQueue_implementation_chapko/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/112800850f460826_Refactor_promiseQueue_implementation_chapko/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/112800850f460826_Refactor_promiseQueue_implementation_chapko/iOS_server.md)





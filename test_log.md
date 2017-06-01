#### Test 12244969560d457d Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-01 13:53:01 - INFO HttpServer: 'listening on *:3000'

2017-06-01 13:53:02 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '6f19f4bc-7a1d-4c6a-90ca-bf2882483105', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 13:53:02 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-01 13:53:04 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '6f19f4bc-7a1d-4c6a-90ca-bf2882483105', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 13:53:04 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '6f19f4bc-7a1d-4c6a-90ca-bf2882483105', platformName: 'ios''

2017-06-01 13:53:06 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'dcd12806-66ae-46ba-ae56-a71ce7e3fdbb', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 13:53:06 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-01 13:53:08 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'dcd12806-66ae-46ba-ae56-a71ce7e3fdbb', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 13:53:08 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: 'dcd12806-66ae-46ba-ae56-a71ce7e3fdbb', platformName: 'ios''

2017-06-01 13:53:11 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '5650ce03-eb43-44df-b585-bff487b5dede', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 13:53:11 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-01 13:53:11 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-01 13:53:11 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-01 13:53:11 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-01 13:53:14 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '5650ce03-eb43-44df-b585-bff487b5dede', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 13:53:14 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: '5650ce03-eb43-44df-b585-bff487b5dede', platformName: 'ios''

2017-06-01 13:53:27 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-01 13:53:27 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-01 13:53:33 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-01 13:53:33 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-01 13:53:39 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-01 13:53:39 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-01 13:53:52 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-01 13:53:52 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-01 13:53:56 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-01 13:53:56 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-01 13:54:02 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-01 13:54:02 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-01 13:54:13 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-01 13:54:13 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:54:16 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:54:16 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:54:22 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:54:22 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:54:26 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '01191d12-6bbc-4be2-8a54-2ddc2fcb7f21', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 13:54:26 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-01 13:54:27 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:54:27 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:54:42 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '78d2ab61-e71c-419d-b0a9-7c7985363f30', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 13:54:42 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-01 13:54:47 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:54:47 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:54:47 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:54:47 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:54:48 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:54:48 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:54:51 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:54:51 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:54:51 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 13:54:52 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 13:54:53 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 13:54:53 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:54:53 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:54:56 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:54:56 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:55:03 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:55:03 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:55:03 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:55:03 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:55:05 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:55:05 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:55:05 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:55:18 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:55:18 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:55:24 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:55:24 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:55:24 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:55:24 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:55:27 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:55:27 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:55:27 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:55:35 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:55:35 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:55:43 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:55:43 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:55:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:55:44 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:55:46 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:55:46 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:55:46 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:55:47 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:55:47 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-01 13:55:53 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-01 13:55:53 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-01 13:56:01 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-01 13:56:01 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-01 13:56:03 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-01 13:56:03 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-01 13:56:08 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-01 13:56:08 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-01 13:56:09 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-01 13:56:09 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-01 13:56:15 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-01 13:56:15 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-01 13:56:16 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '1caa6d3e-b9b3-489a-be58-bf3ba10b5c9f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 13:56:16 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-01 13:56:16 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-06-01 13:56:17 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-06-01 13:56:17 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-01 13:56:17 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-01 13:56:17 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-01 13:56:17 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-01 13:56:17 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-01 13:56:18 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-01 13:56:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '1caa6d3e-b9b3-489a-be58-bf3ba10b5c9f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 13:56:18 - INFO TestFramework: 'updating existing device, name: 'samsung-SM-G935F', uuid: '1caa6d3e-b9b3-489a-be58-bf3ba10b5c9f', platformName: 'android''

2017-06-01 13:56:19 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:56:19 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:56:20 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 13:56:20 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:56:21 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:56:21 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:56:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 13:56:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 13:56:22 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 13:56:22 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:56:22 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:56:22 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 13:56:22 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:56:23 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:56:23 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:56:23 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:56:23 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:56:23 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:56:23 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:56:23 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:56:24 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 13:56:24 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:56:24 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:56:24 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:56:25 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:56:25 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:56:25 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:56:25 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:56:25 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:56:25 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 13:56:25 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:56:29 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:56:29 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:56:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:56:29 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:56:30 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:56:30 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:56:30 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:56:30 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 13:56:30 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-01 13:56:30 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-01 13:56:30 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-01 13:56:31 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-01 13:56:32 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-01 13:56:33 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-01 13:56:34 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-01 13:56:34 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-01 13:56:34 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-01 13:56:34 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-01 13:56:35 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-01 13:56:35 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-01 13:56:37 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-01 13:56:37 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-01 13:56:38 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-01 13:56:38 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-01 13:56:39 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-01 13:56:39 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-01 13:56:48 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-01 13:56:48 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-01 13:56:51 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-01 13:56:51 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-01 13:56:52 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-01 13:56:52 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-01 13:56:52 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-01 13:56:52 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-01 13:56:53 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-01 13:56:53 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-01 13:56:56 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-01 13:56:56 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-01 13:57:00 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-01 13:57:00 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-01 13:57:00 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-01 13:57:00 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-01 13:57:00 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-01 13:57:00 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-01 13:57:01 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-01 13:57:01 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-01 13:57:01 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-01 13:57:01 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-01 13:57:01 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-01 13:57:01 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-01 13:57:02 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-01 13:57:02 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-01 13:57:02 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-01 13:57:02 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-01 13:57:05 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-01 13:57:05 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-01 13:57:05 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-01 13:57:05 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 13:57:05 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 13:57:05 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 13:57:05 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 13:57:05 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 13:57:06 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 13:57:06 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 13:57:06 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 13:57:06 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 13:57:06 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 13:57:06 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 13:57:06 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 13:57:06 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 13:57:06 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 13:57:06 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 13:57:07 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 13:57:07 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 13:57:07 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 13:57:07 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 13:57:07 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 13:57:07 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 13:57:08 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 13:57:08 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 13:57:09 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 13:57:09 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 13:57:10 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 13:57:10 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 13:57:11 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 13:57:11 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 13:57:11 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 13:57:11 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-01 13:57:11 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-01 13:57:11 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-01 13:57:13 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-01 13:57:13 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-01 13:57:14 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-01 13:57:14 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-01 13:57:15 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-01 13:57:15 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-01 13:57:15 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-01 13:57:15 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-01 13:57:19 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-01 13:57:19 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-01 13:57:42 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-06-01 13:57:42 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-06-01 13:57:43 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-06-01 13:57:43 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-06-01 13:57:43 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-06-01 13:57:43 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-06-01 13:58:01 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-01 13:58:01 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-01 13:58:03 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-01 13:58:03 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-01 13:58:04 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-01 13:58:04 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-01 13:58:05 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-01 13:58:05 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-01 13:58:06 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-01 13:58:06 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-01 13:58:07 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-01 13:58:07 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-01 13:58:08 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-01 13:58:08 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-01 13:58:08 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-01 13:58:08 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-01 13:58:09 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-01 13:58:09 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-01 13:58:09 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-01 13:58:09 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-01 13:58:10 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-01 13:58:10 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-01 13:58:10 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-01 13:58:10 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-01 13:58:11 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-01 13:58:11 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-01 13:58:18 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-01 13:58:18 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-01 13:58:23 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-06-01 13:58:23 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-06-01 13:58:24 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-06-01 13:58:24 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-06-01 13:58:24 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-06-01 13:58:24 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-06-01 13:58:24 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-01 13:58:25 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-01 13:58:25 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-01 13:58:25 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-06-01 13:58:25 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-06-01 13:58:25 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-06-01 13:58:25 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-06-01 13:58:25 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-06-01 13:58:25 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-06-01 13:58:26 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-01 13:58:26 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-01 13:58:29 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-01 13:58:29 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-01 13:58:34 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-06-01 13:58:34 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-06-01 13:58:35 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-06-01 13:58:35 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-06-01 13:58:35 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-06-01 13:58:35 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-06-01 13:58:40 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-01 13:58:40 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-01 13:58:43 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-01 13:58:43 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-01 13:58:51 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-01 13:58:51 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-01 13:58:57 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-06-01 13:58:57 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-06-01 13:58:58 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-06-01 13:58:58 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-01 13:58:58 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-01 13:58:58 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-01 13:59:05 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-01 13:59:05 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-01 13:59:06 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-01 13:59:06 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-06-01 13:59:06 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-06-01 13:59:06 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-06-01 13:59:06 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-01 13:59:06 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-01 13:59:06 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-01 13:59:06 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-06-01 13:59:06 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-06-01 13:59:06 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-06-01 13:59:06 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-01 13:59:06 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-01 13:59:06 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-01 13:59:08 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-01 13:59:08 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-01 13:59:09 - ERROR UnitTestFramework: '#run failed: 'discoveryAdvertisingStateUpdateNonTCP is called', error: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"01191d12-6bbc-4be2-8a54-2ddc2fcb7f21"},{"uuid":"78d2ab61-e71c-419d-b0a9-7c7985363f30"},{"uuid":"1caa6d3e-b9b3-489a-be58-bf3ba10b5c9f"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"01191d12-6bbc-4be2-8a54-2ddc2fcb7f21"},{"uuid":"78d2ab61-e71c-419d-b0a9-7c7985363f30"},{"uuid":"1caa6d3e-b9b3-489a-be58-bf3ba10b5c9f"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_12244969560d457d/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_12244969560d457d/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-06-01 13:59:09 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"01191d12-6bbc-4be2-8a54-2ddc2fcb7f21"},{"uuid":"78d2ab61-e71c-419d-b0a9-7c7985363f30"},{"uuid":"1caa6d3e-b9b3-489a-be58-bf3ba10b5c9f"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"01191d12-6bbc-4be2-8a54-2ddc2fcb7f21"},{"uuid":"78d2ab61-e71c-419d-b0a9-7c7985363f30"},{"uuid":"1caa6d3e-b9b3-489a-be58-bf3ba10b5c9f"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_12244969560d457d/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_12244969560d457d/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-06-01 13:59:17 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-01 13:59:17 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-01 13:59:31 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-01 13:59:31 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-01 13:59:39 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-01 13:59:39 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-01 13:59:40 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-01 13:59:40 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-01 13:59:40 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-01 13:59:40 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-01 13:59:43 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-01 13:59:43 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-01 13:59:49 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-01 13:59:49 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-01 13:59:56 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-01 13:59:56 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-01 13:59:59 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-01 13:59:59 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-01 14:00:01 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-01 14:00:01 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-01 14:00:25 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-01 14:00:25 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-01 14:00:26 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-01 14:00:26 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-01 14:00:27 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-01 14:00:27 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-01 14:00:29 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-01 14:00:29 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-01 14:00:33 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-01 14:00:33 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-01 14:00:34 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-01 14:00:34 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-01 14:00:36 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-01 14:00:36 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-01 14:00:44 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-01 14:00:44 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-01 14:01:44 - ERROR UnitTestFramework: '#run failed: 'Correctly parses/stringifies USN', error: 'TimeoutError: timeout exceeded, event: 'teardown_Correctly parses/stringifies USN_finished', test: 'Correctly parses/stringifies USN'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_Correctly parses/stringifies USN_finished', test: 'Correctly parses/stringifies USN'
    at afterTimeout (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-01 14:01:44 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'teardown_Correctly parses/stringifies USN_finished', test: 'Correctly parses/stringifies USN'', stack: 'TimeoutError: timeout exceeded, event: 'teardown_Correctly parses/stringifies USN_finished', test: 'Correctly parses/stringifies USN'
    at afterTimeout (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_12244969560d457d/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-01 14:02:07 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'transport error''

2017-06-01 14:02:10 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '6f19f4bc-7a1d-4c6a-90ca-bf2882483105', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 14:02:10 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '6f19f4bc-7a1d-4c6a-90ca-bf2882483105', platformName: 'ios''

2017-06-01 14:02:11 - DEBUG TestServer: 'completed'

2017-06-01 14:02:11 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-06-01 14:02:11 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-06-01 14:02:11 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-01 14:02:11 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-01 14:02:11 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-06-01 14:02:11 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

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
1/6/2017@15:49:32 Getting the list of iOS devices 
1/6/2017@15:49:33 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
1/6/2017@15:49:33 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
1/6/2017@15:49:33 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
1/6/2017@15:49:33 Deploying iOS test app 
1/6/2017@15:49:33 uninstalling the application 
1/6/2017@15:49:34 installing the application 
1/6/2017@16:12:52 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
1/6/2017@16:12:52 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
1/6/2017@16:12:52 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/12244969560d457d_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/thali03_samsung-SM-G935F.md)

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

App was succesfully started on ce0616068b9f212302

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/12244969560d457d_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/thali04_samsung-SM-G930F.md)

####Node name: thali05
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/12244969560d457d_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/12244969560d457d_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/12244969560d457d_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/12244969560d457d_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/12244969560d457d_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_server.md)





#### Test 122449695f36eb0f Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-01 14:26:32 - INFO HttpServer: 'listening on *:3000'

2017-06-01 14:26:34 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '948be617-b95a-422e-9564-b2fdebb9771e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 14:26:34 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-01 14:26:36 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '948be617-b95a-422e-9564-b2fdebb9771e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 14:26:36 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: '948be617-b95a-422e-9564-b2fdebb9771e', platformName: 'ios''

2017-06-01 14:26:40 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '44972e38-17d9-4ae2-8d96-76568d2ee284', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 14:26:40 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-01 14:26:40 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '3666a8a8-0313-4eff-a68b-429161a4b780', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 14:26:40 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-01 14:26:40 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-01 14:26:40 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-01 14:26:40 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-01 14:26:42 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '44972e38-17d9-4ae2-8d96-76568d2ee284', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 14:26:42 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '44972e38-17d9-4ae2-8d96-76568d2ee284', platformName: 'ios''

2017-06-01 14:26:48 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-01 14:26:48 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-01 14:26:57 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-01 14:26:57 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-01 14:26:59 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-01 14:26:59 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-01 14:27:06 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-01 14:27:06 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-01 14:27:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-01 14:27:09 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-01 14:27:11 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-01 14:27:11 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-01 14:27:11 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-01 14:27:11 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:27:12 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:27:12 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:27:12 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:27:12 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:27:14 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:27:14 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:27:31 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:27:31 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:27:44 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:27:44 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:27:56 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:27:56 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:27:58 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:27:58 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:27:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 14:27:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 14:28:08 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'c2999938-e568-466d-813e-4370578d6db6', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 14:28:08 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-01 14:28:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 14:28:15 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:28:15 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:28:16 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:28:16 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:28:20 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'b885a433-4a25-4b43-9cab-21c4b5a6e6b6', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 14:28:20 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-01 14:28:22 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:28:22 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:28:22 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:28:23 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:28:30 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:28:30 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:28:30 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:28:35 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:28:35 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:28:37 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:28:37 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:28:37 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:28:37 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:28:39 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:28:39 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:28:39 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:28:41 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:28:41 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:28:46 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:28:46 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:28:46 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:28:46 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:06 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:06 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:06 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:13 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:13 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-01 14:29:19 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-01 14:29:19 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-01 14:29:34 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-01 14:29:34 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-01 14:29:35 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-01 14:29:35 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-01 14:29:35 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-01 14:29:35 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-01 14:29:35 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-01 14:29:35 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-01 14:29:36 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-01 14:29:36 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-01 14:29:36 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-01 14:29:36 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-01 14:29:37 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-01 14:29:37 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-01 14:29:38 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '944423d6-a32c-496c-b281-4e2ac4a5ee69', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-01 14:29:38 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-01 14:29:38 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-06-01 14:29:38 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-06-01 14:29:38 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-01 14:29:38 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-01 14:29:38 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-01 14:29:38 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-01 14:29:38 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-01 14:29:39 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-01 14:29:39 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-01 14:29:39 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-01 14:29:39 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-01 14:29:40 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-01 14:29:40 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-01 14:29:40 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-01 14:29:40 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:40 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-01 14:29:40 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-01 14:29:41 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-01 14:29:41 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-01 14:29:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-01 14:29:41 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-01 14:29:43 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-01 14:29:43 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:29:44 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:45 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:45 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:46 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-01 14:29:46 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-01 14:29:47 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-01 14:29:47 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-01 14:29:47 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-01 14:29:47 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:47 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-01 14:29:47 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-01 14:29:48 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-01 14:29:48 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-01 14:29:49 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-01 14:29:49 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:50 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:51 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:51 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:51 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:51 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:52 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-01 14:29:53 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-01 14:29:53 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-01 14:29:53 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-01 14:29:53 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-01 14:29:53 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-01 14:29:53 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-01 14:29:54 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-01 14:29:54 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-01 14:29:55 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-01 14:29:55 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-01 14:29:56 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-01 14:29:56 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-01 14:29:57 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-01 14:29:57 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-01 14:29:57 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-01 14:29:57 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-01 14:29:57 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-01 14:29:57 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-01 14:29:57 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-01 14:29:57 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-01 14:29:57 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-01 14:29:57 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-01 14:29:58 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-01 14:29:59 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-01 14:29:59 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-01 14:30:00 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:30:01 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:30:03 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:30:03 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:30:03 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:30:03 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:30:03 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:30:03 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:30:04 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:30:04 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-01 14:30:05 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-01 14:30:06 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:30:06 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:30:06 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:30:06 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:30:07 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:30:07 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-01 14:30:08 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-01 14:30:09 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-01 14:30:09 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-01 14:30:10 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-01 14:30:10 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-01 14:30:11 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-01 14:30:11 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-01 14:30:11 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-01 14:30:11 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-01 14:30:17 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-01 14:30:17 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-01 14:30:19 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-01 14:30:19 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-01 14:30:23 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-01 14:30:23 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-01 14:30:25 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-01 14:30:25 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-01 14:30:25 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-06-01 14:30:25 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-06-01 14:30:27 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-01 14:30:27 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-01 14:30:28 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-06-01 14:30:28 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-06-01 14:30:28 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-01 14:30:28 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-01 14:30:28 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-06-01 14:30:28 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-06-01 14:30:29 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-01 14:30:29 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-01 14:30:29 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-01 14:30:29 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-01 14:30:30 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-01 14:30:30 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-01 14:30:33 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-01 14:30:33 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-01 14:30:33 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-01 14:30:33 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-01 14:30:34 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-01 14:30:34 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-01 14:30:34 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-01 14:30:34 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-01 14:30:35 - ERROR UnitTestFramework: '#run failed: 'Can shift data', error: 'Error: run failed, test: 'Can shift data', event: 'run_Can shift data', sent data: '[{"uuid":"c2999938-e568-466d-813e-4370578d6db6"},{"uuid":"b885a433-4a25-4b43-9cab-21c4b5a6e6b6"},{"uuid":"944423d6-a32c-496c-b281-4e2ac4a5ee69"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'Can shift data', event: 'run_Can shift data', sent data: '[{"uuid":"c2999938-e568-466d-813e-4370578d6db6"},{"uuid":"b885a433-4a25-4b43-9cab-21c4b5a6e6b6"},{"uuid":"944423d6-a32c-496c-b281-4e2ac4a5ee69"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_122449695f36eb0f/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_122449695f36eb0f/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-06-01 14:30:35 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: run failed, test: 'Can shift data', event: 'run_Can shift data', sent data: '[{"uuid":"c2999938-e568-466d-813e-4370578d6db6"},{"uuid":"b885a433-4a25-4b43-9cab-21c4b5a6e6b6"},{"uuid":"944423d6-a32c-496c-b281-4e2ac4a5ee69"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'Can shift data', event: 'run_Can shift data', sent data: '[{"uuid":"c2999938-e568-466d-813e-4370578d6db6"},{"uuid":"b885a433-4a25-4b43-9cab-21c4b5a6e6b6"},{"uuid":"944423d6-a32c-496c-b281-4e2ac4a5ee69"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_122449695f36eb0f/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_122449695f36eb0f/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-06-01 14:30:47 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-01 14:30:47 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-01 14:30:50 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-01 14:30:50 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-01 14:30:55 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-01 14:30:55 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-01 14:30:57 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-01 14:30:57 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-01 14:31:21 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-01 14:31:21 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-01 14:31:41 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-01 14:31:41 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-01 14:31:46 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-01 14:31:46 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-01 14:31:51 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-01 14:31:51 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-01 14:31:57 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-01 14:31:57 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-01 14:31:58 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-01 14:31:58 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-01 14:32:11 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-01 14:32:11 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-01 14:32:29 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-01 14:32:29 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-01 14:32:36 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-01 14:32:36 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-01 14:32:39 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-01 14:32:39 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-01 14:32:39 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-01 14:32:39 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-01 14:32:39 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-01 14:32:39 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-01 14:32:39 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-01 14:32:39 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-01 14:32:39 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-01 14:32:39 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-01 14:32:39 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-01 14:32:39 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-01 14:32:39 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-01 14:32:39 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-01 14:32:39 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-01 14:32:39 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-01 14:32:40 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-01 14:32:40 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:32:43 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:32:43 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:32:53 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:32:53 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:33:01 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-01 14:33:01 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:33:08 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:33:08 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:33:27 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:33:27 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:33:46 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-01 14:33:46 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:33:50 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:33:50 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:34:07 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:34:07 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:34:13 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-01 14:34:13 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:34:26 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:34:26 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:34:28 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:34:28 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:34:31 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-01 14:34:31 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:34:43 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:34:43 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:34:44 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:34:44 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:34:45 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-01 14:34:45 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:34:47 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:34:47 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:35:02 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:35:02 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:35:03 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-01 14:35:03 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-01 14:35:04 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-01 14:35:04 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-01 14:35:06 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-01 14:35:06 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-01 14:35:07 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-01 14:35:07 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-01 14:35:07 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-01 14:35:07 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-01 14:35:18 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-06-01 14:35:18 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-06-01 14:35:19 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-06-01 14:35:19 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-06-01 14:35:19 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-06-01 14:35:19 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-06-01 14:35:25 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-06-01 14:35:25 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-06-01 14:35:25 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-06-01 14:35:25 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-06-01 14:35:26 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-06-01 14:35:26 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-06-01 14:38:26 - ERROR UnitTestFramework: '#run failed: 'Can shift data via parallel connections', error: 'TimeoutError: timeout exceeded, event: 'run_Can shift data via parallel connections_finished', test: 'Can shift data via parallel connections'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can shift data via parallel connections_finished', test: 'Can shift data via parallel connections'
    at afterTimeout (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-01 14:38:26 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can shift data via parallel connections_finished', test: 'Can shift data via parallel connections'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can shift data via parallel connections_finished', test: 'Can shift data via parallel connections'
    at afterTimeout (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_122449695f36eb0f/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-01 14:38:27 - DEBUG TestServer: 'completed'

2017-06-01 14:38:27 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-06-01 14:38:27 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-06-01 14:38:27 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-06-01 14:38:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-01 14:38:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-06-01 14:38:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
1/6/2017@16:23:18 Getting the list of iOS devices 
1/6/2017@16:23:19 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
1/6/2017@16:23:19 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
1/6/2017@16:23:19 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
1/6/2017@16:23:19 Deploying iOS test app 
1/6/2017@16:23:19 uninstalling the application 
1/6/2017@16:23:20 installing the application 
1/6/2017@16:46:38 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/122449695f36eb0f_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/thali03_samsung-SM-G935F.md)

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

App was succesfully started on ce0616068b9f212302

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/122449695f36eb0f_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/thali04_samsung-SM-G930F.md)

####Node name: thali05
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

STOP log received from ce061606c181d71003
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/122449695f36eb0f_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/122449695f36eb0f_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/122449695f36eb0f_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/122449695f36eb0f_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/122449695f36eb0f_Provide_remote_db_name_for_ThaliReplicationPeerAction_during_runtime__1873_mlesnic/iOS_server.md)





#### Test 1248535468480830 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-20 07:57:07 - INFO HttpServer: 'listening on *:3000'

2017-06-20 07:57:08 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '002648c6-29cc-4b38-97bb-998e6a10042f', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 07:57:08 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-20 07:57:10 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '002648c6-29cc-4b38-97bb-998e6a10042f', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 07:57:10 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '002648c6-29cc-4b38-97bb-998e6a10042f', platformName: 'ios''

2017-06-20 07:57:11 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '861b72b2-be90-4cd4-8f5b-1af2250f5356', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 07:57:11 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-20 07:57:13 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '861b72b2-be90-4cd4-8f5b-1af2250f5356', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 07:57:13 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: '861b72b2-be90-4cd4-8f5b-1af2250f5356', platformName: 'ios''

2017-06-20 07:57:13 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '0332fb13-7589-4901-b005-f3a2855ea8cd', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 07:57:13 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-20 07:57:13 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-20 07:57:13 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-20 07:57:13 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-20 07:57:15 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '0332fb13-7589-4901-b005-f3a2855ea8cd', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 07:57:15 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: '0332fb13-7589-4901-b005-f3a2855ea8cd', platformName: 'ios''

2017-06-20 07:57:18 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-20 07:57:18 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-20 07:57:35 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-20 07:57:35 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-20 07:57:35 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-20 07:57:35 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-20 07:57:37 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-20 07:57:37 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-20 07:57:39 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-20 07:57:39 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-20 07:57:40 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-20 07:57:40 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-20 07:57:41 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-20 07:57:41 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 07:57:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 07:57:41 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 07:57:43 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 07:57:43 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 07:57:43 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 07:57:43 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 07:57:44 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 07:57:44 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 07:57:44 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 07:57:44 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 07:57:45 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 07:57:45 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 07:57:45 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 07:57:45 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 07:57:46 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 07:57:47 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 07:57:48 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 07:57:48 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 07:57:48 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 07:57:48 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 07:57:48 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 07:57:49 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 07:57:49 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 07:57:49 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 07:57:49 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 07:58:04 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 07:58:04 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 07:58:04 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 07:58:04 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 07:58:04 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 07:58:05 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 07:58:05 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 07:58:05 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 07:58:05 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 07:58:16 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '358e9ac0-dc1f-4495-9bb5-25fb80754524', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 07:58:16 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-20 07:58:28 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 07:58:28 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 07:58:28 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 07:58:30 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 07:58:30 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 07:58:33 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '3979fa83-de9f-4c60-b453-1f1fecd81ef4', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 07:58:33 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-20 07:58:42 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 07:58:42 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 07:58:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 07:58:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 07:58:46 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 07:58:46 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 07:58:46 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 07:58:49 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 07:58:49 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-20 07:58:53 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-20 07:58:53 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-20 07:58:54 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-20 07:58:54 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-20 07:58:54 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-20 07:58:54 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-20 07:58:55 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-20 07:58:55 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-20 07:58:56 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-20 07:58:56 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-20 07:59:15 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-20 07:59:15 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-20 07:59:16 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-20 07:59:16 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-20 07:59:19 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-20 07:59:19 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-20 07:59:22 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-20 07:59:22 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-20 07:59:32 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-20 07:59:32 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-20 07:59:36 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-20 07:59:36 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-20 07:59:39 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-20 07:59:39 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-20 07:59:39 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-20 07:59:39 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-20 07:59:40 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-20 07:59:40 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-20 07:59:41 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-20 07:59:41 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-20 07:59:44 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-20 07:59:44 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-20 07:59:45 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-20 07:59:45 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-20 07:59:55 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-20 07:59:55 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:12 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:12 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:12 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '29b897a1-db95-4378-b83a-820c48d006a7', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 08:00:12 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-20 08:00:12 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''
2017-06-20 08:00:12 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-06-20 08:00:12 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:13 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-20 08:00:13 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 08:00:14 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 08:00:14 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 08:00:14 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 08:00:14 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 08:00:15 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 08:00:15 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 08:00:15 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 08:00:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 08:00:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 08:00:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 08:00:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 08:00:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 08:00:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-20 08:00:15 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-20 08:00:16 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:17 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-20 08:00:18 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-20 08:00:19 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-20 08:00:20 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-20 08:00:21 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-20 08:00:21 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-20 08:00:21 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-20 08:00:21 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:00:21 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:00:21 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:00:22 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:00:22 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:00:22 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:00:22 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:00:22 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:00:22 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:00:23 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-20 08:00:23 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-20 08:00:23 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:00:23 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:00:24 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:00:24 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:00:24 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:00:24 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:00:24 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:00:24 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:00:24 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:00:24 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:00:24 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:00:24 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:00:25 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:00:25 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:00:25 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:00:25 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:00:25 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:00:25 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-20 08:00:26 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-20 08:00:29 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-20 08:00:29 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-20 08:00:32 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-20 08:00:32 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-20 08:00:32 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-20 08:00:32 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-20 08:00:34 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-20 08:00:34 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-20 08:00:37 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-20 08:00:37 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-20 08:00:43 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-06-20 08:00:43 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-06-20 08:00:44 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-06-20 08:00:44 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-06-20 08:00:45 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-06-20 08:00:45 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-06-20 08:00:48 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-20 08:00:48 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-20 08:00:51 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-20 08:00:51 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-20 08:00:52 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-20 08:00:52 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-20 08:00:52 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-06-20 08:00:52 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-06-20 08:00:53 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-20 08:00:53 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-20 08:00:53 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-06-20 08:00:53 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-06-20 08:00:53 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-06-20 08:00:53 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-06-20 08:00:53 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-20 08:00:54 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-20 08:00:54 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-20 08:00:54 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-06-20 08:00:54 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-06-20 08:00:54 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-06-20 08:00:54 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-06-20 08:00:54 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-06-20 08:00:54 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-06-20 08:01:00 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-20 08:01:00 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-20 08:01:03 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-20 08:01:03 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-20 08:01:03 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-06-20 08:01:03 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-06-20 08:01:03 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-20 08:01:03 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-20 08:01:04 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-06-20 08:01:04 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-06-20 08:01:04 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-06-20 08:01:04 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-06-20 08:01:04 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-20 08:01:04 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-20 08:01:05 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-20 08:01:05 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-20 08:01:08 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-20 08:01:08 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-20 08:01:14 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-06-20 08:01:14 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-06-20 08:01:15 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-06-20 08:01:15 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 08:01:15 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 08:01:15 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 08:01:20 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-20 08:01:20 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-20 08:01:25 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-20 08:01:25 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-20 08:01:26 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 08:01:26 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 08:01:27 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-20 08:01:27 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-06-20 08:01:27 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-06-20 08:01:27 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-06-20 08:01:27 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-20 08:01:27 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-20 08:01:27 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-20 08:01:28 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-06-20 08:01:28 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-06-20 08:01:28 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-06-20 08:01:28 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-20 08:01:28 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-20 08:01:28 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-20 08:01:28 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-20 08:01:28 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-20 08:01:30 - ERROR UnitTestFramework: '#run failed: 'discoveryAdvertisingStateUpdateNonTCP is called', error: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"358e9ac0-dc1f-4495-9bb5-25fb80754524"},{"uuid":"3979fa83-de9f-4c60-b453-1f1fecd81ef4"},{"uuid":"29b897a1-db95-4378-b83a-820c48d006a7"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"358e9ac0-dc1f-4495-9bb5-25fb80754524"},{"uuid":"3979fa83-de9f-4c60-b453-1f1fecd81ef4"},{"uuid":"29b897a1-db95-4378-b83a-820c48d006a7"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_1248535468480830/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_1248535468480830/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-06-20 08:01:30 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"358e9ac0-dc1f-4495-9bb5-25fb80754524"},{"uuid":"3979fa83-de9f-4c60-b453-1f1fecd81ef4"},{"uuid":"29b897a1-db95-4378-b83a-820c48d006a7"}]', received data: '{"success":false}'', stack: 'Error: run failed, test: 'discoveryAdvertisingStateUpdateNonTCP is called', event: 'run_discoveryAdvertisingStateUpdateNonTCP is called', sent data: '[{"uuid":"358e9ac0-dc1f-4495-9bb5-25fb80754524"},{"uuid":"3979fa83-de9f-4c60-b453-1f1fecd81ef4"},{"uuid":"29b897a1-db95-4378-b83a-820c48d006a7"}]', received data: '{"success":false}'
    at finishedHandler (/home/pi/Test/server_1248535468480830/test/TestServer/Socket.js:205:15)
    at Socket.<anonymous> (/home/pi/Test/server_1248535468480830/test/TestServer/Socket.js:238:9)
    at Socket.g (events.js:160:16)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/lib/socket.js:335:8)
    at Socket.onpacket (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/lib/socket.js:295:12)
    at Client.ondecoded (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/lib/client.js:175:18)
    at Socket.emit (events.js:82:17)
    at Socket.onPacket (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/socket.js:101:14)
    at WebSocket.emit (events.js:82:17)
    at WebSocket.Transport.onPacket (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:104:8)
    at WebSocket.Transport.onData (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transport.js:115:8)
    at WebSocket.onData (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/socket.io/node_modules/engine.io/lib/transports/websocket.js:76:30)
    at WebSocket.emit (events.js:85:17)''

2017-06-20 08:01:33 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-20 08:01:33 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-20 08:01:37 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-20 08:01:37 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-20 08:01:39 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-20 08:01:39 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-20 08:01:41 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-20 08:01:41 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-20 08:01:54 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-20 08:01:54 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-20 08:01:59 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-20 08:01:59 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-20 08:02:03 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-20 08:02:03 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-20 08:02:15 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-20 08:02:15 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-20 08:02:18 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-20 08:02:18 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-20 08:02:21 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-20 08:02:21 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-20 08:02:40 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-20 08:02:40 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-20 08:02:40 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-20 08:02:40 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-20 08:02:43 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-20 08:02:43 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-20 08:02:43 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-20 08:02:43 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-20 08:02:45 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-20 08:02:45 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-20 08:02:46 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-20 08:02:48 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-20 08:02:49 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-20 08:02:49 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-20 08:02:49 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-20 08:02:53 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-20 08:02:53 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-20 08:03:01 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-20 08:03:01 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-20 08:03:02 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-20 08:03:02 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-20 08:03:02 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-20 08:03:02 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-20 08:03:02 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-20 08:03:04 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-20 08:03:04 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:03:04 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:03:04 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:03:18 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:03:18 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:03:21 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 08:03:21 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:03:24 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:03:24 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:03:27 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:03:27 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:03:29 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 08:03:29 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:03:36 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:03:36 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:03:56 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:03:56 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:04:01 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 08:04:01 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:04:02 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:04:02 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:04:02 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:04:02 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:04:05 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 08:04:05 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:04:12 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:04:12 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:04:17 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:04:17 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:04:22 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 08:04:22 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:04:23 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:04:23 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:04:28 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:04:28 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:04:32 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 08:04:32 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-20 08:04:40 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-20 08:04:40 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-20 08:04:48 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-20 08:04:48 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-20 08:04:49 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-20 08:04:49 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-20 08:04:52 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-20 08:04:52 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-20 08:07:52 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-20 08:07:52 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1248535468480830/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-20 08:07:57 - DEBUG TestServer: 'completed'

2017-06-20 08:07:57 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-06-20 08:07:57 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-06-20 08:07:57 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-06-20 08:07:57 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-20 08:07:57 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-20 08:07:57 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

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
20/6/2017@09:53:34 Getting the list of iOS devices 
20/6/2017@09:53:35 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
20/6/2017@09:53:35 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
20/6/2017@09:53:35 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
20/6/2017@09:53:35 Deploying iOS test app 
20/6/2017@09:53:35 uninstalling the application 
20/6/2017@09:53:35 installing the application 
20/6/2017@10:16:54 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
20/6/2017@10:16:54 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
20/6/2017@10:16:54 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
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
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1248535468480830_Make_tests_zombie_proof_jareksl/thali03_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1248535468480830_Make_tests_zombie_proof_jareksl/thali04_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1248535468480830_Make_tests_zombie_proof_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1248535468480830_Make_tests_zombie_proof_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1248535468480830_Make_tests_zombie_proof_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1248535468480830_Make_tests_zombie_proof_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/1248535468480830_Make_tests_zombie_proof_jareksl/iOS_server.md)





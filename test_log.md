#### Test 12650373415b391b Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-20 18:30:39 - INFO HttpServer: 'listening on *:3000'

2017-06-20 18:30:42 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'a749a55f-0a14-4220-97c7-7f455aab0590', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 18:30:42 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-20 18:30:43 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '1f6b994a-48d7-4c7b-932d-e0b6e70dff52', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 18:30:43 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-20 18:30:44 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'a749a55f-0a14-4220-97c7-7f455aab0590', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 18:30:44 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: 'a749a55f-0a14-4220-97c7-7f455aab0590', platformName: 'ios''

2017-06-20 18:30:44 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'a66226f4-5a34-4b6c-9b6c-43ce624f5210', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 18:30:44 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-20 18:30:44 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-20 18:30:44 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-20 18:30:44 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-20 18:30:46 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'a66226f4-5a34-4b6c-9b6c-43ce624f5210', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 18:30:46 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'a66226f4-5a34-4b6c-9b6c-43ce624f5210', platformName: 'ios''

2017-06-20 18:30:59 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-20 18:30:59 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-20 18:31:04 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-20 18:31:04 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-20 18:31:07 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-20 18:31:07 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-20 18:31:09 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-20 18:31:09 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-20 18:31:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-20 18:31:09 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-20 18:31:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-20 18:31:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-20 18:31:11 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-20 18:31:11 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:31:11 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:31:11 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:31:11 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:31:11 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:31:12 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:31:12 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:31:12 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:31:12 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:31:12 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:31:12 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:31:13 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:31:13 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:31:13 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:31:13 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:31:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 18:31:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 18:31:13 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 18:31:13 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:31:13 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:31:14 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:31:14 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:31:14 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:31:14 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:31:14 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:31:15 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:31:15 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:31:15 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''
2017-06-20 18:31:15 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:31:16 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:31:16 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:31:19 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:31:19 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:31:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:31:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:31:34 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:31:34 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:31:34 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:31:51 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:31:51 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:31:59 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:31:59 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:32:00 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:32:01 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:32:02 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'd88129f2-936e-494d-9ab7-ee2f6561c4cf', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 18:32:02 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-20 18:32:16 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '374d53ba-5fda-45eb-b7d4-fae31c3f9b4f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 18:32:16 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-20 18:32:23 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:32:23 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:32:23 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:32:26 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:32:26 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-20 18:32:30 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-20 18:32:30 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-20 18:32:45 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-20 18:32:45 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-20 18:32:48 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-20 18:32:48 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-20 18:32:50 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-20 18:32:50 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-20 18:32:50 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-20 18:32:50 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-20 18:32:50 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-20 18:32:50 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-20 18:32:52 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-20 18:32:52 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-20 18:32:53 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-20 18:32:53 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-20 18:32:55 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-20 18:32:55 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-20 18:32:55 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-20 18:32:55 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-20 18:32:55 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-20 18:32:55 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-20 18:32:56 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-20 18:32:56 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-20 18:32:59 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-20 18:32:59 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-20 18:33:00 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-20 18:33:00 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-20 18:33:00 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-20 18:33:00 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-20 18:33:00 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-20 18:33:00 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-20 18:33:00 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-20 18:33:00 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-20 18:33:02 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-20 18:33:02 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:03 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:03 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:18 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:18 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:38 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:38 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-20 18:33:40 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '2b9ef50d-5034-46e9-954c-a1d439841806', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-20 18:33:40 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''
2017-06-20 18:33:40 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-06-20 18:33:40 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''
2017-06-20 18:33:40 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-20 18:33:41 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:33:41 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:33:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 18:33:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 18:33:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:33:42 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:33:42 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:33:42 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:33:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:33:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:33:42 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:33:42 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:33:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:33:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:33:43 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-20 18:33:43 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-20 18:33:44 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-20 18:33:45 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-20 18:33:45 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-20 18:33:45 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-20 18:33:45 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-20 18:33:45 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-20 18:33:45 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-20 18:33:45 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-20 18:33:46 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-20 18:33:46 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run: 'skip''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup: 'skip with skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup ok: 'skip with skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run: 'skip with skip function''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'skip with skip function', event: 'run_skip with skip function''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'skip with skip function', event: 'run_skip with skip function''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'skip with skip function', event: 'run_skip with skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run ok: 'skip with skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown: 'skip with skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown ok: 'skip with skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup: 'skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup ok: 'skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run: 'skip function''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'skip function', event: 'run_skip function''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'skip function', event: 'run_skip function''

2017-06-20 18:33:47 - INFO Socket: 'run skipped, test: 'skip function', event: 'run_skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run ok: 'skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown: 'skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown ok: 'skip function''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-20 18:33:47 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-20 18:33:48 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-20 18:33:49 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-20 18:33:49 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-20 18:33:49 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-20 18:33:49 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-20 18:33:49 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-20 18:33:49 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:33:50 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:33:51 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-20 18:33:51 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-20 18:33:52 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:33:52 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:33:52 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:33:52 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:33:52 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:33:52 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:33:53 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:33:53 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:33:54 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:33:54 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:33:54 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:33:54 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:33:54 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:33:54 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:33:54 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:33:54 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:33:54 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:33:54 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:33:55 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:33:55 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:33:56 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:33:56 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:33:56 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:33:56 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-20 18:33:57 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-20 18:33:59 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-20 18:33:59 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-20 18:34:01 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-20 18:34:01 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-20 18:34:01 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-20 18:34:01 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-20 18:34:03 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-20 18:34:03 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-20 18:34:04 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-20 18:34:04 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-20 18:34:10 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-20 18:34:10 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-20 18:34:18 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-06-20 18:34:18 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-06-20 18:34:19 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-06-20 18:34:19 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-06-20 18:34:19 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-06-20 18:34:19 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-06-20 18:34:25 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-20 18:34:25 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-20 18:34:32 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-20 18:34:32 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-20 18:34:37 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-20 18:34:37 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-20 18:35:00 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-20 18:35:00 - DEBUG UnitTestFramework: '#setup: 'skip''

2017-06-20 18:35:01 - DEBUG UnitTestFramework: '#setup ok: 'skip''

2017-06-20 18:35:01 - DEBUG UnitTestFramework: '#run: 'skip''

2017-06-20 18:35:01 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 18:35:01 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 18:35:01 - INFO Socket: 'run skipped, test: 'skip', event: 'run_skip''

2017-06-20 18:35:01 - DEBUG UnitTestFramework: '#run ok: 'skip''

2017-06-20 18:35:01 - DEBUG UnitTestFramework: '#teardown: 'skip''

2017-06-20 18:35:02 - DEBUG UnitTestFramework: '#teardown ok: 'skip''

2017-06-20 18:35:02 - DEBUG UnitTestFramework: '#setup: 'another skip''

2017-06-20 18:35:02 - DEBUG UnitTestFramework: '#setup ok: 'another skip''

2017-06-20 18:35:02 - DEBUG UnitTestFramework: '#run: 'another skip''

2017-06-20 18:35:03 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 18:35:04 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 18:35:05 - INFO Socket: 'run skipped, test: 'another skip', event: 'run_another skip''

2017-06-20 18:35:05 - DEBUG UnitTestFramework: '#run ok: 'another skip''

2017-06-20 18:35:05 - DEBUG UnitTestFramework: '#teardown: 'another skip''

2017-06-20 18:35:11 - DEBUG UnitTestFramework: '#teardown ok: 'another skip''

2017-06-20 18:35:11 - DEBUG UnitTestFramework: '#setup: 'skip with skip function''

2017-06-20 18:35:13 - DEBUG UnitTestFramework: '#setup ok: 'skip with skip function''

2017-06-20 18:35:13 - DEBUG UnitTestFramework: '#run: 'skip with skip function''

2017-06-20 18:35:14 - INFO Socket: 'run skipped, test: 'skip with skip function', event: 'run_skip with skip function''

2017-06-20 18:35:14 - INFO Socket: 'run skipped, test: 'skip with skip function', event: 'run_skip with skip function''

2017-06-20 18:35:15 - INFO Socket: 'run skipped, test: 'skip with skip function', event: 'run_skip with skip function''

2017-06-20 18:35:15 - DEBUG UnitTestFramework: '#run ok: 'skip with skip function''

2017-06-20 18:35:15 - DEBUG UnitTestFramework: '#teardown: 'skip with skip function''

2017-06-20 18:35:26 - DEBUG UnitTestFramework: '#teardown ok: 'skip with skip function''

2017-06-20 18:35:26 - DEBUG UnitTestFramework: '#setup: 'skip function''

2017-06-20 18:35:28 - DEBUG UnitTestFramework: '#setup ok: 'skip function''

2017-06-20 18:35:28 - DEBUG UnitTestFramework: '#run: 'skip function''

2017-06-20 18:35:29 - INFO Socket: 'run skipped, test: 'skip function', event: 'run_skip function''

2017-06-20 18:35:30 - INFO Socket: 'run skipped, test: 'skip function', event: 'run_skip function''

2017-06-20 18:35:51 - INFO Socket: 'run skipped, test: 'skip function', event: 'run_skip function''

2017-06-20 18:35:51 - DEBUG UnitTestFramework: '#run ok: 'skip function''

2017-06-20 18:35:51 - DEBUG UnitTestFramework: '#teardown: 'skip function''

2017-06-20 18:35:52 - DEBUG UnitTestFramework: '#teardown ok: 'skip function''

2017-06-20 18:35:52 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-20 18:35:52 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-20 18:35:52 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-20 18:35:52 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-20 18:35:52 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-20 18:35:53 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-20 18:35:53 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-20 18:35:57 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-20 18:35:57 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-20 18:36:18 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-20 18:36:18 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-20 18:36:33 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-20 18:36:33 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-20 18:36:44 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-20 18:36:44 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-20 18:37:00 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-20 18:37:00 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-20 18:37:10 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-20 18:37:10 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-20 18:37:10 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-20 18:37:10 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-20 18:37:11 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-20 18:37:11 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-20 18:37:12 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-20 18:37:12 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-20 18:37:13 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-20 18:37:13 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-20 18:37:14 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-20 18:37:14 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-20 18:37:19 - ERROR UnitTestFramework: '#run failed: 'Can shift data', error: 'TimeoutError: timeout exceeded, event: 'run_Can shift data_finished', test: 'Can shift data'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can shift data_finished', test: 'Can shift data'
    at afterTimeout (/home/pi/Test/server_12650373415b391b/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_12650373415b391b/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-20 18:37:19 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_Can shift data_finished', test: 'Can shift data'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can shift data_finished', test: 'Can shift data'
    at afterTimeout (/home/pi/Test/server_12650373415b391b/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_12650373415b391b/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-20 18:37:23 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-20 18:37:23 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-20 18:37:25 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-20 18:37:25 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-20 18:37:25 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-20 18:37:25 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-20 18:37:27 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-20 18:37:27 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-20 18:37:28 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-20 18:37:28 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-20 18:37:30 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-20 18:37:30 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-20 18:37:31 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-20 18:37:31 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-20 18:37:31 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-20 18:37:31 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-20 18:37:31 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-20 18:37:31 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-20 18:37:31 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-20 18:37:31 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-20 18:37:31 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-20 18:37:32 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-20 18:37:32 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-20 18:37:33 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-20 18:37:33 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-20 18:37:33 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-20 18:37:34 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-20 18:37:52 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-20 18:37:52 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-20 18:37:52 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-20 18:38:01 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-20 18:38:01 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:38:02 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:38:02 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:38:26 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:38:26 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:38:29 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-20 18:38:29 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:38:47 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:38:47 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:38:54 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:38:54 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:39:13 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-20 18:39:13 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:39:14 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:39:14 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:39:16 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:39:16 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:39:19 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-20 18:39:19 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:39:20 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:39:20 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:39:37 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:39:37 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:39:39 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-20 18:39:39 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:39:40 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:39:40 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:40:04 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:40:04 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:40:41 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-20 18:40:41 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:40:46 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:40:46 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:40:47 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:40:47 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:40:48 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-20 18:40:48 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-20 18:40:49 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-20 18:40:49 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-20 18:41:01 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-20 18:41:01 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-20 18:41:04 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-20 18:41:04 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-20 18:41:25 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-20 18:41:25 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-20 18:44:25 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_12650373415b391b/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_12650373415b391b/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-20 18:44:25 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_12650373415b391b/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_12650373415b391b/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-20 18:44:27 - DEBUG TestServer: 'completed'

2017-06-20 18:44:27 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-06-20 18:44:27 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-06-20 18:44:27 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-06-20 18:44:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-20 18:44:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-06-20 18:44:27 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
20/6/2017@20:27:14 Getting the list of iOS devices 
20/6/2017@20:27:15 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
20/6/2017@20:27:15 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
20/6/2017@20:27:15 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
20/6/2017@20:27:15 Deploying iOS test app 
20/6/2017@20:27:15 uninstalling the application 
20/6/2017@20:27:16 installing the application 
20/6/2017@20:50:34 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
20/6/2017@20:50:34 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
20/6/2017@20:50:34 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/12650373415b391b_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/thali03_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/12650373415b391b_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/thali04_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/12650373415b391b_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/12650373415b391b_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/12650373415b391b_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/12650373415b391b_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/12650373415b391b_Added_skip_function_to_allow_a_test_to_be_skipped_over_jareksl/iOS_server.md)





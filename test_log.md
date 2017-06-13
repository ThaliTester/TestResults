#### Test 1248535460c4faef Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 2 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-06-13 13:23:56 - INFO HttpServer: 'listening on *:3000'

2017-06-13 13:23:59 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '9d162a14-e2b5-4f1d-9c15-c0c413049d6b', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-13 13:23:59 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-06-13 13:24:00 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '61906ab6-b3e8-4b04-80d3-60574fe23967', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-13 13:24:00 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-06-13 13:24:00 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c2b636ca-3232-49ca-8f71-66b1c45a9900', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-13 13:24:00 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-06-13 13:24:00 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-06-13 13:24:00 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-06-13 13:24:00 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-13 13:24:00 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '9d162a14-e2b5-4f1d-9c15-c0c413049d6b', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-13 13:24:00 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '9d162a14-e2b5-4f1d-9c15-c0c413049d6b', platformName: 'ios''

2017-06-13 13:24:02 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '61906ab6-b3e8-4b04-80d3-60574fe23967', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-13 13:24:02 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: '61906ab6-b3e8-4b04-80d3-60574fe23967', platformName: 'ios''

2017-06-13 13:24:02 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: 'c2b636ca-3232-49ca-8f71-66b1c45a9900', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-13 13:24:02 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: 'c2b636ca-3232-49ca-8f71-66b1c45a9900', platformName: 'ios''

2017-06-13 13:24:05 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-13 13:24:05 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-13 13:24:08 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-13 13:24:08 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-13 13:24:09 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-13 13:24:09 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-13 13:24:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-13 13:24:10 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-13 13:24:10 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-13 13:24:10 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-13 13:24:12 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-13 13:24:12 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-13 13:24:12 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-13 13:24:12 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:24:13 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:24:13 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:24:13 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:24:13 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:24:14 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:24:14 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:24:14 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:24:14 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:24:14 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:24:14 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:24:14 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:24:14 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:24:15 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:24:15 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:24:15 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-13 13:24:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-13 13:24:16 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-13 13:24:16 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:24:16 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:24:17 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:24:17 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:24:17 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:24:17 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:24:17 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:24:18 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:24:18 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:24:18 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:24:18 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:24:18 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''
2017-06-13 13:24:18 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:24:18 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:24:18 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:24:18 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:24:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:24:19 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:24:19 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:24:19 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:24:19 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:24:19 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:24:20 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:24:20 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:24:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:24:20 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:24:21 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:24:21 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:24:21 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:24:22 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:24:22 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-13 13:24:25 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-13 13:24:25 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-13 13:24:26 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-13 13:24:26 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-13 13:24:27 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-13 13:24:27 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-13 13:24:27 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-13 13:24:27 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-13 13:24:28 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-13 13:24:28 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-13 13:24:38 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-13 13:24:38 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-13 13:24:45 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-13 13:24:45 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-13 13:24:51 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-13 13:24:51 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-13 13:24:56 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-13 13:24:56 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-13 13:25:06 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-13 13:25:06 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-13 13:25:07 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-13 13:25:07 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-13 13:25:08 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-13 13:25:08 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-13 13:25:16 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '99dc16f2-51de-4277-a5a6-93371701ddea', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-13 13:25:16 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-06-13 13:25:17 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-13 13:25:17 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-13 13:25:22 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-13 13:25:22 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-13 13:25:26 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '410efc13-6b54-4b94-9460-f1f63e9d90f6', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-13 13:25:26 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-06-13 13:25:30 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-13 13:25:30 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-13 13:25:31 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-13 13:25:31 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-13 13:25:42 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-13 13:25:42 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-13 13:25:47 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-13 13:25:47 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-13 13:26:10 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-13 13:26:10 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-13 13:26:10 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-13 13:26:10 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-13 13:26:11 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-13 13:26:11 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-13 13:26:14 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-13 13:26:14 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-13 13:26:20 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-13 13:26:20 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-13 13:26:32 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-13 13:26:32 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-13 13:26:33 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-13 13:26:33 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-13 13:26:33 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-13 13:26:33 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-13 13:26:34 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-13 13:26:34 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-13 13:26:35 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-13 13:26:35 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-13 13:26:35 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-13 13:26:35 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-13 13:26:38 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-13 13:26:38 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-13 13:27:00 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-13 13:27:00 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-13 13:27:09 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-13 13:27:09 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-13 13:27:19 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-13 13:27:19 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-13 13:27:25 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '8caca416-6cf7-4801-a9bd-b9801dcf62b7', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-06-13 13:27:25 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''
2017-06-13 13:27:25 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-06-13 13:27:25 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-06-13 13:27:25 - DEBUG UnitTestFramework: 'scheduling tests'

2017-06-13 13:27:26 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-13 13:27:26 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-13 13:27:26 - DEBUG UnitTestFramework: 'tests scheduled'

2017-06-13 13:27:26 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-06-13 13:27:44 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-13 13:27:44 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-13 13:27:45 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-06-13 13:27:45 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:27:46 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:27:47 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:27:47 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:27:47 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-06-13 13:27:47 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:27:47 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:27:47 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:27:47 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:27:47 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:27:48 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-06-13 13:27:48 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:27:48 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:27:48 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:27:48 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-13 13:27:48 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-13 13:27:48 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-06-13 13:27:48 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:27:48 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:27:49 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:27:49 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:27:49 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:27:49 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:27:49 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:27:49 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:27:49 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:27:49 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:27:49 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-06-13 13:27:49 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-06-13 13:27:50 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run: 'basic''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#setup: 'another''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run: 'another''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox spy''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox spy''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox spy''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox spy''

2017-06-13 13:27:51 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox spy''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox spy''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox stub override''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-13 13:27:52 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-13 13:27:56 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox stub override''

2017-06-13 13:27:56 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox stub override''

2017-06-13 13:27:57 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-13 13:27:57 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-13 13:27:57 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-13 13:27:57 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-13 13:27:58 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox stub override''

2017-06-13 13:27:58 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox stub override''

2017-06-13 13:27:58 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-13 13:27:58 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-13 13:27:59 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-13 13:27:59 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-13 13:28:00 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-13 13:28:00 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-13 13:28:03 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-13 13:28:03 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-13 13:28:03 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-13 13:28:03 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-13 13:28:05 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-13 13:28:05 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-13 13:28:06 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-13 13:28:06 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-13 13:28:07 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-13 13:28:07 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-13 13:28:08 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox stub override''

2017-06-13 13:28:08 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox mock''

2017-06-13 13:28:08 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-13 13:28:08 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-13 13:28:10 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-13 13:28:10 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-13 13:28:11 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-13 13:28:11 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-13 13:28:12 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-13 13:28:12 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-13 13:28:13 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-13 13:28:13 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-13 13:28:16 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-13 13:28:16 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-13 13:28:28 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-13 13:28:28 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:28:31 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:28:31 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:28:32 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:28:32 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:28:32 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:28:32 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:28:34 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:28:34 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:28:34 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:28:34 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:28:35 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox mock''

2017-06-13 13:28:35 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox mock''

2017-06-13 13:28:35 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:28:35 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:28:36 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:28:36 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:28:36 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:28:36 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:28:36 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:28:36 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:28:36 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:28:36 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:28:37 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:28:37 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:28:37 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:28:37 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:28:37 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:28:37 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:28:38 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:28:38 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:28:38 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:28:38 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:28:39 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:28:39 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:28:39 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:28:39 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:28:39 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:28:39 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-13 13:28:39 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-13 13:28:39 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-13 13:28:41 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-13 13:28:41 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-13 13:28:42 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-13 13:28:42 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-13 13:28:42 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-13 13:28:42 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-13 13:28:46 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox mock''

2017-06-13 13:28:46 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox mock''

2017-06-13 13:28:52 - DEBUG UnitTestFramework: '#run ok: 'Can connect to a remote peer''

2017-06-13 13:28:52 - DEBUG UnitTestFramework: '#teardown: 'Can connect to a remote peer''

2017-06-13 13:28:53 - DEBUG UnitTestFramework: '#teardown ok: 'Can connect to a remote peer''

2017-06-13 13:28:53 - DEBUG UnitTestFramework: '#setup: 'Can shift data''

2017-06-13 13:28:53 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data''

2017-06-13 13:28:53 - DEBUG UnitTestFramework: '#run: 'Can shift data''

2017-06-13 13:29:05 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox mock''

2017-06-13 13:29:05 - DEBUG UnitTestFramework: '#setup: 'test sinon sansbox restore after test end''

2017-06-13 13:29:06 - DEBUG UnitTestFramework: '#setup ok: 'test sinon sansbox restore after test end''

2017-06-13 13:29:06 - DEBUG UnitTestFramework: '#run: 'test sinon sansbox restore after test end''

2017-06-13 13:29:18 - DEBUG UnitTestFramework: '#run ok: 'test sinon sansbox restore after test end''

2017-06-13 13:29:18 - DEBUG UnitTestFramework: '#teardown: 'test sinon sansbox restore after test end''

2017-06-13 13:29:20 - DEBUG UnitTestFramework: '#teardown ok: 'test sinon sansbox restore after test end''

2017-06-13 13:29:20 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-06-13 13:29:23 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-06-13 13:29:23 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-06-13 13:29:23 - DEBUG UnitTestFramework: '#run ok: 'Can shift data''

2017-06-13 13:29:23 - DEBUG UnitTestFramework: '#teardown: 'Can shift data''

2017-06-13 13:29:24 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data''

2017-06-13 13:29:24 - DEBUG UnitTestFramework: '#setup: 'Can shift data via parallel connections''

2017-06-13 13:29:24 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-06-13 13:29:24 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-06-13 13:29:24 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data via parallel connections''

2017-06-13 13:29:24 - DEBUG UnitTestFramework: '#run: 'Can shift data via parallel connections''

2017-06-13 13:29:25 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-13 13:29:26 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-13 13:29:26 - INFO Socket: 'run skipped, test: 'Can shift data via parallel connections', event: 'run_Can shift data via parallel connections''

2017-06-13 13:29:26 - DEBUG UnitTestFramework: '#run ok: 'Can shift data via parallel connections''

2017-06-13 13:29:26 - DEBUG UnitTestFramework: '#teardown: 'Can shift data via parallel connections''

2017-06-13 13:29:28 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data via parallel connections''

2017-06-13 13:29:28 - DEBUG UnitTestFramework: '#setup: 'Can shift data securely''

2017-06-13 13:29:33 - DEBUG UnitTestFramework: '#setup ok: 'Can shift data securely''

2017-06-13 13:29:33 - DEBUG UnitTestFramework: '#run: 'Can shift data securely''

2017-06-13 13:29:39 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-06-13 13:29:39 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-06-13 13:29:40 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-06-13 13:29:40 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-06-13 13:29:40 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-06-13 13:29:41 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-06-13 13:29:43 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-06-13 13:29:43 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-06-13 13:29:44 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-06-13 13:29:44 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-06-13 13:29:45 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-13 13:29:45 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-13 13:29:45 - DEBUG UnitTestFramework: '#run ok: 'Can shift data securely''

2017-06-13 13:29:45 - DEBUG UnitTestFramework: '#teardown: 'Can shift data securely''

2017-06-13 13:29:45 - INFO Socket: 'run skipped, test: 'onPeerLost calls jxcore', event: 'run_onPeerLost calls jxcore''

2017-06-13 13:29:45 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2017-06-13 13:29:45 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2017-06-13 13:29:46 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift data securely''

2017-06-13 13:29:46 - DEBUG UnitTestFramework: '#setup: 'Can shift large amounts of data''

2017-06-13 13:29:48 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2017-06-13 13:29:48 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2017-06-13 13:29:48 - DEBUG UnitTestFramework: '#setup ok: 'Can shift large amounts of data''

2017-06-13 13:29:48 - DEBUG UnitTestFramework: '#run: 'Can shift large amounts of data''

2017-06-13 13:29:53 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2017-06-13 13:29:53 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2017-06-13 13:29:53 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-13 13:29:54 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-13 13:29:56 - INFO Socket: 'run skipped, test: 'onPeerDiscovered calls jxcore', event: 'run_onPeerDiscovered calls jxcore''

2017-06-13 13:29:56 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2017-06-13 13:29:56 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2017-06-13 13:29:58 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2017-06-13 13:29:58 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:29:59 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:29:59 - DEBUG UnitTestFramework: '#run: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:30:01 - DEBUG UnitTestFramework: '#run ok: 'Can shift large amounts of data''

2017-06-13 13:30:01 - DEBUG UnitTestFramework: '#teardown: 'Can shift large amounts of data''

2017-06-13 13:30:01 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:30:01 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:30:02 - DEBUG UnitTestFramework: '#teardown ok: 'Can shift large amounts of data''

2017-06-13 13:30:02 - DEBUG UnitTestFramework: '#setup: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-13 13:30:03 - DEBUG UnitTestFramework: '#setup ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-13 13:30:03 - DEBUG UnitTestFramework: '#run: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-13 13:30:04 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopListeningForAdvertisements''

2017-06-13 13:30:04 - DEBUG UnitTestFramework: '#setup: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:30:08 - DEBUG UnitTestFramework: '#setup ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:30:08 - DEBUG UnitTestFramework: '#run: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:30:10 - DEBUG UnitTestFramework: '#run ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-13 13:30:10 - DEBUG UnitTestFramework: '#teardown: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-13 13:30:11 - DEBUG UnitTestFramework: '#run ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:30:11 - DEBUG UnitTestFramework: '#teardown: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:30:11 - DEBUG UnitTestFramework: '#teardown ok: 'We do not emit peerAvailabilityChanged events until one of the start methods is called''

2017-06-13 13:30:11 - DEBUG UnitTestFramework: '#setup: 'Test updating advertising and parallel data transfer''

2017-06-13 13:30:12 - DEBUG UnitTestFramework: '#setup ok: 'Test updating advertising and parallel data transfer''

2017-06-13 13:30:12 - DEBUG UnitTestFramework: '#run: 'Test updating advertising and parallel data transfer''

2017-06-13 13:30:12 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-13 13:30:12 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-13 13:30:12 - INFO Socket: 'run skipped, test: 'Test updating advertising and parallel data transfer', event: 'run_Test updating advertising and parallel data transfer''

2017-06-13 13:30:12 - DEBUG UnitTestFramework: '#run ok: 'Test updating advertising and parallel data transfer''

2017-06-13 13:30:12 - DEBUG UnitTestFramework: '#teardown: 'Test updating advertising and parallel data transfer''

2017-06-13 13:30:12 - DEBUG UnitTestFramework: '#teardown ok: 'Test updating advertising and parallel data transfer''

2017-06-13 13:30:12 - DEBUG UnitTestFramework: '#setup: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-13 13:30:13 - DEBUG UnitTestFramework: '#setup ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-13 13:30:13 - DEBUG UnitTestFramework: '#run: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-13 13:30:13 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startListeningForAdvertisements twice is NOT an error''

2017-06-13 13:30:13 - DEBUG UnitTestFramework: '#setup: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:30:17 - DEBUG UnitTestFramework: '#run ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-13 13:30:17 - DEBUG UnitTestFramework: '#teardown: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-13 13:30:18 - DEBUG UnitTestFramework: '#teardown ok: 'discoveryAdvertisingStateUpdateNonTCP is called''

2017-06-13 13:30:18 - DEBUG UnitTestFramework: '#setup: 'cannot call connect when start listening for advertisements is not active''

2017-06-13 13:30:18 - DEBUG UnitTestFramework: '#setup ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-13 13:30:18 - DEBUG UnitTestFramework: '#run: 'cannot call connect when start listening for advertisements is not active''

2017-06-13 13:30:18 - DEBUG UnitTestFramework: '#run ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-13 13:30:18 - DEBUG UnitTestFramework: '#teardown: 'cannot call connect when start listening for advertisements is not active''

2017-06-13 13:30:18 - DEBUG UnitTestFramework: '#teardown ok: 'cannot call connect when start listening for advertisements is not active''

2017-06-13 13:30:18 - DEBUG UnitTestFramework: '#setup: 'Get error when trying to double connect to a peer on Android''

2017-06-13 13:30:18 - DEBUG UnitTestFramework: '#setup ok: 'Get error when trying to double connect to a peer on Android''

2017-06-13 13:30:18 - DEBUG UnitTestFramework: '#run: 'Get error when trying to double connect to a peer on Android''

2017-06-13 13:30:22 - DEBUG UnitTestFramework: '#setup ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:30:22 - DEBUG UnitTestFramework: '#run: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:30:23 - DEBUG UnitTestFramework: '#run ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:30:23 - DEBUG UnitTestFramework: '#teardown: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:30:24 - DEBUG UnitTestFramework: '#teardown ok: 'Calling stopListeningForAdvertisements without calling start is NOT an error''

2017-06-13 13:30:24 - DEBUG UnitTestFramework: '#setup: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:30:26 - DEBUG UnitTestFramework: '#setup ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:30:26 - DEBUG UnitTestFramework: '#run: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:30:27 - DEBUG UnitTestFramework: '#run ok: 'Get error when trying to double connect to a peer on Android''

2017-06-13 13:30:27 - DEBUG UnitTestFramework: '#teardown: 'Get error when trying to double connect to a peer on Android''

2017-06-13 13:30:28 - DEBUG UnitTestFramework: '#teardown ok: 'Get error when trying to double connect to a peer on Android''

2017-06-13 13:30:28 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-13 13:30:28 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-13 13:30:28 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-13 13:30:29 - DEBUG UnitTestFramework: '#run ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:30:29 - DEBUG UnitTestFramework: '#teardown: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:30:36 - DEBUG UnitTestFramework: '#teardown ok: 'Can call start/stopUpdateAdvertisingAndListening''

2017-06-13 13:30:36 - DEBUG UnitTestFramework: '#setup: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:30:38 - DEBUG UnitTestFramework: '#setup ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:30:38 - DEBUG UnitTestFramework: '#run: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:30:41 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-13 13:30:41 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-13 13:30:41 - DEBUG UnitTestFramework: '#run ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:30:41 - DEBUG UnitTestFramework: '#teardown: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:30:42 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''

2017-06-13 13:30:42 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-13 13:30:43 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-13 13:30:43 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-13 13:30:50 - DEBUG UnitTestFramework: '#teardown ok: 'Calling startUpdateAdvertisingAndListening twice is NOT an error''

2017-06-13 13:30:50 - DEBUG UnitTestFramework: '#setup: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:31:08 - DEBUG UnitTestFramework: '#setup ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:31:08 - DEBUG UnitTestFramework: '#run: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:31:18 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-13 13:31:18 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-13 13:31:36 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''

2017-06-13 13:31:36 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-13 13:31:38 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-13 13:31:38 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-13 13:31:53 - DEBUG UnitTestFramework: '#run ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:31:53 - DEBUG UnitTestFramework: '#teardown: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:31:54 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-13 13:31:54 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-13 13:31:55 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''

2017-06-13 13:31:55 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-13 13:31:55 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-13 13:31:55 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-13 13:31:56 - DEBUG UnitTestFramework: '#teardown ok: 'Can call stopUpdateAdvertisingAndListening twice without start and it is not an error''

2017-06-13 13:31:56 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChange is called''

2017-06-13 13:31:58 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChange is called''

2017-06-13 13:31:58 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChange is called''

2017-06-13 13:32:05 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChange is called''

2017-06-13 13:32:05 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChange is called''

2017-06-13 13:32:11 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChange is called''

2017-06-13 13:32:11 - DEBUG UnitTestFramework: '#setup: 'Can connect to a remote peer''

2017-06-13 13:32:14 - DEBUG UnitTestFramework: '#setup ok: 'Can connect to a remote peer''

2017-06-13 13:32:14 - DEBUG UnitTestFramework: '#run: 'Can connect to a remote peer''

2017-06-13 13:32:24 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-13 13:32:24 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#setup: 'initial peer discovery''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#setup ok: 'initial peer discovery''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#run: 'initial peer discovery''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'initial peer discovery', event: 'run_initial peer discovery''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#run ok: 'initial peer discovery''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#teardown: 'initial peer discovery''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#teardown ok: 'initial peer discovery''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 1''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 1''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#run: 'update peer discovery 1''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'update peer discovery 1', event: 'run_update peer discovery 1''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 1''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 1''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 1''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#setup: 'update peer discovery 2''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#setup ok: 'update peer discovery 2''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#run: 'update peer discovery 2''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'update peer discovery 2', event: 'run_update peer discovery 2''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#run ok: 'update peer discovery 2''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#teardown: 'update peer discovery 2''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#teardown ok: 'update peer discovery 2''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#setup: 'check latest peer discovery''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#setup ok: 'check latest peer discovery''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#run: 'check latest peer discovery''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-06-13 13:32:25 - INFO Socket: 'run skipped, test: 'check latest peer discovery', event: 'run_check latest peer discovery''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#run ok: 'check latest peer discovery''

2017-06-13 13:32:25 - DEBUG UnitTestFramework: '#teardown: 'check latest peer discovery''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#teardown ok: 'check latest peer discovery''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#setup: 'Set up for no peer discovery test''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#setup ok: 'Set up for no peer discovery test''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#run: 'Set up for no peer discovery test''

2017-06-13 13:32:26 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-06-13 13:32:26 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-06-13 13:32:26 - INFO Socket: 'run skipped, test: 'Set up for no peer discovery test', event: 'run_Set up for no peer discovery test''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#run ok: 'Set up for no peer discovery test''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#teardown: 'Set up for no peer discovery test''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#teardown ok: 'Set up for no peer discovery test''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#setup: 'no peer discovery''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#setup ok: 'no peer discovery''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#run: 'no peer discovery''

2017-06-13 13:32:26 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-06-13 13:32:26 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-06-13 13:32:26 - INFO Socket: 'run skipped, test: 'no peer discovery', event: 'run_no peer discovery''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#run ok: 'no peer discovery''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#teardown: 'no peer discovery''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#teardown ok: 'no peer discovery''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2017-06-13 13:32:26 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2017-06-13 13:32:27 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-13 13:32:28 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-13 13:32:29 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-13 13:32:30 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-13 13:32:30 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-13 13:32:30 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2017-06-13 13:32:30 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-13 13:32:30 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-13 13:32:30 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-13 13:32:30 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-13 13:32:30 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#setup: 'can create servers manager''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#setup ok: 'can create servers manager''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#run: 'can create servers manager''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#run ok: 'can create servers manager''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#teardown: 'can create servers manager''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#teardown ok: 'can create servers manager''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#setup: 'calling stop without start causes error''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#setup ok: 'calling stop without start causes error''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#run: 'calling stop without start causes error''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#run ok: 'calling stop without start causes error''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#teardown: 'calling stop without start causes error''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#teardown ok: 'calling stop without start causes error''

2017-06-13 13:32:31 - DEBUG UnitTestFramework: '#setup: 'can start/stop servers manager''

2017-06-13 13:32:32 - DEBUG UnitTestFramework: '#setup ok: 'can start/stop servers manager''

2017-06-13 13:32:32 - DEBUG UnitTestFramework: '#run: 'can start/stop servers manager''

2017-06-13 13:32:36 - DEBUG UnitTestFramework: '#run ok: 'can start/stop servers manager''

2017-06-13 13:32:36 - DEBUG UnitTestFramework: '#teardown: 'can start/stop servers manager''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#teardown ok: 'can start/stop servers manager''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#setup: 'starting twice resolves with listening port''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#setup ok: 'starting twice resolves with listening port''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#run: 'starting twice resolves with listening port''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#run ok: 'starting twice resolves with listening port''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#teardown: 'starting twice resolves with listening port''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#teardown ok: 'starting twice resolves with listening port''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#setup: 'terminateIncomingConnection will terminate a connection''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#setup ok: 'terminateIncomingConnection will terminate a connection''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#run: 'terminateIncomingConnection will terminate a connection''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#run ok: 'terminateIncomingConnection will terminate a connection''

2017-06-13 13:32:41 - DEBUG UnitTestFramework: '#teardown: 'terminateIncomingConnection will terminate a connection''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#teardown ok: 'terminateIncomingConnection will terminate a connection''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#setup: 'terminate an Outgoing connection''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#setup ok: 'terminate an Outgoing connection''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#run: 'terminate an Outgoing connection''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#run ok: 'terminate an Outgoing connection''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#teardown: 'terminate an Outgoing connection''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#teardown ok: 'terminate an Outgoing connection''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:32:42 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:32:43 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:32:43 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:32:43 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:32:43 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:32:43 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:32:43 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:32:44 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:32:44 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:32:44 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:32:44 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:32:44 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:32:44 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:32:44 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:32:44 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:32:44 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:32:44 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:32:45 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:32:45 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:32:46 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:32:46 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:32:46 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:32:46 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:32:47 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:32:47 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:32:48 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:32:48 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:32:48 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:32:48 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:32:48 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:32:48 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#setup: 'can get the network status before starting''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status before starting''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#run: 'can get the network status before starting''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#run ok: 'can get the network status before starting''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#teardown: 'can get the network status before starting''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status before starting''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#setup: 'error returned with bad router''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#setup ok: 'error returned with bad router''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#run: 'error returned with bad router''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#run ok: 'error returned with bad router''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#teardown: 'error returned with bad router''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#teardown ok: 'error returned with bad router''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#setup: 'all services are started when we call start''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#setup ok: 'all services are started when we call start''

2017-06-13 13:32:49 - DEBUG UnitTestFramework: '#run: 'all services are started when we call start''

2017-06-13 13:32:51 - DEBUG UnitTestFramework: '#run ok: 'all services are started when we call start''

2017-06-13 13:32:51 - DEBUG UnitTestFramework: '#teardown: 'all services are started when we call start''

2017-06-13 13:32:52 - DEBUG UnitTestFramework: '#teardown ok: 'all services are started when we call start''

2017-06-13 13:32:52 - DEBUG UnitTestFramework: '#setup: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-13 13:32:53 - DEBUG UnitTestFramework: '#setup ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-13 13:32:53 - DEBUG UnitTestFramework: '#run: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-13 13:32:53 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-06-13 13:32:53 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-06-13 13:32:53 - INFO Socket: 'run skipped, test: 'TCP Servers Manager should be null when we call start on iOS', event: 'run_TCP Servers Manager should be null when we call start on iOS''

2017-06-13 13:32:53 - DEBUG UnitTestFramework: '#run ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-13 13:32:53 - DEBUG UnitTestFramework: '#teardown: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-13 13:32:54 - DEBUG UnitTestFramework: '#teardown ok: 'TCP Servers Manager should be null when we call start on iOS''

2017-06-13 13:32:54 - DEBUG UnitTestFramework: '#setup: 'all services are stopped when we call stop''

2017-06-13 13:33:01 - DEBUG UnitTestFramework: '#setup ok: 'all services are stopped when we call stop''

2017-06-13 13:33:01 - DEBUG UnitTestFramework: '#run: 'all services are stopped when we call stop''

2017-06-13 13:33:04 - DEBUG UnitTestFramework: '#run ok: 'all services are stopped when we call stop''

2017-06-13 13:33:04 - DEBUG UnitTestFramework: '#teardown: 'all services are stopped when we call stop''

2017-06-13 13:33:27 - DEBUG UnitTestFramework: '#teardown ok: 'all services are stopped when we call stop''

2017-06-13 13:33:27 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is properly hooked up''

2017-06-13 13:33:31 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is properly hooked up''

2017-06-13 13:33:31 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is properly hooked up''

2017-06-13 13:33:33 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is properly hooked up''

2017-06-13 13:33:33 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is properly hooked up''

2017-06-13 13:33:36 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is properly hooked up''

2017-06-13 13:33:36 - DEBUG UnitTestFramework: '#setup: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#run: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-13 13:33:59 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-06-13 13:33:59 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-06-13 13:33:59 - INFO Socket: 'run skipped, test: 'make sure terminateConnection is return error if we get called on iOS', event: 'run_make sure terminateConnection is return error if we get called on iOS''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateConnection is return error if we get called on iOS''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is properly hooked up''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is properly hooked up''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is properly hooked up''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is properly hooked up''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is properly hooked up''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is properly hooked up''

2017-06-13 13:33:59 - DEBUG UnitTestFramework: '#setup: 'make sure terminateListener is return error if we get called on iOS''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#setup ok: 'make sure terminateListener is return error if we get called on iOS''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#run: 'make sure terminateListener is return error if we get called on iOS''

2017-06-13 13:34:00 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-06-13 13:34:00 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-06-13 13:34:00 - INFO Socket: 'run skipped, test: 'make sure terminateListener is return error if we get called on iOS', event: 'run_make sure terminateListener is return error if we get called on iOS''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#run ok: 'make sure terminateListener is return error if we get called on iOS''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#teardown: 'make sure terminateListener is return error if we get called on iOS''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#teardown ok: 'make sure terminateListener is return error if we get called on iOS''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#setup: 'make sure we actually call kill connections properly''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#setup ok: 'make sure we actually call kill connections properly''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#run: 'make sure we actually call kill connections properly''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#run ok: 'make sure we actually call kill connections properly''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#teardown: 'make sure we actually call kill connections properly''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#teardown ok: 'make sure we actually call kill connections properly''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#setup: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#setup ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#run: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:00 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:00 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:00 - INFO Socket: 'run skipped, test: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection', event: 'run_We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#run ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#teardown: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#teardown ok: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:00 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:01 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:01 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:01 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#setup: 'make sure bad PSK connections fail''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#setup ok: 'make sure bad PSK connections fail''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#run: 'make sure bad PSK connections fail''

2017-06-13 13:34:01 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-06-13 13:34:01 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-06-13 13:34:01 - INFO Socket: 'run skipped, test: 'make sure bad PSK connections fail', event: 'run_make sure bad PSK connections fail''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#run ok: 'make sure bad PSK connections fail''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#teardown: 'make sure bad PSK connections fail''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#teardown ok: 'make sure bad PSK connections fail''

2017-06-13 13:34:01 - DEBUG UnitTestFramework: '#setup: 'peer changes handled from a queue''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#setup ok: 'peer changes handled from a queue''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#run: 'peer changes handled from a queue''

2017-06-13 13:34:02 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-06-13 13:34:02 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-06-13 13:34:02 - INFO Socket: 'run skipped, test: 'peer changes handled from a queue', event: 'run_peer changes handled from a queue''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#run ok: 'peer changes handled from a queue''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#teardown: 'peer changes handled from a queue''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#teardown ok: 'peer changes handled from a queue''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#setup: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#setup ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#run: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-13 13:34:02 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-13 13:34:02 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-13 13:34:02 - INFO Socket: 'run skipped, test: 'relaying discoveryAdvertisingStateUpdateNonTCP', event: 'run_relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#run ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#teardown: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#teardown ok: 'relaying discoveryAdvertisingStateUpdateNonTCP''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#setup: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#setup ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#run: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-13 13:34:02 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-13 13:34:02 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-13 13:34:02 - INFO Socket: 'run skipped, test: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received', event: 'run_thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#run ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#teardown: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#teardown ok: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#setup: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#setup ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-06-13 13:34:02 - DEBUG UnitTestFramework: '#run: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#run ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#teardown: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#teardown ok: 'we successfully receive and replay discoveryAdvertisingStateUpdate''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#setup: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#setup ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#run: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-06-13 13:34:05 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-06-13 13:34:05 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-06-13 13:34:05 - INFO Socket: 'run skipped, test: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS', event: 'run_nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#run ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#teardown: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#teardown ok: 'nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#setup: 'can do HTTP requests between peers''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#setup ok: 'can do HTTP requests between peers''

2017-06-13 13:34:05 - DEBUG UnitTestFramework: '#run: 'can do HTTP requests between peers''

2017-06-13 13:34:18 - DEBUG UnitTestFramework: '#run ok: 'can do HTTP requests between peers''

2017-06-13 13:34:18 - DEBUG UnitTestFramework: '#teardown: 'can do HTTP requests between peers''

2017-06-13 13:34:18 - DEBUG UnitTestFramework: '#teardown ok: 'can do HTTP requests between peers''

2017-06-13 13:34:18 - DEBUG UnitTestFramework: '#setup: 'can still do HTTP requests between peers with coordinator''

2017-06-13 13:34:18 - DEBUG UnitTestFramework: '#setup ok: 'can still do HTTP requests between peers with coordinator''

2017-06-13 13:34:18 - DEBUG UnitTestFramework: '#run: 'can still do HTTP requests between peers with coordinator''

2017-06-13 13:34:26 - DEBUG UnitTestFramework: '#run ok: 'can still do HTTP requests between peers with coordinator''

2017-06-13 13:34:26 - DEBUG UnitTestFramework: '#teardown: 'can still do HTTP requests between peers with coordinator''

2017-06-13 13:34:27 - DEBUG UnitTestFramework: '#teardown ok: 'can still do HTTP requests between peers with coordinator''

2017-06-13 13:34:27 - DEBUG UnitTestFramework: '#setup: 'calls correct starts when network changes''

2017-06-13 13:34:27 - DEBUG UnitTestFramework: '#setup ok: 'calls correct starts when network changes''

2017-06-13 13:34:27 - DEBUG UnitTestFramework: '#run: 'calls correct starts when network changes''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#run ok: 'calls correct starts when network changes''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#teardown: 'calls correct starts when network changes''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#teardown ok: 'calls correct starts when network changes''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#setup: 'test to coordinate connection cut''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#setup ok: 'test to coordinate connection cut''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#run: 'test to coordinate connection cut''

2017-06-13 13:34:31 - INFO Socket: 'run skipped, test: 'test to coordinate connection cut', event: 'run_test to coordinate connection cut''

2017-06-13 13:34:31 - INFO Socket: 'run skipped, test: 'test to coordinate connection cut', event: 'run_test to coordinate connection cut''

2017-06-13 13:34:31 - INFO Socket: 'run skipped, test: 'test to coordinate connection cut', event: 'run_test to coordinate connection cut''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#run ok: 'test to coordinate connection cut''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#teardown: 'test to coordinate connection cut''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#teardown ok: 'test to coordinate connection cut''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#setup: 'can do HTTP requests after connections are cut''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#setup ok: 'can do HTTP requests after connections are cut''

2017-06-13 13:34:31 - DEBUG UnitTestFramework: '#run: 'can do HTTP requests after connections are cut''

2017-06-13 13:34:31 - INFO Socket: 'run skipped, test: 'can do HTTP requests after connections are cut', event: 'run_can do HTTP requests after connections are cut''

2017-06-13 13:34:31 - INFO Socket: 'run skipped, test: 'can do HTTP requests after connections are cut', event: 'run_can do HTTP requests after connections are cut''

2017-06-13 13:34:32 - INFO Socket: 'run skipped, test: 'can do HTTP requests after connections are cut', event: 'run_can do HTTP requests after connections are cut''

2017-06-13 13:34:32 - DEBUG UnitTestFramework: '#run ok: 'can do HTTP requests after connections are cut''

2017-06-13 13:34:32 - DEBUG UnitTestFramework: '#teardown: 'can do HTTP requests after connections are cut''

2017-06-13 13:34:32 - DEBUG UnitTestFramework: '#teardown ok: 'can do HTTP requests after connections are cut''

2017-06-13 13:34:32 - DEBUG UnitTestFramework: '#setup: 'will fail bad PSK connection between peers''

2017-06-13 13:34:32 - DEBUG UnitTestFramework: '#setup ok: 'will fail bad PSK connection between peers''

2017-06-13 13:34:32 - DEBUG UnitTestFramework: '#run: 'will fail bad PSK connection between peers''

2017-06-13 13:34:32 - DEBUG UnitTestFramework: '#run ok: 'will fail bad PSK connection between peers''

2017-06-13 13:34:32 - DEBUG UnitTestFramework: '#teardown: 'will fail bad PSK connection between peers''

2017-06-13 13:34:32 - DEBUG UnitTestFramework: '#teardown ok: 'will fail bad PSK connection between peers''

2017-06-13 13:34:32 - DEBUG UnitTestFramework: '#setup: 'We provide notification when a listener dies and we recreate it''

2017-06-13 13:34:33 - DEBUG UnitTestFramework: '#setup ok: 'We provide notification when a listener dies and we recreate it''

2017-06-13 13:34:33 - DEBUG UnitTestFramework: '#run: 'We provide notification when a listener dies and we recreate it''

2017-06-13 13:34:46 - DEBUG UnitTestFramework: '#run ok: 'We provide notification when a listener dies and we recreate it''

2017-06-13 13:34:46 - DEBUG UnitTestFramework: '#teardown: 'We provide notification when a listener dies and we recreate it''

2017-06-13 13:34:46 - DEBUG UnitTestFramework: '#teardown ok: 'We provide notification when a listener dies and we recreate it''

2017-06-13 13:34:46 - DEBUG UnitTestFramework: '#setup: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-06-13 13:34:46 - DEBUG UnitTestFramework: '#setup ok: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-06-13 13:34:46 - DEBUG UnitTestFramework: '#run: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-06-13 13:34:46 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-06-13 13:34:46 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-06-13 13:34:47 - INFO Socket: 'run skipped, test: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated', event: 'run_We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#run ok: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#teardown: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#teardown ok: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#setup: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#setup ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#run: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#run ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#teardown: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#teardown ok: '#startListeningForAdvertisements should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#setup: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#setup ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#run: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#run ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#teardown: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#teardown ok: '#startUpdateAdvertisingAndListening should fail if start not called''

2017-06-13 13:34:47 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:34:48 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:34:48 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:34:48 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:34:48 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:34:48 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopListeningForAdvertisements many times''

2017-06-13 13:34:48 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:34:48 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:34:48 - DEBUG UnitTestFramework: '#run: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:34:49 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:34:49 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:34:49 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startListeningForAdvertisements many times''

2017-06-13 13:34:49 - DEBUG UnitTestFramework: '#setup: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:34:50 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:34:50 - DEBUG UnitTestFramework: '#run: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:34:51 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:34:51 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:34:51 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #startUpdateAdvertisingAndListening many times''

2017-06-13 13:34:51 - DEBUG UnitTestFramework: '#setup: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:34:51 - DEBUG UnitTestFramework: '#setup ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:34:51 - DEBUG UnitTestFramework: '#run: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:34:52 - DEBUG UnitTestFramework: '#run ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:34:52 - DEBUG UnitTestFramework: '#teardown: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:34:52 - DEBUG UnitTestFramework: '#teardown ok: 'should be able to call #stopAdvertisingAndListening many times''

2017-06-13 13:34:52 - DEBUG UnitTestFramework: '#setup: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#setup ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#run: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#run ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#teardown: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#teardown ok: '#start - Causing native or wifi to fail will cause a promise reject ''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#setup: '#start should fail if called twice in a row''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#setup ok: '#start should fail if called twice in a row''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#run: '#start should fail if called twice in a row''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#run ok: '#start should fail if called twice in a row''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#teardown: '#start should fail if called twice in a row''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#teardown ok: '#start should fail if called twice in a row''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#setup: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#setup ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-06-13 13:34:53 - DEBUG UnitTestFramework: '#run: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-06-13 13:34:54 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-06-13 13:34:54 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-06-13 13:34:54 - INFO Socket: 'run skipped, test: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)', event: 'run_#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown ok: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#setup: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#setup ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-06-13 13:34:54 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-06-13 13:34:54 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-06-13 13:34:54 - INFO Socket: 'run skipped, test: 'does not emit duplicate discoveryAdvertisingStateUpdate', event: 'run_does not emit duplicate discoveryAdvertisingStateUpdate''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown ok: 'does not emit duplicate discoveryAdvertisingStateUpdate''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#setup: 'does not send duplicate availability changes''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#setup ok: 'does not send duplicate availability changes''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run: 'does not send duplicate availability changes''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run ok: 'does not send duplicate availability changes''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown: 'does not send duplicate availability changes''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown ok: 'does not send duplicate availability changes''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#setup: 'can get the network status''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#setup ok: 'can get the network status''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run: 'can get the network status''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run ok: 'can get the network status''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown: 'can get the network status''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown ok: 'can get the network status''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer added/removed to/from cache (native)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-06-13 13:34:54 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer added/removed to/from cache (wifi)''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#setup: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#setup ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#run: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#run ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#teardown: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#teardown ok: 'peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#setup: 'native available - new peer is cached''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#setup ok: 'native available - new peer is cached''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#run: 'native available - new peer is cached''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#run ok: 'native available - new peer is cached''

2017-06-13 13:34:55 - DEBUG UnitTestFramework: '#teardown: 'native available - new peer is cached''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown ok: 'native available - new peer is cached''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with same port and different generation is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup: 'native available - peer with greater generation is cached (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with greater generation is cached (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run: 'native available - peer with greater generation is cached (MPCF)''

2017-06-13 13:34:56 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-06-13 13:34:56 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-06-13 13:34:56 - INFO Socket: 'run skipped, test: 'native available - peer with greater generation is cached (MPCF)', event: 'run_native available - peer with greater generation is cached (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with greater generation is cached (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with greater generation is cached (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with greater generation is cached (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup: 'native available - peer with same or older generation is ignored (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run: 'native available - peer with same or older generation is ignored (MPCF)''

2017-06-13 13:34:56 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-06-13 13:34:56 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-06-13 13:34:56 - INFO Socket: 'run skipped, test: 'native available - peer with same or older generation is ignored (MPCF)', event: 'run_native available - peer with same or older generation is ignored (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown: 'native available - peer with same or older generation is ignored (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown ok: 'native available - peer with same or older generation is ignored (MPCF)''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup: 'native unavailable - new peer is ignored''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup ok: 'native unavailable - new peer is ignored''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run: 'native unavailable - new peer is ignored''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run ok: 'native unavailable - new peer is ignored''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown: 'native unavailable - new peer is ignored''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown ok: 'native unavailable - new peer is ignored''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup: 'native unavailable - cached peer is removed''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#setup ok: 'native unavailable - cached peer is removed''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run: 'native unavailable - cached peer is removed''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#run ok: 'native unavailable - cached peer is removed''

2017-06-13 13:34:56 - DEBUG UnitTestFramework: '#teardown: 'native unavailable - cached peer is removed''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown ok: 'native unavailable - cached peer is removed''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for wifi peers''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-06-13 13:34:57 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-06-13 13:34:57 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-06-13 13:34:57 - INFO Socket: 'run skipped, test: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)', event: 'run_networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown ok: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup: 'multiconnect failure - new peer is ignored (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run: 'multiconnect failure - new peer is ignored (MPCF)''

2017-06-13 13:34:57 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-06-13 13:34:57 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-06-13 13:34:57 - INFO Socket: 'run skipped, test: 'multiconnect failure - new peer is ignored (MPCF)', event: 'run_multiconnect failure - new peer is ignored (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown: 'multiconnect failure - new peer is ignored (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown ok: 'multiconnect failure - new peer is ignored (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-06-13 13:34:57 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-06-13 13:34:57 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-06-13 13:34:57 - INFO Socket: 'run skipped, test: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)', event: 'run_multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown ok: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (TCP_NATIVE)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (TCP_NATIVE)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (TCP_NATIVE)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (TCP_NATIVE)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (TCP_NATIVE)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (TCP_NATIVE)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (BLUETOOTH)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (BLUETOOTH)''

2017-06-13 13:34:57 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup: 'newAddressPort field (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort field (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run: 'newAddressPort field (MPCF)''

2017-06-13 13:34:58 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-06-13 13:34:58 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-06-13 13:34:58 - INFO Socket: 'run skipped, test: 'newAddressPort field (MPCF)', event: 'run_newAddressPort field (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort field (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort field (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort field (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown ok: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - error when peer has not been discovered yet''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-06-13 13:34:58 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-06-13 13:34:58 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-06-13 13:34:58 - INFO Socket: 'run skipped, test: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)', event: 'run_#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)''

2017-06-13 13:34:58 - DEBUG UnitTestFramework: '#setup: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown ok: '#getPeerHostInfo - returns discovered cached wifi peer''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup: '#disconnect fails on wifi peers''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup ok: '#disconnect fails on wifi peers''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run: '#disconnect fails on wifi peers''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run ok: '#disconnect fails on wifi peers''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown: '#disconnect fails on wifi peers''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown ok: '#disconnect fails on wifi peers''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup: '#disconnect delegates native peers to the native wrapper''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup ok: '#disconnect delegates native peers to the native wrapper''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run: '#disconnect delegates native peers to the native wrapper''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run ok: '#disconnect delegates native peers to the native wrapper''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown: '#disconnect delegates native peers to the native wrapper''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown ok: '#disconnect delegates native peers to the native wrapper''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup: 'network changes emitted correctly''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup ok: 'network changes emitted correctly''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run: 'network changes emitted correctly''

2017-06-13 13:34:59 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-06-13 13:34:59 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-06-13 13:34:59 - INFO Socket: 'run skipped, test: 'network changes emitted correctly', event: 'run_network changes emitted correctly''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run ok: 'network changes emitted correctly''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown: 'network changes emitted correctly''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown ok: 'network changes emitted correctly''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in started state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in started state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in started state''

2017-06-13 13:34:59 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-06-13 13:34:59 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-06-13 13:34:59 - INFO Socket: 'run skipped, test: 'network changes not emitted in started state', event: 'run_network changes not emitted in started state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in started state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in started state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in started state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup: 'network changes not emitted in stopped state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup ok: 'network changes not emitted in stopped state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run: 'network changes not emitted in stopped state''

2017-06-13 13:34:59 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-06-13 13:34:59 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-06-13 13:34:59 - INFO Socket: 'run skipped, test: 'network changes not emitted in stopped state', event: 'run_network changes not emitted in stopped state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run ok: 'network changes not emitted in stopped state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown: 'network changes not emitted in stopped state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#teardown ok: 'network changes not emitted in stopped state''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#setup ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-06-13 13:34:59 - DEBUG UnitTestFramework: '#run: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-06-13 13:35:00 - DEBUG UnitTestFramework: '#run ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-06-13 13:35:00 - DEBUG UnitTestFramework: '#teardown: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-06-13 13:35:01 - DEBUG UnitTestFramework: '#teardown ok: 'We properly fire peer unavailable and then available when connection fails on Android''

2017-06-13 13:35:01 - DEBUG UnitTestFramework: '#setup: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-06-13 13:35:01 - DEBUG UnitTestFramework: '#setup ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-06-13 13:35:01 - DEBUG UnitTestFramework: '#run: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-06-13 13:35:01 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-06-13 13:35:01 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-06-13 13:35:01 - INFO Socket: 'run skipped, test: 'We properly fire peer unavailable and then available when connection fails on iOS', event: 'run_We properly fire peer unavailable and then available when connection fails on iOS''

2017-06-13 13:35:01 - DEBUG UnitTestFramework: '#run ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-06-13 13:35:01 - DEBUG UnitTestFramework: '#teardown: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-06-13 13:35:01 - DEBUG UnitTestFramework: '#teardown ok: 'We properly fire peer unavailable and then available when connection fails on iOS''

2017-06-13 13:35:01 - DEBUG UnitTestFramework: '#setup: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-06-13 13:35:01 - DEBUG UnitTestFramework: '#setup ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-06-13 13:35:01 - DEBUG UnitTestFramework: '#run: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-06-13 13:35:02 - DEBUG UnitTestFramework: '#run ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-06-13 13:35:02 - DEBUG UnitTestFramework: '#teardown: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-06-13 13:35:03 - DEBUG UnitTestFramework: '#teardown ok: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''

2017-06-13 13:35:03 - DEBUG UnitTestFramework: '#setup: 'does not fire duplicate events after peer listener recreation''

2017-06-13 13:35:03 - DEBUG UnitTestFramework: '#setup ok: 'does not fire duplicate events after peer listener recreation''

2017-06-13 13:35:03 - DEBUG UnitTestFramework: '#run: 'does not fire duplicate events after peer listener recreation''

2017-06-13 13:35:03 - DEBUG UnitTestFramework: '#run ok: 'does not fire duplicate events after peer listener recreation''

2017-06-13 13:35:03 - DEBUG UnitTestFramework: '#teardown: 'does not fire duplicate events after peer listener recreation''

2017-06-13 13:35:03 - DEBUG UnitTestFramework: '#teardown ok: 'does not fire duplicate events after peer listener recreation''

2017-06-13 13:35:03 - DEBUG UnitTestFramework: '#setup: '#stop should change peers''

2017-06-13 13:35:03 - DEBUG UnitTestFramework: '#setup ok: '#stop should change peers''

2017-06-13 13:35:03 - DEBUG UnitTestFramework: '#run: '#stop should change peers''

2017-06-13 13:35:04 - DEBUG UnitTestFramework: '#run ok: '#stop should change peers''

2017-06-13 13:35:04 - DEBUG UnitTestFramework: '#teardown: '#stop should change peers''

2017-06-13 13:35:04 - DEBUG UnitTestFramework: '#teardown ok: '#stop should change peers''

2017-06-13 13:35:04 - DEBUG UnitTestFramework: '#setup: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-06-13 13:35:04 - DEBUG UnitTestFramework: '#setup ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-06-13 13:35:04 - DEBUG UnitTestFramework: '#run: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#run ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#teardown: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#teardown ok: 'If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#setup: 'peer should be found once after listening and discovery started''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#setup ok: 'peer should be found once after listening and discovery started''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#run: 'peer should be found once after listening and discovery started''

2017-06-13 13:35:05 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-06-13 13:35:05 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-06-13 13:35:05 - INFO Socket: 'run skipped, test: 'peer should be found once after listening and discovery started', event: 'run_peer should be found once after listening and discovery started''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#run ok: 'peer should be found once after listening and discovery started''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#teardown: 'peer should be found once after listening and discovery started''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#teardown ok: 'peer should be found once after listening and discovery started''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#setup: 'can get data from all participants''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#setup ok: 'can get data from all participants''

2017-06-13 13:35:05 - DEBUG UnitTestFramework: '#run: 'can get data from all participants''

2017-06-13 13:35:14 - ERROR UnitTestFramework: '#run failed: 'Can connect to a remote peer', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-13 13:35:14 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'ios', error: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'', stack: 'TimeoutError: timeout exceeded, event: 'run_Can connect to a remote peer_finished', test: 'Can connect to a remote peer'
    at afterTimeout (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-06-13 13:35:17 - ERROR TestServerProcess: 'uncaught promise rejection, error: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'', stack: 'AssertionError: equals arrays expected, received array 1: '[object Object],[object Object],[object Object]', array 2: '[object Object],[object Object],[object Object]'
    at Object.module.exports.arrayEquals (/home/pi/Test/server_1248535460c4faef/test/TestServer/utils/asserts.js:69:3)
    at UnitTestFramework.unbindSync (/home/pi/Test/server_1248535460c4faef/test/TestServer/UnitTestFramework.js:233:11)
    at /home/pi/Test/server_1248535460c4faef/test/TestServer/UnitTestFramework.js:100:10
    at PassThroughHandlerContext.finallyHandler (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/finally.js:55:23)
    at PassThroughHandlerContext.tryCatcher (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/promise.js:510:31)
    at Promise._settlePromise (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/promise.js:567:18)
    at Promise._settlePromise0 (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Promise._fulfill (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/promise.js:636:18)
    at PromiseArray._resolve (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/promise_array.js:125:19)
    at PromiseArray._promiseFulfilled (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/promise_array.js:143:14)
    at Promise._settlePromise (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/promise.js:572:26)
    at Promise._settlePromise0 (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/promise.js:612:10)
    at Promise._settlePromises (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/promise.js:691:18)
    at Async._drainQueue (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/home/pi/Test/server_1248535460c4faef/test/TestServer/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:917:13)''

2017-06-13 13:35:17 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-06-13 13:35:17 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

2017-06-13 13:35:17 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-06-13 13:35:17 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-06-13 13:35:17 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-06-13 13:35:17 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
13/6/2017@15:20:27 Getting the list of iOS devices 
13/6/2017@15:20:28 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
13/6/2017@15:20:28 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
13/6/2017@15:20:28 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
13/6/2017@15:20:28 Deploying iOS test app 
13/6/2017@15:20:28 uninstalling the application 
13/6/2017@15:20:28 installing the application 
13/6/2017@15:43:47 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
13/6/2017@15:43:47 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
13/6/2017@15:43:47 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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

Error! Unexpected exit on device ce061606e320561102 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1248535460c4faef_Make_tests_zombie_proof_jareksl/thali03_samsung-SM-G935F.md)

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

Error! Unexpected exit on device ce0616068b9f212302 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1248535460c4faef_Make_tests_zombie_proof_jareksl/thali04_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606c181d71003 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1248535460c4faef_Make_tests_zombie_proof_jareksl/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1248535460c4faef_Make_tests_zombie_proof_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1248535460c4faef_Make_tests_zombie_proof_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1248535460c4faef_Make_tests_zombie_proof_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/1248535460c4faef_Make_tests_zombie_proof_jareksl/iOS_server.md)





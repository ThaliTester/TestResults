#### Test 12302516380258fe Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-05-30 11:51:29 - INFO HttpServer: 'listening on *:3000'

2017-05-30 11:51:34 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '8b774633-c35d-4d0f-906f-b247f4715b58', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-30 11:51:34 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-05-30 11:51:36 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'a1727c29-ab97-4dd4-8b5f-316345b1d05e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-30 11:51:36 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-05-30 11:51:36 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '8b774633-c35d-4d0f-906f-b247f4715b58', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-30 11:51:36 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-mfts', uuid: '8b774633-c35d-4d0f-906f-b247f4715b58', platformName: 'ios''

2017-05-30 11:51:37 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '8bdd35cc-da39-41e0-9b0a-4a1322023059', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-30 11:51:37 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-05-30 11:51:37 - INFO TestFramework: 'all required 3 devices are present for platformName: 'ios''

2017-05-30 11:51:37 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'ios''

2017-05-30 11:51:37 - DEBUG UnitTestFramework: 'scheduling tests'

2017-05-30 11:51:38 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: 'a1727c29-ab97-4dd4-8b5f-316345b1d05e', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-30 11:51:38 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: 'a1727c29-ab97-4dd4-8b5f-316345b1d05e', platformName: 'ios''

2017-05-30 11:51:38 - DEBUG UnitTestFramework: 'tests scheduled'

2017-05-30 11:51:38 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-05-30 11:51:39 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-05-30 11:51:39 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-05-30 11:51:39 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '8bdd35cc-da39-41e0-9b0a-4a1322023059', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-30 11:51:39 - INFO TestFramework: 'updating existing device, name: 'Apple-iphone-5s-1', uuid: '8bdd35cc-da39-41e0-9b0a-4a1322023059', platformName: 'ios''

2017-05-30 11:51:40 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-05-30 11:51:40 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-05-30 11:51:40 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-05-30 11:51:40 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-05-30 11:51:40 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-05-30 11:51:40 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-05-30 11:51:40 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-05-30 11:51:40 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-05-30 11:51:42 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-05-30 11:51:42 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-30 11:51:47 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-30 11:51:47 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-30 11:51:51 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-30 11:51:51 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-30 11:51:55 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-05-30 11:51:55 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-30 11:51:59 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-30 11:51:59 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-30 11:51:59 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-30 11:51:59 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-30 11:52:01 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-05-30 11:52:01 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-05-30 11:52:09 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-30 11:52:09 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-05-30 11:52:09 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-30 11:52:09 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-30 11:52:28 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on a single db change', event: 'run_Call of onCheckpointReached handler on a single db change''

2017-05-30 11:52:28 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-30 11:52:28 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-05-30 11:52:29 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-05-30 11:52:29 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-30 11:52:43 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-30 11:52:43 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-30 11:52:43 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-30 11:52:43 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-30 11:52:50 - INFO Socket: 'run skipped, test: 'Call of multiple onCheckpointReached handlers on a single db change', event: 'run_Call of multiple onCheckpointReached handlers on a single db change''

2017-05-30 11:52:50 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-30 11:52:50 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-30 11:52:51 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-05-30 11:52:51 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-30 11:52:51 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-30 11:52:51 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-30 11:52:52 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-30 11:52:52 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-30 11:52:53 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-30 11:52:53 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-30 11:52:53 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-30 11:52:54 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-05-30 11:52:54 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-30 11:52:57 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-30 11:52:57 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-30 11:52:57 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-30 11:52:58 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-30 11:53:02 - INFO Socket: 'run skipped, test: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-30 11:53:02 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-30 11:53:02 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-30 11:53:03 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-05-30 11:53:03 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-05-30 11:53:03 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-05-30 11:53:03 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-05-30 11:53:03 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-05-30 11:53:03 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-05-30 11:53:03 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-05-30 11:53:03 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-05-30 11:53:05 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-05-30 11:53:05 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-05-30 11:53:12 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-05-30 11:53:12 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-05-30 11:53:18 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-05-30 11:53:18 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-05-30 11:53:37 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-05-30 11:53:37 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-05-30 11:53:44 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-05-30 11:53:44 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-05-30 11:53:58 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-05-30 11:53:58 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-05-30 11:54:10 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-05-30 11:54:10 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-05-30 11:54:13 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-05-30 11:54:13 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-05-30 11:54:15 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-05-30 11:54:15 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-05-30 11:54:17 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-05-30 11:54:17 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-05-30 11:54:26 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-05-30 11:54:26 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-05-30 11:55:13 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-05-30 11:55:13 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-05-30 11:55:21 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-05-30 11:55:21 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-05-30 11:55:28 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-05-30 11:55:28 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-05-30 11:55:29 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-05-30 11:55:29 - DEBUG UnitTestFramework: '#setup: 'enqueued function are always executed asynchronously''

2017-05-30 11:55:29 - DEBUG UnitTestFramework: '#setup ok: 'enqueued function are always executed asynchronously''

2017-05-30 11:55:29 - DEBUG UnitTestFramework: '#run: 'enqueued function are always executed asynchronously''

2017-05-30 11:55:33 - DEBUG UnitTestFramework: '#run ok: 'enqueued function are always executed asynchronously''

2017-05-30 11:55:33 - DEBUG UnitTestFramework: '#teardown: 'enqueued function are always executed asynchronously''

2017-05-30 11:55:38 - DEBUG UnitTestFramework: '#teardown ok: 'enqueued function are always executed asynchronously''

2017-05-30 11:55:38 - DEBUG UnitTestFramework: '#setup: 'exceptions in the executor are properly handled''

2017-05-30 11:55:45 - DEBUG UnitTestFramework: '#setup ok: 'exceptions in the executor are properly handled''

2017-05-30 11:55:45 - DEBUG UnitTestFramework: '#run: 'exceptions in the executor are properly handled''

2017-05-30 11:55:56 - DEBUG UnitTestFramework: '#run ok: 'exceptions in the executor are properly handled''

2017-05-30 11:55:56 - DEBUG UnitTestFramework: '#teardown: 'exceptions in the executor are properly handled''

2017-05-30 11:56:01 - DEBUG UnitTestFramework: '#teardown ok: 'exceptions in the executor are properly handled''

2017-05-30 11:56:01 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-05-30 11:56:02 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-05-30 11:56:02 - DEBUG UnitTestFramework: '#run: 'basic''

2017-05-30 11:56:02 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-05-30 11:56:02 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-05-30 11:56:21 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-05-30 11:56:21 - DEBUG UnitTestFramework: '#setup: 'another''

2017-05-30 11:56:24 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-05-30 11:56:24 - DEBUG UnitTestFramework: '#run: 'another''

2017-05-30 11:56:29 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_12302516380258fe/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-30 11:56:29 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-05-30 11:56:29 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-05-30 11:56:29 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

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
30/5/2017@13:47:50 Getting the list of iOS devices 
30/5/2017@13:47:51 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
30/5/2017@13:47:51 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
30/5/2017@13:47:51 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
30/5/2017@13:47:51 Deploying iOS test app 
30/5/2017@13:47:51 uninstalling the application 
30/5/2017@13:47:51 installing the application 
30/5/2017@14:11:10 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
30/5/2017@14:11:10 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/12302516380258fe_Enable_tests_that_were_disabled_due_to__1600___1618_and__1767_mlesnic/thali03_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/12302516380258fe_Enable_tests_that_were_disabled_due_to__1600___1618_and__1767_mlesnic/thali04_samsung-SM-G930F.md)

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

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/12302516380258fe_Enable_tests_that_were_disabled_due_to__1600___1618_and__1767_mlesnic/thali05_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/12302516380258fe_Enable_tests_that_were_disabled_due_to__1600___1618_and__1767_mlesnic/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/12302516380258fe_Enable_tests_that_were_disabled_due_to__1600___1618_and__1767_mlesnic/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/12302516380258fe_Enable_tests_that_were_disabled_due_to__1600___1618_and__1767_mlesnic/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/12302516380258fe_Enable_tests_that_were_disabled_due_to__1600___1618_and__1767_mlesnic/iOS_server.md)





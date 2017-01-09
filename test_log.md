#### Test 996748488b0f149 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2017-01-09 11:55:22 - INFO HttpServer: 'listening on *:3000'

2017-01-09 11:57:03 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '4d9796f3-1721-459d-9712-be76aa7f2ef4', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-09 11:57:03 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-09 11:57:09 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '15575761-29ff-4205-99eb-ab3d024110fb', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-09 11:57:09 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-01-09 11:58:25 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '53907625-4c0a-43e3-b484-cef8ed6072dc', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-09 11:58:25 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-09 11:58:25 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-01-09 11:58:25 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-01-09 11:58:25 - DEBUG UnitTestFramework: 'scheduling tests'

2017-01-09 11:58:26 - DEBUG UnitTestFramework: 'tests scheduled'

2017-01-09 11:58:26 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-09 11:58:27 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-09 11:58:28 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-09 11:58:29 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-09 11:58:29 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-09 11:58:29 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2017-01-09 11:58:29 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-09 11:58:29 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-09 11:58:29 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-09 11:58:30 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-09 11:58:30 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-09 11:58:30 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2017-01-09 11:58:30 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-09 11:58:30 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-09 11:58:30 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2017-01-09 11:58:31 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#run: 'basic''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-01-09 11:58:32 - DEBUG UnitTestFramework: '#setup: 'another''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#run: 'another''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#setup: 'Correctly parses/stringifies USN''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#setup ok: 'Correctly parses/stringifies USN''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#run: 'Correctly parses/stringifies USN''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#run ok: 'Correctly parses/stringifies USN''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#teardown: 'Correctly parses/stringifies USN''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#teardown ok: 'Correctly parses/stringifies USN''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2017-01-09 11:58:33 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2017-01-09 12:00:22 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_996748488b0f149/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-09 12:00:22 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''
2017-01-09 12:00:22 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''
2017-01-09 12:00:22 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : Error: Command failed: true
9/1/2017@12:52:07 Getting the list of iOS devices 
9/1/2017@12:52:08 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
9/1/2017@12:52:08 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
9/1/2017@12:52:08 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
9/1/2017@12:52:08 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
9/1/2017@12:52:08 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
9/1/2017@12:52:08 Deploying iOS test app 
9/1/2017@12:52:08 uninstalling the application 
9/1/2017@12:52:09 installing the application 
9/1/2017@12:54:45 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/996748488b0f149_Fix_race_conditions_in_networkChanged_event_handling_chapko/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/996748488b0f149_Fix_race_conditions_in_networkChanged_event_handling_chapko/iOS_iphone-5s-mfts.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/996748488b0f149_Fix_race_conditions_in_networkChanged_event_handling_chapko/iOS_iphone-6-2.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/996748488b0f149_Fix_race_conditions_in_networkChanged_event_handling_chapko/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/996748488b0f149_Fix_race_conditions_in_networkChanged_event_handling_chapko/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/996748488b0f149_Fix_race_conditions_in_networkChanged_event_handling_chapko/iOS_server.md)


###Android Logs
####Node name: thali02
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/996748488b0f149_Fix_race_conditions_in_networkChanged_event_handling_chapko/thali02_samsung-SM-G930F.md)

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

STOP log received from ce061606c181d71003
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/996748488b0f149_Fix_race_conditions_in_networkChanged_event_handling_chapko/thali03_samsung-SM-G930F.md)

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

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/996748488b0f149_Fix_race_conditions_in_networkChanged_event_handling_chapko/thali04_samsung-SM-G935F.md)





#### Test 107380351668086c Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
Enter ____.js
Targets defined
http required
Creating internal server
Got request
URL:  [ 'nodes', '3' ]
Got request
URL:  [ 'ios', '4' ]
Enter checkIt
Got request
URL:  [ 'droid', '1' ]
Got request
URL:  [ 'droid', '1' ]
Got request
URL:  [ 'droid', '1' ]
Enter checkIt
checkIt do the job
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2017-02-23 13:53:58 - INFO HttpServer: 'listening on *:3000'

2017-02-23 13:54:00 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: '74bd6abf-392f-4aa2-a859-c771f7a38819', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 13:54:00 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-02-23 13:54:04 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: 'd83f094b-d8b7-484f-80fd-ab61668e3b97', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 13:54:04 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-mini-mfts''

2017-02-23 13:54:06 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-mini-mfts', uuid: 'd83f094b-d8b7-484f-80fd-ab61668e3b97', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 13:54:06 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-mini-mfts', uuid: 'd83f094b-d8b7-484f-80fd-ab61668e3b97', platformName: 'ios''

2017-02-23 13:54:07 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '3b7a3f8c-b16b-462c-90e0-2ef316b7d52c', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 13:54:07 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-02-23 13:54:09 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '3b7a3f8c-b16b-462c-90e0-2ef316b7d52c', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 13:54:09 - INFO TestFramework: 'updating existing device, name: 'Apple-ipad-air-2-1', uuid: '3b7a3f8c-b16b-462c-90e0-2ef316b7d52c', platformName: 'ios''

2017-02-23 13:55:23 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '46c01233-f7bb-4dd0-943d-2cc32672324e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 13:55:23 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-23 13:55:38 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'f158fd2c-3bfc-4cff-8087-526344f4365a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 13:55:38 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-02-23 13:57:12 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'fc1e0274-100d-4b46-9739-dae14c0eadbe', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-02-23 13:57:12 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-02-23 13:57:12 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-02-23 13:57:12 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-02-23 13:57:12 - DEBUG UnitTestFramework: 'scheduling tests'

2017-02-23 13:57:12 - DEBUG UnitTestFramework: 'tests scheduled'

2017-02-23 13:57:12 - DEBUG UnitTestFramework: '#setup: 'basic''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#run: 'basic''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#run ok: 'basic''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#teardown: 'basic''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#setup: 'another''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#setup ok: 'another''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#run: 'another''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#run ok: 'another''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#teardown: 'another''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: 'all unit tests succeeded, platformName: 'android''

2017-02-23 13:57:14 - DEBUG UnitTestFramework: 'skipped tests: '[]''

2017-02-23 13:58:58 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_107380351668086c/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-02-23 13:58:58 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

2017-02-23 13:58:58 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-mini-mfts' disconnected, reason: 'undefined''

2017-02-23 13:58:58 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-02-23 13:58:58 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2017-02-23 13:58:58 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2017-02-23 13:58:58 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
23/2/2017@14:50:39 Getting the list of iOS devices 
23/2/2017@14:50:40 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
23/2/2017@14:50:40 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
23/2/2017@14:50:40 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
23/2/2017@14:50:40 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
23/2/2017@14:50:40 Deploying iOS test app 
23/2/2017@14:50:40 uninstalling the application 
23/2/2017@14:50:41 installing the application 
23/2/2017@14:53:17 ios: child process exited with code 254 on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
23/2/2017@15:13:59 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
23/2/2017@15:13:59 ios: child process exited with code null on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
23/2/2017@15:13:59 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
true

```
###iOS Logs
[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/107380351668086c_CI_sanity_check_-_master_jareksl/iOS_iphone-5s-mfts.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/107380351668086c_CI_sanity_check_-_master_jareksl/iOS_iphone-6-2.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/107380351668086c_CI_sanity_check_-_master_jareksl/iOS_ipad-air-2-1.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/107380351668086c_CI_sanity_check_-_master_jareksl/iOS_ipad-mini-mfts.md)

[server](https://github.com/ThaliTester/TestResults/blob/107380351668086c_CI_sanity_check_-_master_jareksl/iOS_server.md)




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

STOP log received from ce0616068b9f212302
Test has SUCCEED

Device test finished on ce0616068b9f212302 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/107380351668086c_CI_sanity_check_-_master_jareksl/thali02_samsung-SM-G930F.md)

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
Test has SUCCEED

Device test finished on ce061606c181d71003 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/107380351668086c_CI_sanity_check_-_master_jareksl/thali03_samsung-SM-G930F.md)

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
Test has SUCCEED

Device test finished on ce061606e320561102 
Android task is completed. [SUCCESS]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/107380351668086c_CI_sanity_check_-_master_jareksl/thali04_samsung-SM-G935F.md)



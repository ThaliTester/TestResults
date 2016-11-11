#### Test 93390913232c8a0 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":1}}
2016-11-11 20:59:17 - INFO HttpServer: 'listening on *:3000'

2016-11-11 21:00:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '3a4d213c-f104-4552-be08-44b3ddab8406', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-11 21:00:18 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-11-11 21:00:18 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-11-11 21:04:17 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_93390913232c8a0/test/TestServer/index.js:46:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
11/11/2016@21:56:01 Getting the list of iOS devices 
11/11/2016@21:56:02 Deploying iOS test app 
11/11/2016@21:56:02 uninstalling the application 
11/11/2016@21:56:02 installing the application 
11/11/2016@22:19:21 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
true

```
###Android Logs
####Node name: thali05
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/93390913232c8a0_DONT_MERGE_-_test_CI_with_iOS_larryonoff/thali05_samsung-SM-G935F.md)


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/93390913232c8a0_DONT_MERGE_-_test_CI_with_iOS_larryonoff/iOS_IpadAir2-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/93390913232c8a0_DONT_MERGE_-_test_CI_with_iOS_larryonoff/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/93390913232c8a0_DONT_MERGE_-_test_CI_with_iOS_larryonoff/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/93390913232c8a0_DONT_MERGE_-_test_CI_with_iOS_larryonoff/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/93390913232c8a0_DONT_MERGE_-_test_CI_with_iOS_larryonoff/iOS_server.md)





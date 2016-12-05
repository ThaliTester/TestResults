#### Test 965175628202a26 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":2,"android":3}}
2016-12-05 13:10:26 - INFO HttpServer: 'listening on *:3000'

2016-12-05 13:11:11 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '861773ef-7602-4da2-a01c-daf95dc05d95', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-05 13:11:11 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-12-05 13:15:26 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_965175628202a26/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-05 13:15:26 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
5/12/2016@14:07:13 Getting the list of iOS devices 
5/12/2016@14:07:14 Deploying iOS test app 
5/12/2016@14:07:14 uninstalling the application 
5/12/2016@14:07:14 installing the application 
5/12/2016@14:08:37 ios: child process exited with code 253 on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
5/12/2016@14:08:45 ios: child process exited with code 253 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/965175628202a26_iOS_preparation_for_swift_xctest_larryonoff/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/965175628202a26_iOS_preparation_for_swift_xctest_larryonoff/iOS_Iphone6-2.md)

[server](https://github.com/ThaliTester/TestResults/blob/965175628202a26_iOS_preparation_for_swift_xctest_larryonoff/iOS_server.md)


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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/965175628202a26_iOS_preparation_for_swift_xctest_larryonoff/thali05_samsung-SM-G935F.md)

####Node name: thali06
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

Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/965175628202a26_iOS_preparation_for_swift_xctest_larryonoff/thali06_samsung-SM-G930F.md)

####Node name: thali07
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/965175628202a26_iOS_preparation_for_swift_xctest_larryonoff/thali07_samsung-SM-G930F.md)





#### Test 910208789f3a884 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":1}}
2016-11-10 13:46:23 - INFO HttpServer: 'listening on *:3000'

2016-11-10 13:51:24 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_910208789f3a884/test/TestServer/index.js:46:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
10/11/2016@14:43:42 Getting the list of iOS devices 
10/11/2016@14:43:43 Deploying iOS test app 
10/11/2016@14:43:43 uninstalling the application 
10/11/2016@14:43:43 installing the application 
10/11/2016@15:07:02 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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

Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/910208789f3a884_Fix_testThaliMobileNativeTest_tests__dersim-davaod/thali05_samsung-SM-G935F.md)


###iOS Logs
[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/910208789f3a884_Fix_testThaliMobileNativeTest_tests__dersim-davaod/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/910208789f3a884_Fix_testThaliMobileNativeTest_tests__dersim-davaod/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/910208789f3a884_Fix_testThaliMobileNativeTest_tests__dersim-davaod/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/910208789f3a884_Fix_testThaliMobileNativeTest_tests__dersim-davaod/iOS_server.md)





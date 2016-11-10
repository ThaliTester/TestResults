#### Test 921522868c3974a Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":1}}
2016-11-10 10:03:55 - INFO HttpServer: 'listening on *:3000'

2016-11-10 10:08:56 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_921522868c3974a/test/TestServer/index.js:46:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/921522868c3974a_Implemented_ThaliMobileNativeWrapper_multiConnect_method_squid48/thali05_samsung-SM-G935F.md)




###iOS Logs
[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/921522868c3974a_Implemented_ThaliMobileNativeWrapper_multiConnect_method_squid48/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/921522868c3974a_Implemented_ThaliMobileNativeWrapper_multiConnect_method_squid48/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/921522868c3974a_Implemented_ThaliMobileNativeWrapper_multiConnect_method_squid48/iOS_IpadAir2-1.md)



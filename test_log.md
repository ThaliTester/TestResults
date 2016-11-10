#### Test 93142442ff07d87 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":1}}
2016-11-10 12:59:00 - INFO HttpServer: 'listening on *:3000'

2016-11-10 12:59:01 - DEBUG HttpServer: 'device presented, name: 'Apple-Iphone6-2', uuid: 'ce62888e-ab75-425e-ade8-aec2792a04bb', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-11-10 12:59:01 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'Apple-Iphone6-2''

2016-11-10 12:59:01 - INFO HttpServer: 'Socket to device name: 'Apple-Iphone6-2' disconnected, reason: 'client namespace disconnect''

2016-11-10 13:04:00 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_93142442ff07d87/test/TestServer/index.js:46:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
10/11/2016@13:56:19 Getting the list of iOS devices 
10/11/2016@13:56:20 Deploying iOS test app 
10/11/2016@13:56:20 uninstalling the application 
10/11/2016@13:56:20 installing the application 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/93142442ff07d87__897_implemented_1__3__4__5_tasks_squid48/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/93142442ff07d87__897_implemented_1__3__4__5_tasks_squid48/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/93142442ff07d87__897_implemented_1__3__4__5_tasks_squid48/iOS_IpadAir2-1.md)


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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/93142442ff07d87__897_implemented_1__3__4__5_tasks_squid48/thali05_samsung-SM-G935F.md)





#### Test 935721672bafbe2 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":2}}
2016-11-21 15:49:31 - INFO HttpServer: 'listening on *:3000'

2016-11-21 15:50:31 - DEBUG HttpServer: 'device presented, name: 'Huawei-Nexus 6P', uuid: '28692e9c-212f-4215-acad-8ad110d8db01', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-11-21 15:50:31 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-11-21 15:54:31 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_935721672bafbe2/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-11-21 15:54:31 - INFO HttpServer: 'Socket to device name: 'Huawei-Nexus 6P' disconnected, reason: 'undefined''


 
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
21/11/2016@16:46:29 Getting the list of iOS devices 
21/11/2016@16:46:30 Deploying iOS test app 
21/11/2016@16:46:30 uninstalling the application 
21/11/2016@16:46:30 installing the application 
21/11/2016@16:49:09 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
21/11/2016@17:09:49 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/935721672bafbe2_New_peer_generation__894__evabishchevich/thali05_samsung-SM-G935F.md)

####Node name: thali07
Console output:
```
Stopping app on  ENU7N16516000121
Uninstalling app on  ENU7N16516000121

All devices are ready!

Deploying to ENU7N16516000121
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000121

Starting application ThaliTest on ENU7N16516000121

App was succesfully started on ENU7N16516000121

STOP log received from ENU7N16516000121
Test has FAILED

Device test finished on ENU7N16516000121 
Android task is completed. [FAILED]
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/935721672bafbe2_New_peer_generation__894__evabishchevich/thali07_Huawei-Nexus 6P.md)


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/935721672bafbe2_New_peer_generation__894__evabishchevich/iOS_IpadAir2-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/935721672bafbe2_New_peer_generation__894__evabishchevich/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/935721672bafbe2_New_peer_generation__894__evabishchevich/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/935721672bafbe2_New_peer_generation__894__evabishchevich/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/935721672bafbe2_New_peer_generation__894__evabishchevich/iOS_server.md)





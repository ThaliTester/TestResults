#### Test 96524298ae159c7 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":2,"android":3}}
2016-12-06 12:45:25 - INFO HttpServer: 'listening on *:3000'

2016-12-06 12:46:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '3abe0b78-e637-4359-89ce-88e9c0c439fb', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-06 12:46:18 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-06 12:50:25 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_96524298ae159c7/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-06 12:50:25 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''


 
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
6/12/2016@13:42:12 Getting the list of iOS devices 
6/12/2016@13:42:13 Deploying iOS test app 
6/12/2016@13:42:13 uninstalling the application 
6/12/2016@13:42:13 installing the application 
6/12/2016@14:05:31 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
6/12/2016@14:05:31 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/96524298ae159c7_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/thali05_samsung-SM-G935F.md)

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

STOP log received from ce061606c181d71003
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/96524298ae159c7_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/thali06_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/96524298ae159c7_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/thali07_samsung-SM-G930F.md)


###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/96524298ae159c7_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/96524298ae159c7_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/96524298ae159c7_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_server.md)





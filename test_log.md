#### Test 96524298edd5c74 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2016-12-07 11:52:33 - INFO HttpServer: 'listening on *:3000'

2016-12-07 11:53:27 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'cf20611b-ab20-4fd9-991a-405a9b40cef3', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-07 11:53:27 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-12-07 11:57:33 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_96524298edd5c74/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-07 11:57:33 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''


 
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
7/12/2016@12:49:01 Getting the list of iOS devices 
7/12/2016@12:49:02 Deploying iOS test app 
7/12/2016@12:49:02 uninstalling the application 
7/12/2016@12:49:03 installing the application 
7/12/2016@12:51:43 ios: child process exited with code 254 on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
7/12/2016@13:12:21 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
7/12/2016@13:12:21 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/96524298edd5c74_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/thali05_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/96524298edd5c74_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/thali06_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/96524298edd5c74_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/thali07_samsung-SM-G930F.md)


###iOS Logs
[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/96524298edd5c74_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_ipad-mini-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/96524298edd5c74_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_ipad-air-2-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/96524298edd5c74_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_iphone-5s-1.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/96524298edd5c74_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_iphone-6-2.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/96524298edd5c74_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_iphone-5s-mfts.md)

[server](https://github.com/ThaliTester/TestResults/blob/96524298edd5c74_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_server.md)





#### Test 965242983906281 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2016-12-06 15:05:17 - INFO HttpServer: 'listening on *:3000'

2016-12-06 15:06:06 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '591924f5-b5cc-4596-ad04-998d9e48c328', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-06 15:06:07 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-06 15:10:17 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_965242983906281/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-06 15:10:17 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
6/12/2016@16:02:10 Getting the list of iOS devices 
6/12/2016@16:02:11 Deploying iOS test app 
6/12/2016@16:02:11 uninstalling the application 
6/12/2016@16:02:12 installing the application 
6/12/2016@16:02:53 ios: child process exited with code 253 on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
6/12/2016@16:03:57 ios: child process exited with code 253 on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
6/12/2016@16:04:00 ios: child process exited with code 253 on device bffa901fefdea07f59339a6737776943349f5077 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/965242983906281_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_ipad-mini-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/965242983906281_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_ipad-air-2-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/965242983906281_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_iphone-5s-1.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/965242983906281_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_iphone-6-2.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/965242983906281_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_iphone-5s-mfts.md)

[server](https://github.com/ThaliTester/TestResults/blob/965242983906281_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/iOS_server.md)


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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/965242983906281_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/thali05_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/965242983906281_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/thali06_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/965242983906281_change_devices_tests_network_type_from_Wi-Fi_to_Native_larryonoff/thali07_samsung-SM-G930F.md)





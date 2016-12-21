#### Test 9856377413b1ea0 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2016-12-21 14:43:02 - INFO HttpServer: 'listening on *:3000'

2016-12-21 14:43:19 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'f398e161-be18-484d-b009-d2b8c9f72730', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-21 14:43:19 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-21 14:44:30 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '362ffe10-bb8b-4904-b806-471cd883482e', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-21 14:44:30 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-21 14:48:02 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_9856377413b1ea0/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-21 14:48:02 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

2016-12-21 14:48:02 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
21/12/2016@15:40:00 Getting the list of iOS devices 
21/12/2016@15:40:01 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
21/12/2016@15:40:01 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
21/12/2016@15:40:01 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
21/12/2016@15:40:01 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
21/12/2016@15:40:01 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
21/12/2016@15:40:01 Deploying iOS test app 
21/12/2016@15:40:01 uninstalling the application 
21/12/2016@15:40:02 installing the application 
21/12/2016@15:42:49 ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
21/12/2016@16:03:19 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
true

```
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
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9856377413b1ea0_Run_iOS_branch_again_in_CI_and_confirm_that_it_passes_on_devices_1654_larryonoff/thali02_samsung-SM-G930F.md)

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
Test has FAILED

Device test finished on ce061606c181d71003 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9856377413b1ea0_Run_iOS_branch_again_in_CI_and_confirm_that_it_passes_on_devices_1654_larryonoff/thali03_samsung-SM-G930F.md)

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
Test has FAILED

Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/9856377413b1ea0_Run_iOS_branch_again_in_CI_and_confirm_that_it_passes_on_devices_1654_larryonoff/thali04_samsung-SM-G935F.md)


###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/9856377413b1ea0_Run_iOS_branch_again_in_CI_and_confirm_that_it_passes_on_devices_1654_larryonoff/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/9856377413b1ea0_Run_iOS_branch_again_in_CI_and_confirm_that_it_passes_on_devices_1654_larryonoff/iOS_iphone-5s-mfts.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/9856377413b1ea0_Run_iOS_branch_again_in_CI_and_confirm_that_it_passes_on_devices_1654_larryonoff/iOS_iphone-6-2.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/9856377413b1ea0_Run_iOS_branch_again_in_CI_and_confirm_that_it_passes_on_devices_1654_larryonoff/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/9856377413b1ea0_Run_iOS_branch_again_in_CI_and_confirm_that_it_passes_on_devices_1654_larryonoff/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/9856377413b1ea0_Run_iOS_branch_again_in_CI_and_confirm_that_it_passes_on_devices_1654_larryonoff/iOS_server.md)





#### Test 99448283f49b3a7 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2016-12-28 15:59:23 - INFO HttpServer: 'listening on *:3000'

2016-12-28 16:00:28 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'ab5f4cd7-b046-40f7-b708-64c0b87b15ec', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-28 16:00:28 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-12-28 16:04:23 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_99448283f49b3a7/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-28 16:04:23 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : Error: Command failed: true
28/12/2016@16:56:01 Getting the list of iOS devices 
28/12/2016@16:56:02 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
28/12/2016@16:56:02 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
28/12/2016@16:56:02 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
28/12/2016@16:56:02 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
28/12/2016@16:56:02 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
28/12/2016@16:56:02 Deploying iOS test app 
28/12/2016@16:56:02 uninstalling the application 
28/12/2016@16:56:03 installing the application 
28/12/2016@16:58:37 ios: child process exited with code 254 on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/99448283f49b3a7_Refactor_start/stop_operation_test_evabishchevich/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/99448283f49b3a7_Refactor_start/stop_operation_test_evabishchevich/iOS_iphone-5s-mfts.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/99448283f49b3a7_Refactor_start/stop_operation_test_evabishchevich/iOS_iphone-6-2.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/99448283f49b3a7_Refactor_start/stop_operation_test_evabishchevich/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/99448283f49b3a7_Refactor_start/stop_operation_test_evabishchevich/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/99448283f49b3a7_Refactor_start/stop_operation_test_evabishchevich/iOS_server.md)


###Android Logs
####Node name: thali02
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/99448283f49b3a7_Refactor_start/stop_operation_test_evabishchevich/thali02_samsung-SM-G930F.md)

####Node name: thali03
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/99448283f49b3a7_Refactor_start/stop_operation_test_evabishchevich/thali03_samsung-SM-G930F.md)

####Node name: thali04
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/99448283f49b3a7_Refactor_start/stop_operation_test_evabishchevich/thali04_samsung-SM-G935F.md)





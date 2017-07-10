#### Test 127198710c0cbe24 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-07-10 10:02:58 - INFO HttpServer: 'listening on *:3000'

2017-07-10 10:04:12 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'eb2af344-f8cc-4bc3-b0cf-3b0237df0ffd', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-07-10 10:04:12 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-07-10 10:07:58 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_127198710c0cbe24/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-07-10 10:07:58 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : Error: Command failed: true
10/7/2017@11:59:04 Getting the list of iOS devices 
10/7/2017@11:59:05 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
10/7/2017@11:59:05 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
10/7/2017@11:59:05 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
10/7/2017@11:59:05 Deploying iOS test app 
10/7/2017@11:59:05 uninstalling the application 
10/7/2017@11:59:06 installing the application 
10/7/2017@12:01:20 ios: child process exited with code 253 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
10/7/2017@12:01:27 ios: child process exited with code 253 on device bffa901fefdea07f59339a6737776943349f5077 
10/7/2017@12:01:29 ios: child process exited with code 253 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/127198710c0cbe24_Fix_iOS_native_tests_mlesnic/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/127198710c0cbe24_Fix_iOS_native_tests_mlesnic/iOS_iphone-5s-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/127198710c0cbe24_Fix_iOS_native_tests_mlesnic/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/127198710c0cbe24_Fix_iOS_native_tests_mlesnic/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/127198710c0cbe24_Fix_iOS_native_tests_mlesnic/thali01_samsung-SM-G930F.md)

####Node name: thali03
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

```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/127198710c0cbe24_Fix_iOS_native_tests_mlesnic/thali03_samsung-SM-G935F.md)

####Node name: thali04
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

Error! Unexpected exit on device ce0616068b9f212302 app:com.thaliproject.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/127198710c0cbe24_Fix_iOS_native_tests_mlesnic/thali04_samsung-SM-G930F.md)





#### Test 101910573e732e55 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2017-01-17 18:06:40 - INFO HttpServer: 'listening on *:3000'

2017-01-17 18:08:16 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'abe72d7f-2c46-4bce-a28d-001dd9dc8204', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-17 18:08:16 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-17 18:08:18 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'a0bc6b22-02f5-4bbb-8eab-93aef17ad95b', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-17 18:08:18 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2017-01-17 18:08:19 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-01-17 18:08:22 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'transport close''

2017-01-17 18:09:55 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '808b8d44-7218-4df6-884b-432bc5e32ab3', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-17 18:09:55 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2017-01-17 18:09:55 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2017-01-17 18:09:55 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2017-01-17 18:09:55 - DEBUG UnitTestFramework: 'scheduling tests'

2017-01-17 18:09:57 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '808b8d44-7218-4df6-884b-432bc5e32ab3', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-01-17 18:09:57 - INFO TestFramework: 'updating existing device, name: 'samsung-SM-G935F', uuid: '808b8d44-7218-4df6-884b-432bc5e32ab3', platformName: 'android''

2017-01-17 18:11:40 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_101910573e732e55/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-01-17 18:11:40 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
17/1/2017@19:03:26 Getting the list of iOS devices 
17/1/2017@19:03:27 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
17/1/2017@19:03:27 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
17/1/2017@19:03:27 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
17/1/2017@19:03:27 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
17/1/2017@19:03:27 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
17/1/2017@19:03:27 Deploying iOS test app 
17/1/2017@19:03:27 uninstalling the application 
17/1/2017@19:03:28 installing the application 
17/1/2017@19:03:29 ios: child process exited with code 253 on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
17/1/2017@19:26:46 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
17/1/2017@19:26:46 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/101910573e732e55_Fix_failing_test___1725_and__1731__chapko/thali02_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/101910573e732e55_Fix_failing_test___1725_and__1731__chapko/thali03_samsung-SM-G930F.md)

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

Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/101910573e732e55_Fix_failing_test___1725_and__1731__chapko/thali04_samsung-SM-G935F.md)


###iOS Logs
[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/101910573e732e55_Fix_failing_test___1725_and__1731__chapko/iOS_iphone-6-2.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/101910573e732e55_Fix_failing_test___1725_and__1731__chapko/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/101910573e732e55_Fix_failing_test___1725_and__1731__chapko/iOS_iphone-5s-mfts.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/101910573e732e55_Fix_failing_test___1725_and__1731__chapko/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/101910573e732e55_Fix_failing_test___1725_and__1731__chapko/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/101910573e732e55_Fix_failing_test___1725_and__1731__chapko/iOS_server.md)





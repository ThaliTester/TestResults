#### Test 112016147e249d1d Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
Enter ____.js
Targets defined
http required
Creating internal server
Got request
URL:  [ 'nodes', '3' ]
Got request
URL:  [ 'ios', '3' ]
Enter checkIt
Got request
URL:  [ 'droid', '1' ]
Got request
URL:  [ 'droid', '1' ]
Got request
URL:  [ 'droid', '1' ]
Enter checkIt
checkIt do the job
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":3}}
2017-03-22 17:34:30 - INFO HttpServer: 'listening on *:3000'

2017-03-22 17:34:40 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-mfts', uuid: 'e71bf4ee-dd06-4336-a5f5-494e04f59cf1', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-22 17:34:40 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-mfts''

2017-03-22 17:34:50 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '285ac3b5-0da2-49a6-ac15-ea6ae0489a24', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-03-22 17:34:50 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-03-22 17:38:21 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'ping timeout''

2017-03-22 17:39:30 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_112016147e249d1d/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-03-22 17:39:30 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-mfts' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
22/3/2017@18:31:03 Getting the list of iOS devices 
22/3/2017@18:31:04 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
22/3/2017@18:31:04 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
22/3/2017@18:31:04 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
22/3/2017@18:31:04 Deploying iOS test app 
22/3/2017@18:31:04 uninstalling the application 
22/3/2017@18:31:04 installing the application 
22/3/2017@18:54:23 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
22/3/2017@18:54:23 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
22/3/2017@18:54:23 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###Android Logs
####Node name: thali02
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606c181d71003 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606c181d71003
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/112016147e249d1d_Implement_CustomNSError_protocol_for_ThaliTest_AppContextError_asuhodolov/thali02_samsung-SM-G930F.md)

####Node name: thali03
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G935F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/112016147e249d1d_Implement_CustomNSError_protocol_for_ThaliTest_AppContextError_asuhodolov/thali03_samsung-SM-G935F.md)

####Node name: thali04
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

Error: problem running Android apk(com.test.thalitest) on device samsung-SM-G930F 
Starting: Intent { cmp=com.test.thalitest/.MainActivity VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
Error type 3
Error: Activity class {com.test.thalitest/com.test.thalitest.MainActivity} does not exist.
 
Error! true 
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/112016147e249d1d_Implement_CustomNSError_protocol_for_ThaliTest_AppContextError_asuhodolov/thali04_samsung-SM-G930F.md)


###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/112016147e249d1d_Implement_CustomNSError_protocol_for_ThaliTest_AppContextError_asuhodolov/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/112016147e249d1d_Implement_CustomNSError_protocol_for_ThaliTest_AppContextError_asuhodolov/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/112016147e249d1d_Implement_CustomNSError_protocol_for_ThaliTest_AppContextError_asuhodolov/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/112016147e249d1d_Implement_CustomNSError_protocol_for_ThaliTest_AppContextError_asuhodolov/iOS_server.md)





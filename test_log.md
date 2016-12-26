#### Test 993933123c9286c Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2016-12-26 23:22:34 - INFO HttpServer: 'listening on *:3000'

2016-12-26 23:22:55 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '72656d17-b955-48d4-917f-761cac91faef', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-26 23:22:55 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-12-26 23:23:05 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '0214310b-c196-43f5-bfe9-e726d0382d24', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-12-26 23:23:05 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-12-26 23:23:05 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-12-26 23:23:59 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '7c4beced-3f38-41b2-a9c4-ae0f4c6b6400', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-26 23:23:59 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-26 23:27:34 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_993933123c9286c/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-26 23:27:34 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

2016-12-26 23:27:34 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''

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
27/12/2016@00:19:26 Getting the list of iOS devices 
27/12/2016@00:19:28 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
27/12/2016@00:19:28 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
27/12/2016@00:19:28 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
27/12/2016@00:19:28 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
27/12/2016@00:19:28 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
27/12/2016@00:19:28 Deploying iOS test app 
27/12/2016@00:19:28 uninstalling the application 
27/12/2016@00:19:28 installing the application 
27/12/2016@00:22:52 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
27/12/2016@00:42:46 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
27/12/2016@00:42:46 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/993933123c9286c_Added_retry_for_runTestOnAllParticipants_andrew-aladev/thali02_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/993933123c9286c_Added_retry_for_runTestOnAllParticipants_andrew-aladev/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/993933123c9286c_Added_retry_for_runTestOnAllParticipants_andrew-aladev/thali04_samsung-SM-G935F.md)


###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/993933123c9286c_Added_retry_for_runTestOnAllParticipants_andrew-aladev/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/993933123c9286c_Added_retry_for_runTestOnAllParticipants_andrew-aladev/iOS_iphone-5s-mfts.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/993933123c9286c_Added_retry_for_runTestOnAllParticipants_andrew-aladev/iOS_iphone-6-2.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/993933123c9286c_Added_retry_for_runTestOnAllParticipants_andrew-aladev/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/993933123c9286c_Added_retry_for_runTestOnAllParticipants_andrew-aladev/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/993933123c9286c_Added_retry_for_runTestOnAllParticipants_andrew-aladev/iOS_server.md)





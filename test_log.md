#### Test 978514903f1da2e Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2016-12-13 23:10:30 - INFO HttpServer: 'listening on *:3000'

2016-12-13 23:10:56 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: '6199d1de-dd0d-4a59-9095-ea5035c858ef', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-12-13 23:10:56 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G935F''

2016-12-13 23:10:56 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'client namespace disconnect''

2016-12-13 23:11:35 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'cd50fca4-dbe3-4e4d-9ad1-18913d6830b7', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-13 23:11:35 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-13 23:15:30 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_978514903f1da2e/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-13 23:15:30 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''


 
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
14/12/2016@00:07:07 Getting the list of iOS devices 
14/12/2016@00:07:08 Deploying iOS test app 
14/12/2016@00:07:08 uninstalling the application 
14/12/2016@00:07:09 installing the application 
14/12/2016@00:30:27 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
14/12/2016@00:30:27 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/978514903f1da2e__1632_-_Fixing_broken_build_yaronyg/thali05_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/978514903f1da2e__1632_-_Fixing_broken_build_yaronyg/thali06_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/978514903f1da2e__1632_-_Fixing_broken_build_yaronyg/thali07_samsung-SM-G930F.md)


###iOS Logs
[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/978514903f1da2e__1632_-_Fixing_broken_build_yaronyg/iOS_ipad-mini-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/978514903f1da2e__1632_-_Fixing_broken_build_yaronyg/iOS_ipad-air-2-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/978514903f1da2e__1632_-_Fixing_broken_build_yaronyg/iOS_iphone-5s-1.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/978514903f1da2e__1632_-_Fixing_broken_build_yaronyg/iOS_iphone-6-2.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/978514903f1da2e__1632_-_Fixing_broken_build_yaronyg/iOS_iphone-5s-mfts.md)

[server](https://github.com/ThaliTester/TestResults/blob/978514903f1da2e__1632_-_Fixing_broken_build_yaronyg/iOS_server.md)





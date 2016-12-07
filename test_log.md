#### Test 965327534acc906 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2016-12-07 13:17:10 - INFO HttpServer: 'listening on *:3000'

2016-12-07 13:18:03 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'b50d28ef-19ec-4cd0-a927-10ba5c645d98', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-07 13:18:03 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-07 13:22:10 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_965327534acc906/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-07 13:22:10 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
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

Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/965327534acc906__1601_vasilevskayaem/thali05_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/965327534acc906__1601_vasilevskayaem/thali06_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/965327534acc906__1601_vasilevskayaem/thali07_samsung-SM-G930F.md)




###iOS Logs
[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/965327534acc906__1601_vasilevskayaem/iOS_ipad-mini-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/965327534acc906__1601_vasilevskayaem/iOS_ipad-air-2-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/965327534acc906__1601_vasilevskayaem/iOS_iphone-5s-1.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/965327534acc906__1601_vasilevskayaem/iOS_iphone-6-2.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/965327534acc906__1601_vasilevskayaem/iOS_iphone-5s-mfts.md)



#### Test 98912682a6d9d3f Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2016-12-21 18:27:05 - INFO HttpServer: 'listening on *:3000'

2016-12-21 18:27:25 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G935F', uuid: 'ceac3625-b7f9-461f-a502-ad2d75834450', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-21 18:27:25 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-12-21 18:28:53 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: 'dd5bd33f-9fc1-433e-a326-689afd7bcccc', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'true''

2016-12-21 18:28:53 - INFO TestFramework: 'disqualifying device on which native tests failed, name: 'samsung-SM-G930F''

2016-12-21 18:28:53 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'client namespace disconnect''

2016-12-21 18:32:05 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_98912682a6d9d3f/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-21 18:32:05 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G935F' disconnected, reason: 'undefined''

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
21/12/2016@19:23:50 Getting the list of iOS devices 
21/12/2016@19:23:51 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
21/12/2016@19:23:51 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
21/12/2016@19:23:51 ios: device name: iphone-6-2 , device identifier:  7ed231f0829a4ace34162e6c18308bcd995bc25a
21/12/2016@19:23:51 ios: device name: ipad-mini-mfts , device identifier:  83aab4e7f1dde3becec287ac4c44362439d2595b
21/12/2016@19:23:51 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
21/12/2016@19:23:51 Deploying iOS test app 
21/12/2016@19:23:51 uninstalling the application 
21/12/2016@19:23:52 installing the application 
21/12/2016@19:47:10 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
21/12/2016@19:47:10 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/98912682a6d9d3f__1665_Fix__Test__update_peer_discovery_1__fails_on_desktop_and_phones_in_iOS_branch__chapko/thali02_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/98912682a6d9d3f__1665_Fix__Test__update_peer_discovery_1__fails_on_desktop_and_phones_in_iOS_branch__chapko/thali03_samsung-SM-G930F.md)

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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/98912682a6d9d3f__1665_Fix__Test__update_peer_discovery_1__fails_on_desktop_and_phones_in_iOS_branch__chapko/thali04_samsung-SM-G935F.md)


###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/98912682a6d9d3f__1665_Fix__Test__update_peer_discovery_1__fails_on_desktop_and_phones_in_iOS_branch__chapko/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/98912682a6d9d3f__1665_Fix__Test__update_peer_discovery_1__fails_on_desktop_and_phones_in_iOS_branch__chapko/iOS_iphone-5s-mfts.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/98912682a6d9d3f__1665_Fix__Test__update_peer_discovery_1__fails_on_desktop_and_phones_in_iOS_branch__chapko/iOS_iphone-6-2.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/98912682a6d9d3f__1665_Fix__Test__update_peer_discovery_1__fails_on_desktop_and_phones_in_iOS_branch__chapko/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/98912682a6d9d3f__1665_Fix__Test__update_peer_discovery_1__fails_on_desktop_and_phones_in_iOS_branch__chapko/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/98912682a6d9d3f__1665_Fix__Test__update_peer_discovery_1__fails_on_desktop_and_phones_in_iOS_branch__chapko/iOS_server.md)





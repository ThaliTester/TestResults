#### Test 98312760b2c4df9 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":3}}
2016-12-19 14:14:40 - INFO HttpServer: 'listening on *:3000'

2016-12-19 14:16:13 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '59c6c6e8-40db-4323-bf23-8d9154098d89', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-19 14:16:13 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-19 14:19:40 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_98312760b2c4df9/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-19 14:19:40 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''


 
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
19/12/2016@15:11:26 Getting the list of iOS devices 
19/12/2016@15:11:27 Deploying iOS test app 
19/12/2016@15:11:27 uninstalling the application 
19/12/2016@15:11:28 installing the application 
19/12/2016@15:34:46 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
19/12/2016@15:34:46 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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

Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
Child process exited with code null on device ce061606e320561102
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/98312760b2c4df9_Fixed_peer_generation_evabishchevich/thali05_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/98312760b2c4df9_Fixed_peer_generation_evabishchevich/thali06_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/98312760b2c4df9_Fixed_peer_generation_evabishchevich/thali07_samsung-SM-G930F.md)


###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/98312760b2c4df9_Fixed_peer_generation_evabishchevich/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/98312760b2c4df9_Fixed_peer_generation_evabishchevich/iOS_iphone-5s-mfts.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/98312760b2c4df9_Fixed_peer_generation_evabishchevich/iOS_iphone-6-2.md)

[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/98312760b2c4df9_Fixed_peer_generation_evabishchevich/iOS_ipad-mini-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/98312760b2c4df9_Fixed_peer_generation_evabishchevich/iOS_iphone-5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/98312760b2c4df9_Fixed_peer_generation_evabishchevich/iOS_server.md)





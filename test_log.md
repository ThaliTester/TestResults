#### Test 95321062378f266 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-12-06 11:50:36 - INFO HttpServer: 'listening on *:3000'

2016-12-06 11:51:45 - INFO HttpServer: 'Socket to device name: 'device that was not presented yet' disconnected, reason: 'transport close''

2016-12-06 11:55:36 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_95321062378f266/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''


 
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
6/12/2016@12:47:18 Getting the list of iOS devices 
6/12/2016@12:47:19 Deploying iOS test app 
6/12/2016@12:47:19 uninstalling the application 
6/12/2016@12:47:19 installing the application 
6/12/2016@12:49:00 ios: child process exited with code 253 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
6/12/2016@13:10:38 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
6/12/2016@13:10:38 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
6/12/2016@13:10:38 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/95321062378f266_Fix_build_scripts_chapko/thali05_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/95321062378f266_Fix_build_scripts_chapko/thali06_samsung-SM-G930F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/95321062378f266_Fix_build_scripts_chapko/thali07_samsung-SM-G930F.md)


###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/95321062378f266_Fix_build_scripts_chapko/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/95321062378f266_Fix_build_scripts_chapko/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/95321062378f266_Fix_build_scripts_chapko/iOS_IpadAir2-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/95321062378f266_Fix_build_scripts_chapko/iOS_Iphone6-2.md)

[server](https://github.com/ThaliTester/TestResults/blob/95321062378f266_Fix_build_scripts_chapko/iOS_server.md)





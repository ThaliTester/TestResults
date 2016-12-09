#### Test 9732732894937d3 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":2}}
2016-12-09 15:52:04 - INFO HttpServer: 'listening on *:3000'

2016-12-09 15:57:04 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_9732732894937d3/test/TestServer/index.js:45:9)
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
9/12/2016@16:48:41 Getting the list of iOS devices 
9/12/2016@16:48:42 Deploying iOS test app 
9/12/2016@16:48:42 uninstalling the application 
9/12/2016@16:48:43 installing the application 
9/12/2016@16:51:35 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
9/12/2016@17:12:01 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
9/12/2016@17:12:01 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/9732732894937d3_Fixed_unexpectedConnectHandler_error__dersim-davaod/thali05_samsung-SM-G935F.md)

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

Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
Child process exited with code null on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/9732732894937d3_Fixed_unexpectedConnectHandler_error__dersim-davaod/thali07_samsung-SM-G930F.md)


###iOS Logs
[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/9732732894937d3_Fixed_unexpectedConnectHandler_error__dersim-davaod/iOS_ipad-mini-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/9732732894937d3_Fixed_unexpectedConnectHandler_error__dersim-davaod/iOS_ipad-air-2-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/9732732894937d3_Fixed_unexpectedConnectHandler_error__dersim-davaod/iOS_iphone-5s-1.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/9732732894937d3_Fixed_unexpectedConnectHandler_error__dersim-davaod/iOS_iphone-6-2.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/9732732894937d3_Fixed_unexpectedConnectHandler_error__dersim-davaod/iOS_iphone-5s-mfts.md)

[server](https://github.com/ThaliTester/TestResults/blob/9732732894937d3_Fixed_unexpectedConnectHandler_error__dersim-davaod/iOS_server.md)





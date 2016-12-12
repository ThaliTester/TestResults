#### Test 912434547c1b96c Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":2}}
2016-12-12 17:33:23 - INFO HttpServer: 'listening on *:3000'

2016-12-12 17:38:23 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_912434547c1b96c/test/TestServer/index.js:45:9)
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
12/12/2016@18:30:22 Getting the list of iOS devices 
12/12/2016@18:30:23 Deploying iOS test app 
12/12/2016@18:30:23 uninstalling the application 
12/12/2016@18:30:24 installing the application 
12/12/2016@18:32:28 ios: child process exited with code 253 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
12/12/2016@18:32:28 ios: child process exited with code 253 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
12/12/2016@18:53:42 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
12/12/2016@18:53:42 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
12/12/2016@18:53:42 ios: child process exited with code null on device 83aab4e7f1dde3becec287ac4c44362439d2595b 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/912434547c1b96c_added_logs_vasilevskayaem/thali05_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/912434547c1b96c_added_logs_vasilevskayaem/thali07_samsung-SM-G930F.md)


###iOS Logs
[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/912434547c1b96c_added_logs_vasilevskayaem/iOS_ipad-mini-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/912434547c1b96c_added_logs_vasilevskayaem/iOS_ipad-air-2-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/912434547c1b96c_added_logs_vasilevskayaem/iOS_iphone-5s-1.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/912434547c1b96c_added_logs_vasilevskayaem/iOS_iphone-6-2.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/912434547c1b96c_added_logs_vasilevskayaem/iOS_iphone-5s-mfts.md)

[server](https://github.com/ThaliTester/TestResults/blob/912434547c1b96c_added_logs_vasilevskayaem/iOS_server.md)





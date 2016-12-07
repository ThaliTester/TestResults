#### Test 96293062c9b8e19 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":2}}
2016-12-07 16:13:14 - INFO HttpServer: 'listening on *:3000'

2016-12-07 16:18:14 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_96293062c9b8e19/test/TestServer/index.js:45:9)
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
7/12/2016@17:10:26 Getting the list of iOS devices 
7/12/2016@17:10:27 Deploying iOS test app 
7/12/2016@17:10:27 uninstalling the application 
7/12/2016@17:10:28 installing the application 
7/12/2016@17:33:46 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/96293062c9b8e19_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/thali05_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/96293062c9b8e19_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/thali07_samsung-SM-G930F.md)


###iOS Logs
[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/96293062c9b8e19_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_ipad-mini-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/96293062c9b8e19_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_ipad-air-2-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/96293062c9b8e19_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_iphone-5s-1.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/96293062c9b8e19_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_iphone-6-2.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/96293062c9b8e19_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_iphone-5s-mfts.md)

[server](https://github.com/ThaliTester/TestResults/blob/96293062c9b8e19_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_server.md)





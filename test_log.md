#### Test 962930629a6bd77 Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":2}}
2016-12-07 15:23:09 - INFO HttpServer: 'listening on *:3000'

2016-12-07 15:24:38 - DEBUG HttpServer: 'device presented, name: 'samsung-SM-G930F', uuid: '4099bdb2-40ac-48e4-b2eb-c52f3bc73395', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-12-07 15:24:38 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-12-07 15:28:09 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_962930629a6bd77/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-12-07 15:28:09 - INFO HttpServer: 'Socket to device name: 'samsung-SM-G930F' disconnected, reason: 'undefined''


 
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
7/12/2016@16:20:04 Getting the list of iOS devices 
7/12/2016@16:20:05 Deploying iOS test app 
7/12/2016@16:20:05 uninstalling the application 
7/12/2016@16:20:06 installing the application 
7/12/2016@16:43:24 ios: child process exited with code null on device bffa901fefdea07f59339a6737776943349f5077 
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
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/962930629a6bd77_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/thali05_samsung-SM-G935F.md)

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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/962930629a6bd77_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/thali07_samsung-SM-G930F.md)


###iOS Logs
[ipad-mini-mfts](https://github.com/ThaliTester/TestResults/blob/962930629a6bd77_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_ipad-mini-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/962930629a6bd77_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_ipad-air-2-1.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/962930629a6bd77_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_iphone-5s-1.md)

[iphone-6-2](https://github.com/ThaliTester/TestResults/blob/962930629a6bd77_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_iphone-6-2.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/962930629a6bd77_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_iphone-5s-mfts.md)

[server](https://github.com/ThaliTester/TestResults/blob/962930629a6bd77_10_attempts_run_socket_tests__1229_and_branch_vNext_yarong_417_812_1205_vasilevskayaem/iOS_server.md)





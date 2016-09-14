#### Test 85067679b83ffc4 Logs

#### Test Server Logs
```
Error: Command failed: 2016-09-14 10:40:43 - error: uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_85067679b83ffc4/test/TestServer/TestFramework.js:51:11)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)'

IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":2}}
2016-09-14 10:35:43 - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-09-14 10:40:43 - error: uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_85067679b83ffc4/test/TestServer/TestFramework.js:51:11)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)'


```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali06
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
child process exited with code null on device ce0616068b9f212302 
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:null 
child process exited with code null on device ENU7N16516000107 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/85067679b83ffc4_Do_not_merge__CI_test_andrew-aladev/thali06_samsung-SM-G930F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/85067679b83ffc4_Do_not_merge__CI_test_andrew-aladev/thali06_Huawei-Nexus 6P.md)





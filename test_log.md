#### Test 8596714975a1490 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":2}}
2016-09-20T13:04:13.122Z - info: Require 0 ios devices

2016-09-20T13:04:13.141Z - info: Require 2 android devices

2016-09-20T13:04:13.200Z - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali04
Console output:
```
Trying to deploy app to android: ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to android ce061606e320561102
App was succesfully deployed to ce061606e320561102
Trying to deploy app to android: ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to android ce0616068b9f212302
App was succesfully deployed to ce0616068b9f212302
Trying to start application ThaliTest on ce061606e320561102
Trying to start application ThaliTest on ce0616068b9f212302
App was succesfully started on ce061606e320561102
-------------------------------------------
App was succesfully started on ce0616068b9f212302
-------------------------------------------
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:0 
Child process exited with code 0 on device ce061606e320561102
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:0 
Child process exited with code 0 on device ce0616068b9f212302
Android task is completed. [FAILED]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8596714975a1490_Fixed_typo___connect__-___multiConnect__artemjackson/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/8596714975a1490_Fixed_typo___connect__-___multiConnect__artemjackson/thali04_samsung-SM-G930F.md)





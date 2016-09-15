#### Test 85019474898df24 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-15T11:02:46.184Z - info: Require 0 ios devices

2016-09-15T11:02:46.202Z - info: Require 3 android devices

2016-09-15T11:02:46.261Z - info: listening on *:3000

2016-09-15T11:03:01.689Z - debug: Device presented: Huawei-Nexus 6P (72e281b1-dd7c-487d-90c1-2f10785ac48b) - android 6.0.1

2016-09-15T11:26:16.674Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Deploying app to android: ENU7N16516000107Deploying to android ENU7N16516000107Deploying app to android: ce061606e320561102Deploying to android ce061606e320561102Deploying app to android: ce0616068b9f212302Deploying to android ce0616068b9f212302Trying to start application ThaliTest on ENU7N16516000107Trying to start application ThaliTest on ce061606e320561102Trying to start application ThaliTest on ce0616068b9f212302Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali04
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:0 
child process exited with code 0 on device ENU7N16516000107 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:null 
child process exited with code null on device ce061606e320561102 
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:0 
child process exited with code 0 on device ce0616068b9f212302 
Android task is completed. [FAILED]
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/85019474898df24_DO_NOT_MERGE_CI_smoke_test__74_mlesnic/thali04_Huawei-Nexus 6P.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/85019474898df24_DO_NOT_MERGE_CI_smoke_test__74_mlesnic/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/85019474898df24_DO_NOT_MERGE_CI_smoke_test__74_mlesnic/thali04_samsung-SM-G930F.md)





#### Test 85019474dae17e3 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-15T13:05:50.694Z - info: Require 0 ios devices

2016-09-15T13:05:50.712Z - info: Require 3 android devices

2016-09-15T13:05:50.769Z - info: listening on *:3000

2016-09-15T13:06:18.032Z - debug: Device presented: Huawei-Nexus 6P (6fe34158-8539-4fed-aca3-af479a53de44) - android 6.0.1

2016-09-15T13:29:32.596Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close


 
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

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:0 
child process exited with code 0 on device ENU7N16516000107 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:0 
child process exited with code 0 on device ce061606e320561102 
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
child process exited with code null on device ce0616068b9f212302 
Android task is completed. [FAILED]
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/85019474dae17e3_DO_NOT_MERGE_CI_smoke_test__74_mlesnic/thali04_Huawei-Nexus 6P.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/85019474dae17e3_DO_NOT_MERGE_CI_smoke_test__74_mlesnic/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/85019474dae17e3_DO_NOT_MERGE_CI_smoke_test__74_mlesnic/thali04_samsung-SM-G930F.md)





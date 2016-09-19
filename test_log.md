#### Test 8504691185ffef1 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-09-19T12:38:37.766Z - info: Require 4 ios devices

2016-09-19T12:38:37.787Z - info: Require 3 android devices

2016-09-19T12:38:37.846Z - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
19/9/2016@14:34:43 Getting the list of iOS devices 
19/9/2016@14:34:44 Deploying iOS test app 
19/9/2016@14:34:44 uninstalling the application 
19/9/2016@14:34:44 installing the application 
19/9/2016@14:58:03 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
19/9/2016@14:58:03 ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/8504691185ffef1_DO_NOT_MERGE_-_CI_smoke_test__74_mlesnic/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/8504691185ffef1_DO_NOT_MERGE_-_CI_smoke_test__74_mlesnic/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/8504691185ffef1_DO_NOT_MERGE_-_CI_smoke_test__74_mlesnic/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/8504691185ffef1_DO_NOT_MERGE_-_CI_smoke_test__74_mlesnic/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/8504691185ffef1_DO_NOT_MERGE_-_CI_smoke_test__74_mlesnic/iOS_server.md)




###Android Logs
####Node name: thali04
Console output:
```

Trying to deploy app to android: ENU7N16516000107

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Deploying to android ENU7N16516000107

App was succesfully deployed to ENU7N16516000107

Trying to deploy app to android: ce061606e320561102

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Deploying to android ce061606e320561102

App was succesfully deployed to ce061606e320561102

Trying to deploy app to android: ce0616068b9f212302

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Deploying to android ce0616068b9f212302

App was succesfully deployed to ce0616068b9f212302

Trying to start application ThaliTest on ENU7N16516000107

Trying to start application ThaliTest on ce061606e320561102

Trying to start application ThaliTest on ce0616068b9f212302
STOP log received from ce061606e320561102
Test has SUCCEED
STOP log received from ce0616068b9f212302
Test has SUCCEED
Device test finished on ce061606e320561102 
Device test finished on ce0616068b9f212302 
STOP log received from ENU7N16516000107
Test has SUCCEED
Device test finished on ENU7N16516000107 
Android task is completed.
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8504691185ffef1_DO_NOT_MERGE_-_CI_smoke_test__74_mlesnic/thali04_Huawei-Nexus 6P.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8504691185ffef1_DO_NOT_MERGE_-_CI_smoke_test__74_mlesnic/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/8504691185ffef1_DO_NOT_MERGE_-_CI_smoke_test__74_mlesnic/thali04_samsung-SM-G930F.md)



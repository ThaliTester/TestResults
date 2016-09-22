#### Test 8617437972ae596 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-09-22T08:18:42.874Z - info: Require 4 ios devices

2016-09-22T08:18:42.892Z - info: Require 3 android devices

2016-09-22T08:18:42.951Z - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
22/9/2016@10:14:21 Getting the list of iOS devices 
22/9/2016@10:14:22 Deploying iOS test app 
22/9/2016@10:14:22 uninstalling the application 
22/9/2016@10:14:23 installing the application 
22/9/2016@10:16:18 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : No Error
```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/8617437972ae596_V_next_avsyuchenya_946_test_baydet/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/8617437972ae596_V_next_avsyuchenya_946_test_baydet/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/8617437972ae596_V_next_avsyuchenya_946_test_baydet/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/8617437972ae596_V_next_avsyuchenya_946_test_baydet/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/8617437972ae596_V_next_avsyuchenya_946_test_baydet/iOS_server.md)




###Android Logs
####Node name: thali05
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102
Stopping app on  ENU7N16516000107
Uninstalling app on  ENU7N16516000107

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Deploying to ENU7N16516000107
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000107

Starting application ThaliTest on ce0616068b9f212302

Starting application ThaliTest on ce061606e320561102

Starting application ThaliTest on ENU7N16516000107

App was succesfully started on ce0616068b9f212302

App was succesfully started on ce061606e320561102

App was succesfully started on ENU7N16516000107

STOP log received from ce061606e320561102
Test has SUCCEED

STOP log received from ce0616068b9f212302
Test has SUCCEED

STOP log received from ENU7N16516000107
Test has SUCCEED

Device test finished on ce0616068b9f212302 
Device test finished on ce061606e320561102 
Device test finished on ENU7N16516000107 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/8617437972ae596_V_next_avsyuchenya_946_test_baydet/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8617437972ae596_V_next_avsyuchenya_946_test_baydet/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8617437972ae596_V_next_avsyuchenya_946_test_baydet/thali05_Huawei-Nexus 6P.md)



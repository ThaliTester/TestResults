#### Test 8670851855de81a Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-09-26T09:48:58.512Z - info: Require 4 ios devices

2016-09-26T09:48:58.531Z - info: Require 3 android devices

2016-09-26T09:48:58.588Z - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
26/9/2016@11:44:14 Getting the list of iOS devices 
26/9/2016@11:44:15 Deploying iOS test app 
26/9/2016@11:44:15 uninstalling the application 
26/9/2016@11:44:16 installing the application 
26/9/2016@12:07:34 ios: child process exited with code null on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
true

```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/8670851855de81a__1146_remove_shrinkwrap_chapko/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/8670851855de81a__1146_remove_shrinkwrap_chapko/iOS_Iphone6-2.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/8670851855de81a__1146_remove_shrinkwrap_chapko/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/8670851855de81a__1146_remove_shrinkwrap_chapko/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/8670851855de81a__1146_remove_shrinkwrap_chapko/iOS_server.md)




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

Device test finished on ce061606e320561102 
STOP log received from ce0616068b9f212302
Test has SUCCEED

Device test finished on ce0616068b9f212302 
STOP log received from ENU7N16516000107
Test has SUCCEED

Device test finished on ENU7N16516000107 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/8670851855de81a__1146_remove_shrinkwrap_chapko/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8670851855de81a__1146_remove_shrinkwrap_chapko/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8670851855de81a__1146_remove_shrinkwrap_chapko/thali05_Huawei-Nexus 6P.md)



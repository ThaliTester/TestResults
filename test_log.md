#### Test 79763830b1f5deb Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":8}}
2016-08-23T15:05:13.230Z - info: Require 3 ios devices

2016-08-23T15:05:13.251Z - info: Require 8 android devices

2016-08-23T15:05:13.314Z - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
23/8/2016@17:01:15 Getting the list of iOS devices 
23/8/2016@17:01:16 Deploying iOS test app 
23/8/2016@17:01:16 uninstalling the application 
23/8/2016@17:01:17 installing the application 
23/8/2016@17:02:35 ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
23/8/2016@17:02:36 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
23/8/2016@17:02:37 ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device LGD855a6933058 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD855a6933058 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali03_samsung-SM-A300FU.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali03_samsung-SM-A500FU.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Error! Unexpected exit on device HT54GYJ03048 app:com.test.thalitest code:null 
child process exited with code null on device HT54GYJ03048 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali04_samsung-SM-A300FU.md)

[HTC-HTC One M9](https://github.com/ThaliTester/TestResults/blob/79763830b1f5deb_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali04_HTC-HTC One M9.md)





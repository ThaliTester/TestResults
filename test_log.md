#### Test 79763830b0b67a9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":3}}
2016-08-12T11:04:14.689Z - info: Require 3 ios devices

2016-08-12T11:04:14.723Z - info: Require 3 android devices

2016-08-12T11:04:14.784Z - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
12/8/2016@13:00:13 Getting the list of iOS devices 
12/8/2016@13:00:14 Deploying iOS test app 
12/8/2016@13:00:14 uninstalling the application 
12/8/2016@13:00:15 installing the application 
12/8/2016@13:00:38 ios: child process exited with code 253 on device 17df3859480c382d3b761fa2643dde395ced1bd8 
12/8/2016@13:01:28 ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
12/8/2016@13:01:28 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
12/8/2016@13:01:30 ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/79763830b0b67a9_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/79763830b0b67a9_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/79763830b0b67a9_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/79763830b0b67a9_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/79763830b0b67a9_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:0 
child process exited with code 0 on device 0be0c6c6 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79763830b0b67a9_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD855a6933058 Test has  FAILED
Device test finished on LGD855a6933058 
STOP log received from  LGD7228ee9cf5b Test has  FAILED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79763830b0b67a9_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79763830b0b67a9_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali02_LGE-LG-D855.md)





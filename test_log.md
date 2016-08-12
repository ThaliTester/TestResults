#### Test 797638300d10dad Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":4}}
2016-08-12T13:12:51.640Z - info: Require 3 ios devices

2016-08-12T13:12:51.659Z - info: Require 3 android devices

2016-08-12T13:12:51.718Z - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
12/8/2016@15:08:52 Getting the list of iOS devices 
12/8/2016@15:08:53 Deploying iOS test app 
12/8/2016@15:08:53 uninstalling the application 
12/8/2016@15:08:53 installing the application 
12/8/2016@15:10:04 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
12/8/2016@15:10:06 ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
12/8/2016@15:10:06 ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/797638300d10dad_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/797638300d10dad_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/797638300d10dad_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/797638300d10dad_Enhance_CI_to_run_iOS_tests__771_larryonoff/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  0be0c6c6 Test has  FAILED
STOP log received from  ZX1G429CRK Test has  FAILED
Device test finished on ZX1G429CRK 
Device test finished on 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/797638300d10dad_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/797638300d10dad_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  FAILED
Device test finished on LGD7228ee9cf5b 
STOP log received from  LGD855a6933058 Test has  FAILED
Device test finished on LGD855a6933058 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/797638300d10dad_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/797638300d10dad_Enhance_CI_to_run_iOS_tests__771_larryonoff/thali02_LGE-LG-D855.md)





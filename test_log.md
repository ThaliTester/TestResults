#### Test 80912877ea0a40f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-08-11T10:03:48.159Z - info: Require 3 ios devices

2016-08-11T10:03:48.185Z - info: Require 3 android devices

2016-08-11T10:03:48.245Z - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
11/8/2016@11:59:45 Getting the list of iOS devices 
11/8/2016@11:59:46 Deploying iOS test app 
11/8/2016@11:59:46 uninstalling the application 
11/8/2016@11:59:47 installing the application 
11/8/2016@12:00:10 ios: child process exited with code 253 on device 17df3859480c382d3b761fa2643dde395ced1bd8 
11/8/2016@12:00:58 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
11/8/2016@12:00:58 ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
11/8/2016@12:01:01 ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/80912877ea0a40f_Check_IOS_devices_based_on_771_jareksl/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/80912877ea0a40f_Check_IOS_devices_based_on_771_jareksl/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/80912877ea0a40f_Check_IOS_devices_based_on_771_jareksl/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/80912877ea0a40f_Check_IOS_devices_based_on_771_jareksl/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/80912877ea0a40f_Check_IOS_devices_based_on_771_jareksl/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  0be0c6c6 Test has  FAILED
Device test finished on 0be0c6c6 
STOP log received from  ZX1G429CRK Test has  FAILED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/80912877ea0a40f_Check_IOS_devices_based_on_771_jareksl/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/80912877ea0a40f_Check_IOS_devices_based_on_771_jareksl/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD855a6933058 Test has  FAILED
Device test finished on LGD855a6933058 
STOP log received from  LGD7228ee9cf5b Test has  FAILED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/80912877ea0a40f_Check_IOS_devices_based_on_771_jareksl/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/80912877ea0a40f_Check_IOS_devices_based_on_771_jareksl/thali02_LGE-LG-D855.md)





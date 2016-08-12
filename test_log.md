#### Test 80912877664003a Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-08-12T07:22:04.972Z - info: Require 3 ios devices

2016-08-12T07:22:04.991Z - info: Require 3 android devices

2016-08-12T07:22:05.051Z - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
12/8/2016@09:18:22 Getting the list of iOS devices 
12/8/2016@09:18:23 Deploying iOS test app 
12/8/2016@09:18:23 uninstalling the application 
12/8/2016@09:18:24 installing the application 
12/8/2016@09:18:48 ios: child process exited with code 253 on device 17df3859480c382d3b761fa2643dde395ced1bd8 
12/8/2016@09:19:37 ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
12/8/2016@09:19:38 ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
12/8/2016@09:19:42 ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/80912877664003a_Check_IOS_devices_based_on_771_jareksl/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/80912877664003a_Check_IOS_devices_based_on_771_jareksl/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/80912877664003a_Check_IOS_devices_based_on_771_jareksl/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/80912877664003a_Check_IOS_devices_based_on_771_jareksl/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/80912877664003a_Check_IOS_devices_based_on_771_jareksl/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  41009dc6f26f910b Test has  FAILED
Device test finished on 41009dc6f26f910b 
STOP log received from  0be0c6c6 Test has  FAILED
Device test finished on 0be0c6c6 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/80912877664003a_Check_IOS_devices_based_on_771_jareksl/thali01_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/80912877664003a_Check_IOS_devices_based_on_771_jareksl/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD855a6933058 Test has  FAILED
Device test finished on LGD855a6933058 
STOP log received from  LGD7228ee9cf5b Test has  FAILED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/80912877664003a_Check_IOS_devices_based_on_771_jareksl/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/80912877664003a_Check_IOS_devices_based_on_771_jareksl/thali02_LGE-LG-D855.md)





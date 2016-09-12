#### Test 846487400fb5c63 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":5,"android":9}}
2016-09-12T11:12:10.815Z - info: Require 5 ios devices

2016-09-12T11:12:10.833Z - info: Require 9 android devices

2016-09-12T11:12:10.892Z - info: listening on *:3000


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
12/9/2016@13:08:11 Getting the list of iOS devices 
12/9/2016@13:08:12 Deploying iOS test app 
12/9/2016@13:08:12 uninstalling the application 
12/9/2016@13:08:13 installing the application 
12/9/2016@13:08:31 ios: child process exited with code 253 on device f70cda60583ea0f895d05ea355cd125983c27594 
12/9/2016@13:09:30 ios: child process exited with code 253 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
12/9/2016@13:09:34 ios: child process exited with code 253 on device 7ed231f0829a4ace34162e6c18308bcd995bc25a 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/iOS_Iphone6-1.md)

[Iphone6-2](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/iOS_Iphone6-2.md)

[Iphone6sPlus-1](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/iOS_Iphone6sPlus-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/thali01_samsung-SM-G900F.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD855a6933058 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD855a6933058 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/thali04_samsung-SM-A300FU.md)

####Node name: thali05
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  ce061606e320561102 Test has  SUCCEEDED
STOP log received from  e8c09bab Test has  SUCCEEDED
Device test finished on ce061606e320561102 
Device test finished on e8c09bab 
Android task is completed. [SUCCESS]
```
[samsung-SM-T719](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/thali05_samsung-SM-T719.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/846487400fb5c63_fix__Cannot_find_module__child-process-promise__on_CI_in_vNext__1012_larryonoff/thali05_samsung-SM-G935F.md)





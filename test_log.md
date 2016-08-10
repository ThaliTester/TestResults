#### Test 79751015c075caf Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-10T12:14:15.114Z - info: Require 0 ios devices

2016-08-10T12:14:15.133Z - info: Require 4 android devices

2016-08-10T12:14:15.193Z - info: listening on *:3000


 
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
####Node name: thali01
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  0be0c6c6 Test has  FAILED
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015c075caf_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015c075caf_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015c075caf_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015c075caf_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)





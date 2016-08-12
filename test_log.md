#### Test 7975101567d962b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-08-12T10:20:06.582Z - info: Require 0 ios devices

2016-08-12T10:20:06.601Z - info: Require 3 android devices

2016-08-12T10:20:06.659Z - info: listening on *:3000

2016-08-12T10:20:26.678Z - debug: Device presented: LGE-LG-D855 (9ab99c9a-d9ba-4613-b4d4-7d51b33044f2) - android 5.0

2016-08-12T10:20:40.918Z - debug: Device presented: LGE-LG-D722 (e7907371-f17e-4599-879b-ba10ec01a9a2) - android 5.0.2

2016-08-12T10:43:33.782Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-12T10:43:35.914Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:0 
child process exited with code 0 on device 0be0c6c6 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/7975101567d962b_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/7975101567d962b_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/7975101567d962b_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)





#### Test 80768856ffd4d9b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-08-11T14:12:15.440Z - info: Require 3 ios devices

2016-08-11T14:12:15.458Z - info: Require 3 android devices

2016-08-11T14:12:15.524Z - info: listening on *:3000

2016-08-11T14:13:05.480Z - debug: Device presented: LGE-LG-D855 (f2645ce0-dfdd-430d-8465-d905111a5a6b) - android 5.0

2016-08-11T14:13:10.883Z - debug: Device presented: LGE-LG-D722 (7aefa38b-a329-4b5d-ba13-65ad6ffbd7fa) - android 5.0.2

2016-08-11T14:35:36.945Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-11T14:35:39.290Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/80768856ffd4d9b__697_Fixed_setInterval_battery_abuse_artemjackson/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/80768856ffd4d9b__697_Fixed_setInterval_battery_abuse_artemjackson/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/80768856ffd4d9b__697_Fixed_setInterval_battery_abuse_artemjackson/thali02_LGE-LG-D855.md)





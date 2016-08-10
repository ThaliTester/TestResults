#### Test 797510154a934e8 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":7}}
2016-08-10T08:44:31.364Z - info: Require 0 ios devices

2016-08-10T08:44:31.383Z - info: Require 7 android devices

2016-08-10T08:44:31.443Z - info: listening on *:3000

2016-08-10T08:44:33.010Z - debug: Device presented: samsung-SM-G900F (3634e726-0e6b-4c42-8389-e9ffdff83816) - android 6.0.1

2016-08-10T08:44:34.051Z - debug: Device presented: samsung-SM-G900F (3634e726-0e6b-4c42-8389-e9ffdff83816) - android 6.0.1

2016-08-10T08:44:34.056Z - info: Updating existing device: samsung-SM-G900F (3634e726-0e6b-4c42-8389-e9ffdff83816)

2016-08-10T08:44:34.546Z - debug: Device presented: samsung-SM-G900F (a7eeca5b-816d-4a29-af4f-c00ff38798f0) - android 6.0.1

2016-08-10T08:44:35.519Z - debug: Device presented: samsung-SM-G900F (a7eeca5b-816d-4a29-af4f-c00ff38798f0) - android 6.0.1

2016-08-10T08:44:35.520Z - info: Updating existing device: samsung-SM-G900F (a7eeca5b-816d-4a29-af4f-c00ff38798f0)

2016-08-10T08:44:36.184Z - debug: Device presented: motorola-Nexus 6 (e8275298-4da0-4fd4-8576-be30d78e3175) - android 6.0.1

2016-08-10T08:44:37.180Z - debug: Device presented: motorola-Nexus 6 (e8275298-4da0-4fd4-8576-be30d78e3175) - android 6.0.1

2016-08-10T08:44:37.182Z - info: Updating existing device: motorola-Nexus 6 (e8275298-4da0-4fd4-8576-be30d78e3175)

2016-08-10T08:45:18.783Z - debug: Device presented: LGE-LG-D855 (72f1b8a7-ad73-4667-aedf-ecf667dc4457) - android 5.0

2016-08-10T08:45:33.092Z - debug: Device presented: LGE-LG-D722 (0b16c452-46a7-4b27-9e9b-451048da1771) - android 5.0.2

2016-08-10T09:05:00.268Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-10T09:05:02.720Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-10T09:05:05.203Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-10T09:07:58.641Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-10T09:08:00.912Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/797510154a934e8_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/797510154a934e8_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/797510154a934e8_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/797510154a934e8_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)

####Node name: thali05
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/797510154a934e8_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_samsung-SM-G900F.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/797510154a934e8_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-Nexus 5.md)

####Node name: thali06
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 03157df360a1882a app:com.test.thalitest code:0 
child process exited with code 0 on device 03157df360a1882a 
Android task is completed. [FAILED]
```
[samsung-SM-G920F](https://github.com/ThaliTester/TestResults/blob/797510154a934e8_Check_811_failures_in_CI_do_not_merge__czyzm/thali06_samsung-SM-G920F.md)





#### Test 79751015d87d04c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-10T13:11:17.423Z - info: Require 0 ios devices

2016-08-10T13:11:17.442Z - info: Require 4 android devices

2016-08-10T13:11:17.500Z - info: listening on *:3000

2016-08-10T13:11:22.272Z - debug: Device presented: samsung-SM-G900F (bb3b36a2-121d-4e8f-8824-20f2a3e16e14) - android 6.0.1

2016-08-10T13:11:23.291Z - debug: Device presented: samsung-SM-G900F (bb3b36a2-121d-4e8f-8824-20f2a3e16e14) - android 6.0.1

2016-08-10T13:11:23.297Z - info: Updating existing device: samsung-SM-G900F (bb3b36a2-121d-4e8f-8824-20f2a3e16e14)

2016-08-10T13:12:01.494Z - debug: Device presented: LGE-LG-D855 (94d1a93e-bcd1-47f9-939d-daabfc8f86e8) - android 5.0

2016-08-10T13:12:18.689Z - debug: Device presented: LGE-LG-D722 (033f902b-ed02-4024-9909-7df292618c66) - android 5.0.2

2016-08-10T13:32:00.152Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-10T13:34:44.535Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-10T13:34:46.771Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015d87d04c_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015d87d04c_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015d87d04c_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015d87d04c_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)





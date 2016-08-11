#### Test 797510152beef86 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-11T04:35:28.535Z - info: Require 0 ios devices

2016-08-11T04:35:28.563Z - info: Require 4 android devices

2016-08-11T04:35:28.618Z - info: listening on *:3000

2016-08-11T04:35:31.917Z - debug: Device presented: samsung-SM-G900F (2095282a-9fba-43b0-bf37-2ac8a8d0920b) - android 6.0.1

2016-08-11T04:35:32.958Z - debug: Device presented: samsung-SM-G900F (2095282a-9fba-43b0-bf37-2ac8a8d0920b) - android 6.0.1

2016-08-11T04:35:32.964Z - info: Updating existing device: samsung-SM-G900F (2095282a-9fba-43b0-bf37-2ac8a8d0920b)

2016-08-11T04:37:06.259Z - debug: Device presented: LGE-LG-D855 (79d7e8b4-3961-456d-a04e-453814aa1b5e) - android 5.0

2016-08-11T04:37:17.472Z - debug: Device presented: LGE-LG-D722 (d6504aae-0715-44f2-83e2-7901aaf5177b) - android 5.0.2

2016-08-11T04:55:48.924Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-11T04:58:50.330Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-11T04:58:52.509Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/797510152beef86_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/797510152beef86_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/797510152beef86_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/797510152beef86_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)





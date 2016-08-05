#### Test 79751015abe04ee Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":5}}
2016-08-05T09:27:17.583Z - info: Require 3 ios devices

2016-08-05T09:27:17.602Z - info: Require 3 android devices

2016-08-05T09:27:17.668Z - info: listening on *:3000

2016-08-05T09:27:20.822Z - debug: Device presented: samsung-SM-G900F (149632b7-c6d6-4d4b-8512-24a32c258ee2) - android 6.0.1

2016-08-05T09:27:21.737Z - debug: Device presented: samsung-SM-G900F (149632b7-c6d6-4d4b-8512-24a32c258ee2) - android 6.0.1

2016-08-05T09:27:21.739Z - info: Updating existing device: samsung-SM-G900F (149632b7-c6d6-4d4b-8512-24a32c258ee2)

2016-08-05T09:27:22.950Z - debug: Device presented: motorola-Nexus 6 (a2d66c6c-9ee0-4cc8-b8d1-5f8c7b696998) - android 6.0.1

2016-08-05T09:27:23.942Z - debug: Device presented: motorola-Nexus 6 (a2d66c6c-9ee0-4cc8-b8d1-5f8c7b696998) - android 6.0.1

2016-08-05T09:27:23.943Z - info: Updating existing device: motorola-Nexus 6 (a2d66c6c-9ee0-4cc8-b8d1-5f8c7b696998)

2016-08-05T09:28:03.833Z - debug: Device presented: samsung-SM-N9005 (91bf25b7-7819-4274-b3cc-7dd490cb5767) - android 5.0

2016-08-05T09:28:19.594Z - debug: Device presented: LGE-LG-D722 (776bb816-f496-40bb-8d35-cfa2e87b58fe) - android 5.0.2

2016-08-05T09:47:04.117Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-05T09:47:06.186Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-05T09:50:45.089Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-05T09:50:47.965Z - info: Socket to device LGE-LG-D722 disconnected: transport close


 
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
####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device LGD855a6933058 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD855a6933058 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/79751015abe04ee_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015abe04ee_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015abe04ee_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:0 
child process exited with code 0 on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015abe04ee_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015abe04ee_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_samsung-SM-G900F.md)





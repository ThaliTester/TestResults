#### Test 796897752095895 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":5}}
2016-08-08T10:06:52.580Z - info: Require 3 ios devices

2016-08-08T10:06:52.600Z - info: Require 3 android devices

2016-08-08T10:06:52.658Z - info: listening on *:3000

2016-08-08T10:06:55.293Z - debug: Device presented: samsung-SM-G900F (a93628bb-3b0c-46df-a845-e64f7e20cac9) - android 6.0.1

2016-08-08T10:06:56.299Z - debug: Device presented: samsung-SM-G900F (a93628bb-3b0c-46df-a845-e64f7e20cac9) - android 6.0.1

2016-08-08T10:06:56.302Z - info: Updating existing device: samsung-SM-G900F (a93628bb-3b0c-46df-a845-e64f7e20cac9)

2016-08-08T10:07:48.659Z - debug: Device presented: samsung-SM-N9005 (a054e0af-eebb-4c67-b488-51aa17f28e3b) - android 5.0

2016-08-08T10:07:51.681Z - debug: Device presented: LGE-LG-D855 (b7e90914-2cda-4d49-a37b-64178e1b46b4) - android 5.0

2016-08-08T10:08:06.038Z - debug: Device presented: LGE-LG-D722 (9cbf3c04-c2a1-4ab7-96ef-673844f3e379) - android 5.0.2

2016-08-08T10:26:26.167Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-08T10:30:20.449Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-08T10:30:23.360Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-08T10:30:25.411Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/796897752095895_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/796897752095895_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/796897752095895_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D855.md)

####Node name: thali08
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/796897752095895_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/796897752095895_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_samsung-SM-G900F.md)





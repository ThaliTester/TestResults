#### Test 79689775603fe2e Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":5}}
2016-08-08T13:45:53.418Z - info: Require 3 ios devices

2016-08-08T13:45:53.438Z - info: Require 3 android devices

2016-08-08T13:45:53.497Z - info: listening on *:3000

2016-08-08T13:45:58.063Z - debug: Device presented: samsung-SM-G900F (a5b5fab6-1c7c-4d9e-be45-fff0709d66e8) - android 6.0.1

2016-08-08T13:45:59.045Z - debug: Device presented: samsung-SM-G900F (a5b5fab6-1c7c-4d9e-be45-fff0709d66e8) - android 6.0.1

2016-08-08T13:45:59.047Z - info: Updating existing device: samsung-SM-G900F (a5b5fab6-1c7c-4d9e-be45-fff0709d66e8)

2016-08-08T13:46:50.425Z - debug: Device presented: samsung-SM-N9005 (5268d652-9411-44d6-b24c-a3d0b01ae7c0) - android 5.0

2016-08-08T13:47:02.275Z - debug: Device presented: LGE-LG-D855 (ed907c31-a853-4fd0-94b3-a431a034f1f3) - android 5.0

2016-08-08T13:47:06.342Z - debug: Device presented: LGE-LG-D722 (9f29f4a0-ed8c-4817-9ddd-c9010437ca70) - android 5.0.2

2016-08-08T14:05:36.064Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-08T14:09:31.677Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-08T14:09:34.410Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-08T14:09:36.333Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/79689775603fe2e_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79689775603fe2e_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79689775603fe2e_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  ZX1G429CRK Test has  FAILED
Device test finished on ZX1G429CRK 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79689775603fe2e_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79689775603fe2e_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_samsung-SM-G900F.md)





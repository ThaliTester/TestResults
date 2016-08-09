#### Test 796897756520203 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-09T13:35:46.653Z - info: Require 3 ios devices

2016-08-09T13:35:46.672Z - info: Require 3 android devices

2016-08-09T13:35:46.731Z - info: listening on *:3000

2016-08-09T13:35:49.441Z - debug: Device presented: LGE-LG-D855 (5d923ead-c116-4503-9702-cb1e6150b90d) - android 5.0

2016-08-09T13:35:50.345Z - debug: Device presented: LGE-LG-D722 (5effe25a-b42c-4bdc-9fd8-110f3f0a4ffb) - android 5.0.2

2016-08-09T13:35:50.402Z - debug: Device presented: LGE-LG-D855 (5d923ead-c116-4503-9702-cb1e6150b90d) - android 5.0

2016-08-09T13:35:50.404Z - info: Updating existing device: LGE-LG-D855 (5d923ead-c116-4503-9702-cb1e6150b90d)

2016-08-09T13:35:51.194Z - debug: Device presented: LGE-LG-D722 (5effe25a-b42c-4bdc-9fd8-110f3f0a4ffb) - android 5.0.2

2016-08-09T13:35:51.195Z - info: Updating existing device: LGE-LG-D722 (5effe25a-b42c-4bdc-9fd8-110f3f0a4ffb)

2016-08-09T13:37:32.595Z - debug: Device presented: samsung-SM-G900F (cb672944-a056-4c41-a4ba-d2e6919b15d5) - android 6.0.1

2016-08-09T13:55:58.019Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-09T13:56:00.039Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-09T13:59:41.812Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device LGD855a6933058 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD855a6933058 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/796897756520203_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/796897756520203_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D855.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/796897756520203_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_samsung-SM-G900F.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/796897756520203_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_motorola-Nexus 6.md)





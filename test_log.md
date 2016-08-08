#### Test 796897758e11f09 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-08T15:10:06.710Z - info: Require 3 ios devices

2016-08-08T15:10:06.730Z - info: Require 3 android devices

2016-08-08T15:10:06.787Z - info: listening on *:3000

2016-08-08T15:11:04.821Z - debug: Device presented: samsung-SM-N9005 (6c1a7c6f-0420-43ac-a063-2b4a52e30385) - android 5.0

2016-08-08T15:11:19.496Z - debug: Device presented: LGE-LG-D722 (2d7cf77a-834b-4c94-b8b1-71a5ef411bd1) - android 5.0.2

2016-08-08T15:33:34.457Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-08T15:33:36.970Z - info: Socket to device LGE-LG-D722 disconnected: transport close


 
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
Error! Unexpected exit on device LGD855a6933058 app:com.test.thalitest code:null 
child process exited with code null on device LGD855a6933058 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/796897758e11f09_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/796897758e11f09_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/796897758e11f09_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:0 
child process exited with code 0 on device 0be0c6c6 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/796897758e11f09_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_samsung-SM-G900F.md)





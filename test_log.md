#### Test 796897751b9e824 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-08-09T14:28:20.774Z - info: Require 3 ios devices

2016-08-09T14:28:20.793Z - info: Require 3 android devices

2016-08-09T14:28:20.851Z - info: listening on *:3000

2016-08-09T14:30:01.145Z - debug: Device presented: LGE-LG-D855 (c606bb53-ed12-4316-a5b8-4d61663f1abc) - android 5.0

2016-08-09T14:30:14.465Z - debug: Device presented: LGE-LG-D722 (8fc85ed8-e725-41be-a29e-32875a01101b) - android 5.0.2

2016-08-09T14:51:48.035Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-09T14:51:50.008Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/796897751b9e824_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/796897751b9e824_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/796897751b9e824_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_samsung-SM-G900F.md)





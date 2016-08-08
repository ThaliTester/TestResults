#### Test 79689775691c720 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":5}}
2016-08-08T12:27:20.670Z - info: Require 3 ios devices

2016-08-08T12:27:20.689Z - info: Require 3 android devices

2016-08-08T12:27:20.753Z - info: listening on *:3000

2016-08-08T12:27:24.059Z - debug: Device presented: samsung-SM-G900F (6389ee62-57cc-4f97-9e4c-1a90b721fdd5) - android 6.0.1

2016-08-08T12:27:25.100Z - debug: Device presented: samsung-SM-G900F (6389ee62-57cc-4f97-9e4c-1a90b721fdd5) - android 6.0.1

2016-08-08T12:27:25.104Z - info: Updating existing device: samsung-SM-G900F (6389ee62-57cc-4f97-9e4c-1a90b721fdd5)

2016-08-08T12:28:18.091Z - debug: Device presented: samsung-SM-N9005 (a81ff922-3dbf-4b01-9979-3f36572ff4df) - android 5.0

2016-08-08T12:28:19.624Z - debug: Device presented: LGE-LG-D855 (13fe766f-9b1e-4c85-a2bb-c639da4ef645) - android 5.0

2016-08-08T12:28:33.700Z - debug: Device presented: LGE-LG-D722 (8ea248a9-5727-4c3a-9821-e2b2b6464c1d) - android 5.0.2

2016-08-08T12:46:53.772Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-08T12:50:48.114Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-08T12:50:51.011Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-08T12:50:52.944Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/79689775691c720_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79689775691c720_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79689775691c720_PR_for_CI_test_purposes__issue_777_mlesnic/thali05_LGE-LG-D855.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79689775691c720_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79689775691c720_PR_for_CI_test_purposes__issue_777_mlesnic/thali08_samsung-SM-G900F.md)





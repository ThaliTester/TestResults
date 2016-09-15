#### Test 85019474fcda771 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-15T09:13:07.132Z - info: Require 0 ios devices

2016-09-15T09:13:07.151Z - info: Require 3 android devices

2016-09-15T09:13:07.207Z - info: listening on *:3000

2016-09-15T09:13:18.589Z - debug: Device presented: Huawei-Nexus 6P (133c4c1c-b3b3-4d7f-a1f6-e17860591828) - android 6.0.1

2016-09-15T09:13:18.826Z - debug: Device presented: LGE-LG-H850 (0df96909-63f9-4d99-93f2-2b97128d026b) - android 6.0.1

2016-09-15T09:36:35.661Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close

2016-09-15T09:36:36.769Z - info: Socket to device LGE-LG-H850 disconnected: transport close


 
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
####Node name: thali04
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:0 
child process exited with code 0 on device ce0616068b9f212302 
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:0 
child process exited with code 0 on device ENU7N16516000107 
Error! Unexpected exit on device LGH85049457824 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH85049457824 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/85019474fcda771_DO_NOT_MERGE_CI_smoke_test__74_mlesnic/thali04_samsung-SM-G930F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/85019474fcda771_DO_NOT_MERGE_CI_smoke_test__74_mlesnic/thali04_Huawei-Nexus 6P.md)

[LGE-LG-H850](https://github.com/ThaliTester/TestResults/blob/85019474fcda771_DO_NOT_MERGE_CI_smoke_test__74_mlesnic/thali04_LGE-LG-H850.md)





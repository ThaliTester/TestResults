#### Test 852025183f6a479 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-14T10:51:17.279Z - info: Require 0 ios devices

2016-09-14T10:51:17.298Z - info: Require 3 android devices

2016-09-14T10:51:17.357Z - info: listening on *:3000

2016-09-14T10:53:06.585Z - debug: Device presented: samsung-SM-G930F (6a44cd2b-50b7-442d-894e-3aeb69620ba6) - android 6.0.1

2016-09-14T10:53:23.043Z - debug: Device presented: LGE-LG-H850 (66571510-c01c-4b1c-b013-b14835ca14bc) - android 6.0.1

2016-09-14T11:15:04.247Z - info: Socket to device samsung-SM-G930F disconnected: transport close

2016-09-14T11:15:06.706Z - info: Socket to device LGE-LG-H850 disconnected: transport close


 
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
####Node name: thali06
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:null 
child process exited with code null on device ce0616068b9f212302 
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:0 
child process exited with code 0 on device ENU7N16516000107 
Error! Unexpected exit on device LGH85049457824 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH85049457824 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/852025183f6a479__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali06_samsung-SM-G930F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/852025183f6a479__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali06_Huawei-Nexus 6P.md)

[LGE-LG-H850](https://github.com/ThaliTester/TestResults/blob/852025183f6a479__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali06_LGE-LG-H850.md)





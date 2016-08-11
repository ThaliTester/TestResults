#### Test 807613740d32244 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":4}}
2016-08-11T09:09:18.779Z - info: Require 3 ios devices

2016-08-11T09:09:18.807Z - info: Require 3 android devices

2016-08-11T09:09:18.863Z - info: listening on *:3000

2016-08-11T09:09:23.927Z - debug: Device presented: samsung-SM-G900F (f1c48bba-5e71-45ca-ab14-11fc7d56970a) - android 6.0.1

2016-08-11T09:09:24.945Z - debug: Device presented: samsung-SM-G900F (f1c48bba-5e71-45ca-ab14-11fc7d56970a) - android 6.0.1

2016-08-11T09:09:24.947Z - info: Updating existing device: samsung-SM-G900F (f1c48bba-5e71-45ca-ab14-11fc7d56970a)

2016-08-11T09:10:59.211Z - debug: Device presented: LGE-LG-D855 (ac1e671c-87db-44e5-b3a7-5a3f6df3a6c3) - android 5.0

2016-08-11T09:11:13.627Z - debug: Device presented: LGE-LG-D722 (96f03e93-d285-49bb-83d3-248b9303f73a) - android 5.0.2

2016-08-11T09:29:46.160Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-11T09:32:46.027Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-11T09:32:47.910Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/807613740d32244__777_Additional_native_unit_tests_mlesnic/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/807613740d32244__777_Additional_native_unit_tests_mlesnic/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/807613740d32244__777_Additional_native_unit_tests_mlesnic/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/807613740d32244__777_Additional_native_unit_tests_mlesnic/thali02_LGE-LG-D855.md)





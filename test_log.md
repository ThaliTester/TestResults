#### Test 79751015c29d5b7 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":8}}
2016-08-10T07:33:54.818Z - info: Require 0 ios devices

2016-08-10T07:33:54.837Z - info: Require 8 android devices

2016-08-10T07:33:54.895Z - info: listening on *:3000

2016-08-10T07:33:55.527Z - debug: Device presented: motorola-Nexus 6 (018b8c98-0265-45be-9bb8-c9bf6ea1ab3f) - android 6.0.1

2016-08-10T07:33:55.549Z - debug: Device presented: samsung-SM-G920F (d8f939cd-6a5c-43ec-a11c-71cfec5ebe87) - android 6.0.1

2016-08-10T07:33:56.477Z - debug: Device presented: motorola-Nexus 6 (018b8c98-0265-45be-9bb8-c9bf6ea1ab3f) - android 6.0.1

2016-08-10T07:33:56.479Z - info: Updating existing device: motorola-Nexus 6 (018b8c98-0265-45be-9bb8-c9bf6ea1ab3f)

2016-08-10T07:33:56.550Z - debug: Device presented: samsung-SM-G920F (d8f939cd-6a5c-43ec-a11c-71cfec5ebe87) - android 6.0.1

2016-08-10T07:33:56.551Z - info: Updating existing device: samsung-SM-G920F (d8f939cd-6a5c-43ec-a11c-71cfec5ebe87)

2016-08-10T07:33:59.380Z - debug: Device presented: samsung-SM-G900F (5faa1824-28a7-4bf4-a072-7c5d8634a176) - android 6.0.1

2016-08-10T07:33:59.478Z - debug: Device presented: samsung-SM-G900F (371fbc0f-ab36-44dc-8ecf-87e41c97636b) - android 6.0.1

2016-08-10T07:33:59.754Z - debug: Device presented: LGE-Nexus 5 (9ffe133f-8290-45d5-9f5b-56b90c7595f8) - android 6.0.1

2016-08-10T07:34:00.415Z - debug: Device presented: samsung-SM-G900F (5faa1824-28a7-4bf4-a072-7c5d8634a176) - android 6.0.1

2016-08-10T07:34:00.416Z - info: Updating existing device: samsung-SM-G900F (5faa1824-28a7-4bf4-a072-7c5d8634a176)

2016-08-10T07:34:00.516Z - debug: Device presented: samsung-SM-G900F (371fbc0f-ab36-44dc-8ecf-87e41c97636b) - android 6.0.1

2016-08-10T07:34:00.517Z - info: Updating existing device: samsung-SM-G900F (371fbc0f-ab36-44dc-8ecf-87e41c97636b)

2016-08-10T07:34:00.803Z - debug: Device presented: LGE-Nexus 5 (9ffe133f-8290-45d5-9f5b-56b90c7595f8) - android 6.0.1

2016-08-10T07:34:00.804Z - info: Updating existing device: LGE-Nexus 5 (9ffe133f-8290-45d5-9f5b-56b90c7595f8)

2016-08-10T07:34:40.360Z - debug: Device presented: LGE-LG-D855 (a70e4957-ff0f-4e5e-ba35-71acfba2c1f1) - android 5.0

2016-08-10T07:34:55.658Z - debug: Device presented: LGE-LG-D722 (f43824fb-b41c-4b35-9585-30eac908a592) - android 5.0.2

2016-08-10T07:54:02.428Z - info: Socket to device samsung-SM-G920F disconnected: transport close

2016-08-10T07:54:21.657Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-10T07:54:23.811Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-08-10T07:54:25.752Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-08-10T07:54:28.018Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-08-10T07:57:21.894Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-10T07:57:24.008Z - info: Socket to device LGE-LG-D855 disconnected: transport close


 
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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015c29d5b7_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_motorola-Nexus 6.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015c29d5b7_Check_811_failures_in_CI_do_not_merge__czyzm/thali01_samsung-SM-G900F.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015c29d5b7_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015c29d5b7_Check_811_failures_in_CI_do_not_merge__czyzm/thali02_LGE-LG-D855.md)

####Node name: thali05
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015c29d5b7_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_samsung-SM-G900F.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/79751015c29d5b7_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-Nexus 5.md)

####Node name: thali06
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
STOP log received from  HT4BLJT02274 Test has  SUCCEEDED
Device test finished on HT4BLJT02274 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 03157df360a1882a app:com.test.thalitest code:0 
child process exited with code 0 on device 03157df360a1882a 
Android task is completed. [FAILED]
```
[htc-Nexus 9](https://github.com/ThaliTester/TestResults/blob/79751015c29d5b7_Check_811_failures_in_CI_do_not_merge__czyzm/thali06_htc-Nexus 9.md)

[samsung-SM-G920F](https://github.com/ThaliTester/TestResults/blob/79751015c29d5b7_Check_811_failures_in_CI_do_not_merge__czyzm/thali06_samsung-SM-G920F.md)





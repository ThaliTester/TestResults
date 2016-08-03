#### Test 798805944e41806 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":6}}
2016-08-03T10:36:49.020Z - info: Require 3 ios devices

2016-08-03T10:36:49.039Z - info: Require 3 android devices

2016-08-03T10:36:49.097Z - info: listening on *:3000

2016-08-03T10:36:50.407Z - debug: Device presented: samsung-SM-N9005 (19115ece-6788-4539-aa16-e8be785bad1c) - android 5.0

2016-08-03T10:36:51.398Z - debug: Device presented: samsung-SM-N9005 (19115ece-6788-4539-aa16-e8be785bad1c) - android 5.0

2016-08-03T10:36:51.400Z - info: Updating existing device: samsung-SM-N9005 (19115ece-6788-4539-aa16-e8be785bad1c)

2016-08-03T10:36:51.525Z - debug: Device presented: LGE-LG-D722 (8c47a386-170c-4226-a830-07186dbae9a4) - android 5.0.2

2016-08-03T10:36:52.369Z - debug: Device presented: LGE-LG-D722 (8c47a386-170c-4226-a830-07186dbae9a4) - android 5.0.2

2016-08-03T10:36:52.370Z - info: Updating existing device: LGE-LG-D722 (8c47a386-170c-4226-a830-07186dbae9a4)

2016-08-03T10:37:25.660Z - debug: Device presented: samsung-SM-N910C (d043ea9c-d53a-460d-9964-f8484059858d) - android 6.0.1

2016-08-03T10:37:42.220Z - debug: Device presented: samsung-SM-G900F (57f5663a-4846-43f2-92fb-eb3fce95d613) - android 6.0.1

2016-08-03T10:56:54.937Z - info: Socket to device samsung-SM-N9005 disconnected: transport close

2016-08-03T10:56:57.604Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-03T11:00:45.247Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-08-03T11:00:47.813Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
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
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/798805944e41806_Fixed_typos_and_cases_in_js_files_evabishchevich/thali05_samsung-SM-N9005.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/798805944e41806_Fixed_typos_and_cases_in_js_files_evabishchevich/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/798805944e41806_Fixed_typos_and_cases_in_js_files_evabishchevich/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission


 Marshmallow device. Granting ACCESS_COARSE_LOCATION permission
STOP log received from  ZX1G429CRK Test has  FAILED
Device test finished on ZX1G429CRK 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:0 
child process exited with code 0 on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/798805944e41806_Fixed_typos_and_cases_in_js_files_evabishchevich/thali08_motorola-Nexus 6.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/798805944e41806_Fixed_typos_and_cases_in_js_files_evabishchevich/thali08_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/798805944e41806_Fixed_typos_and_cases_in_js_files_evabishchevich/thali08_samsung-SM-G900F.md)





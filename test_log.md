#### Test 85202518dd4c7ab Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-16T10:39:34.117Z - info: Require 0 ios devices

2016-09-16T10:39:34.135Z - info: Require 3 android devices

2016-09-16T10:39:34.193Z - info: listening on *:3000

2016-09-16T10:41:18.179Z - debug: Device presented: samsung-SM-G935F (2f0a46aa-d2a8-4b8a-af95-6661c013f693) - android 6.0.1

2016-09-16T10:41:18.869Z - debug: Device presented: samsung-SM-G930F (e7e0c5bf-237d-4692-bd50-bd26070ace66) - android 6.0.1

2016-09-16T10:41:35.858Z - debug: Device presented: Huawei-Nexus 6P (d25bf352-afe3-4545-b37f-82765062e0e2) - android 6.0.1

2016-09-16T10:41:35.860Z - info: All 3 android devices are present

2016-09-16T10:41:35.867Z - info: Starting unit test run on 3 android devices

2016-09-16T10:41:36.806Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-09-16T10:41:38.701Z - info: Running on android test: 2. emits incomingConnectionState

2016-09-16T10:41:40.854Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-09-16T10:41:42.632Z - info: Running on android test: 4. native server connections all up

2016-09-16T10:41:44.478Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-09-16T10:41:46.380Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-09-16T10:41:48.224Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-09-16T10:41:51.001Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-09-16T10:41:52.493Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-09-16T10:41:54.389Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-09-16T10:41:56.224Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-09-16T10:41:57.760Z - info: Running on android test: 12. Coordinated seq test

2016-09-16T10:41:58.703Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-16T10:41:59.488Z - info: Socket to device samsung-SM-G930F disconnected: transport close

2016-09-16T10:43:52.605Z - debug: Device presented: samsung-SM-G935F (6ef5f299-6ab7-47f5-8221-b5ab004361cf) - android 6.0.1

2016-09-16T10:43:53.216Z - debug: Device presented: samsung-SM-G930F (ab1a60fc-0173-40be-9662-dbe4b5065f52) - android 6.0.1

2016-09-16T11:03:08.430Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close

2016-09-16T11:03:09.867Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-16T11:03:11.230Z - info: Socket to device samsung-SM-G930F disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: 
Trying to deploy app to android: ENU7N16516000107

Deploying to android ENU7N16516000107

App was succesfully deployed to ENU7N16516000107

Trying to deploy app to android: ce061606e320561102

Deploying to android ce061606e320561102

App was succesfully deployed to ce061606e320561102

Trying to deploy app to android: ce0616068b9f212302

Deploying to android ce0616068b9f212302

App was succesfully deployed to ce0616068b9f212302

Trying to start application ThaliTest on ENU7N16516000107

Trying to start application ThaliTest on ce061606e320561102

Trying to start application ThaliTest on ce0616068b9f212302
TIMEOUT REACHED. KILLING the APPS
child process exited with code 0
child process exited with code 0
child process exited with code 0
Android task is completed.
Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali04
Console output:
```

Trying to deploy app to android: ENU7N16516000107

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Deploying to android ENU7N16516000107

App was succesfully deployed to ENU7N16516000107

Trying to deploy app to android: ce061606e320561102

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Deploying to android ce061606e320561102

App was succesfully deployed to ce061606e320561102

Trying to deploy app to android: ce0616068b9f212302

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Deploying to android ce0616068b9f212302

App was succesfully deployed to ce0616068b9f212302

Trying to start application ThaliTest on ENU7N16516000107

Trying to start application ThaliTest on ce061606e320561102

Trying to start application ThaliTest on ce0616068b9f212302
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:0 
child process exited with code 0
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:0 
child process exited with code 0
Error! Unexpected exit on device ce0616068b9f212302 app:com.test.thalitest code:0 
child process exited with code 0
Android task is completed.
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/85202518dd4c7ab__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_Huawei-Nexus 6P.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/85202518dd4c7ab__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/85202518dd4c7ab__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G930F.md)





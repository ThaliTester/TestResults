#### Test 85202518ae3d7e8 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-16T11:37:13.598Z - info: Require 0 ios devices

2016-09-16T11:37:13.616Z - info: Require 3 android devices

2016-09-16T11:37:13.673Z - info: listening on *:3000

2016-09-16T11:39:03.732Z - debug: Device presented: samsung-SM-G935F (8fd9450c-b3c3-4394-9674-6aae328a3221) - android 6.0.1

2016-09-16T11:39:04.152Z - debug: Device presented: samsung-SM-G930F (1717ace9-eb52-4624-a23e-38ed79a52586) - android 6.0.1

2016-09-16T11:39:06.733Z - debug: Device presented: Huawei-Nexus 6P (74eebcab-0446-4d20-b4d0-41280201456b) - android 6.0.1

2016-09-16T11:39:06.735Z - info: All 3 android devices are present

2016-09-16T11:39:06.741Z - info: Starting unit test run on 3 android devices

2016-09-16T11:39:07.922Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-09-16T11:39:09.594Z - info: Running on android test: 2. emits incomingConnectionState

2016-09-16T11:39:11.323Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-09-16T11:39:13.602Z - info: Running on android test: 4. native server connections all up

2016-09-16T11:39:15.325Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-09-16T11:39:16.659Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-09-16T11:39:18.393Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-09-16T11:39:19.823Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-09-16T11:39:20.118Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-09-16T11:39:21.892Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-09-16T11:39:22.265Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-09-16T11:39:22.539Z - info: Running on android test: 12. closeAll can close even when connections open

2016-09-16T11:39:22.870Z - info: Running on android test: 13. closeAll with promise

2016-09-16T11:39:23.178Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-09-16T11:39:23.504Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-09-16T11:39:23.812Z - info: Running on android test: 16. onPeerLost calls jxcore

2016-09-16T11:39:26.083Z - info: Running on android test: 17. onPeerDiscovered calls jxcore

2016-09-16T11:39:28.417Z - info: Running on android test: 18. test defaultDirectory

2016-09-16T11:39:28.673Z - info: Running on android test: 19. test defaultAdapter

2016-09-16T11:39:29.195Z - info: Running on android test: 20. enqueue and run in order

2016-09-16T11:39:29.637Z - info: Running on android test: 21. enqueueAtTop and run backwards

2016-09-16T11:39:29.838Z - info: Running on android test: 22. mix enqueue and enqueueAtTop

2016-09-16T11:39:30.166Z - info: Running on android test: 23. queues handled independently

2016-09-16T11:39:30.541Z - info: Running on android test: 24. basic

2016-09-16T11:39:30.719Z - info: Running on android test: 25. another

2016-09-16T11:39:30.909Z - info: Running on android test: 26. can pass data in setup

2016-09-16T11:39:31.101Z - info: Running on android test: 27. test thali manager spies

2016-09-16T11:39:31.942Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-16T11:39:31.960Z - info: Socket to device samsung-SM-G930F disconnected: transport close

2016-09-16T11:41:25.416Z - debug: Device presented: samsung-SM-G930F (5a426b7a-52e0-462e-b3d1-a2686364c2a0) - android 6.0.1

2016-09-16T11:41:25.599Z - debug: Device presented: samsung-SM-G935F (17275324-8370-4d7d-b21d-073a23be6ad9) - android 6.0.1

2016-09-16T11:41:30.369Z - debug: Too many emit retries to device: samsung-SM-G935F

2016-09-16T11:41:30.372Z - debug: Too many emit retries to device: samsung-SM-G930F

2016-09-16T12:00:41.073Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close

2016-09-16T12:00:42.537Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-16T12:00:44.044Z - info: Socket to device samsung-SM-G930F disconnected: transport close


 
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
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/85202518ae3d7e8__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_Huawei-Nexus 6P.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/85202518ae3d7e8__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/85202518ae3d7e8__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G930F.md)





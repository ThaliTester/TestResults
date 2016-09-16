#### Test 85202518d111121 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-09-16T14:41:21.450Z - info: Require 0 ios devices

2016-09-16T14:41:21.468Z - info: Require 3 android devices

2016-09-16T14:41:21.525Z - info: listening on *:3000

2016-09-16T14:43:10.542Z - debug: Device presented: samsung-SM-G935F (20acf350-cc66-4dc6-be9b-ad9679c85c1a) - android 6.0.1

2016-09-16T14:43:11.390Z - debug: Device presented: samsung-SM-G930F (27b69e3c-c9aa-4e9a-b783-4e41421b27ce) - android 6.0.1

2016-09-16T14:43:16.090Z - debug: Device presented: Huawei-Nexus 6P (8c26536f-9509-43b0-96a0-05e9f5e08408) - android 6.0.1

2016-09-16T14:43:16.092Z - info: All 3 android devices are present

2016-09-16T14:43:16.099Z - info: Starting unit test run on 3 android devices

2016-09-16T14:43:17.084Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-09-16T14:43:18.678Z - info: Running on android test: 2. emits incomingConnectionState

2016-09-16T14:43:20.522Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-09-16T14:43:22.608Z - info: Running on android test: 4. native server connections all up

2016-09-16T14:43:24.737Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-09-16T14:43:26.597Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-09-16T14:43:29.253Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-09-16T14:43:32.131Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-09-16T14:43:33.847Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-09-16T14:43:36.246Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-09-16T14:43:38.341Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-09-16T14:43:40.185Z - info: Running on android test: 12. closeAll can close even when connections open

2016-09-16T14:43:42.227Z - info: Running on android test: 13. closeAll with promise

2016-09-16T14:43:44.078Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-09-16T14:43:46.107Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-09-16T14:43:47.948Z - info: Running on android test: 16. onPeerLost calls jxcore

2016-09-16T14:43:52.211Z - info: Running on android test: 17. onPeerDiscovered calls jxcore

2016-09-16T14:43:55.863Z - info: Running on android test: 18. test defaultDirectory

2016-09-16T14:43:58.113Z - info: Running on android test: 19. test defaultAdapter

2016-09-16T14:43:59.637Z - info: Running on android test: 20. enqueue and run in order

2016-09-16T14:44:01.336Z - info: Running on android test: 21. enqueueAtTop and run backwards

2016-09-16T14:44:01.647Z - info: Running on android test: 22. mix enqueue and enqueueAtTop

2016-09-16T14:44:01.999Z - info: Running on android test: 23. queues handled independently

2016-09-16T14:44:02.413Z - info: Running on android test: 24. basic

2016-09-16T14:44:02.650Z - info: Running on android test: 25. another

2016-09-16T14:44:02.849Z - info: Running on android test: 26. can pass data in setup

2016-09-16T14:44:03.089Z - info: Running on android test: 27. #startListeningForAdvertisements should fail if start not called

2016-09-16T14:44:03.310Z - info: Running on android test: 28. #startUpdateAdvertisingAndListening should fail if start not called

2016-09-16T14:44:03.542Z - info: Running on android test: 29. should be able to call #stopListeningForAdvertisements many times

2016-09-16T14:44:03.988Z - info: Running on android test: 30. should be able to call #startListeningForAdvertisements many times

2016-09-16T14:44:05.435Z - info: Running on android test: 31. should be able to call #startUpdateAdvertisingAndListening many times

2016-09-16T14:44:06.749Z - info: Socket to device samsung-SM-G930F disconnected: transport close

2016-09-16T14:46:05.711Z - debug: Too many emit retries to device: samsung-SM-G930F

2016-09-16T15:04:48.973Z - info: Socket to device Huawei-Nexus 6P disconnected: transport close

2016-09-16T15:04:50.377Z - info: Socket to device samsung-SM-G935F disconnected: transport close


 
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
STOP log received from ce0616068b9f212302
Test has FAILED
TIMEOUT REACHED. KILLING the APPS
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
STOP log received from ce0616068b9f212302
Test has FAILED
Device test finished on ce0616068b9f212302 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ENU7N16516000107 app:com.test.thalitest code:0 
child process exited with code 0
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:0 
child process exited with code 0
Android task is completed.
```
[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/85202518d111121__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_Huawei-Nexus 6P.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/85202518d111121__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/85202518d111121__1031_DO_NOT_MERGE_Excluded__bad__test_files_artemjackson/thali04_samsung-SM-G930F.md)





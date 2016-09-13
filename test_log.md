#### Test 846186374ed975d Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":9}}
2016-09-13T09:17:04.167Z - info: Require 0 ios devices

2016-09-13T09:17:04.185Z - info: Require 9 android devices

2016-09-13T09:17:04.242Z - info: listening on *:3000

2016-09-13T09:18:13.442Z - debug: Device presented: samsung-SM-G935F (bb6e9241-929e-4cc7-aa24-f7a57b4f33a2) - android 6.0.1

2016-09-13T09:18:17.155Z - debug: Device presented: samsung-SM-T719 (034e5230-5f35-4564-bc90-c9a6a0264df6) - android 6.0.1

2016-09-13T09:18:24.736Z - debug: Device presented: samsung-SM-A300FU (809494fa-9460-4e38-8acb-c8179ae87f46) - android 5.0.2

2016-09-13T09:18:55.392Z - debug: Device presented: samsung-SM-A300FU (1c557aae-7f06-4f4e-bed7-5ca34d7ae78a) - android 5.0.2

2016-09-13T09:18:56.463Z - debug: Device presented: samsung-SM-A500FU (96b04d08-3b76-43f0-b629-8354854745a1) - android 5.0.2

2016-09-13T09:18:57.428Z - debug: Device presented: LGE-LG-D855 (07301500-e142-4f6f-bec6-55506a0b1415) - android 5.0

2016-09-13T09:19:05.907Z - debug: Device presented: motorola-Nexus 6 (3c8c753c-6050-4e9c-a9f3-8eb597945828) - android 6.0.1

2016-09-13T09:19:07.075Z - debug: Device presented: LGE-LG-D722 (d99723c4-bdd8-40fb-ae05-40307d894e15) - android 5.0.2

2016-09-13T09:19:07.190Z - debug: Device presented: samsung-SM-G900F (b9edcfba-e5ae-49c6-987a-fa7bf3a6dbeb) - android 6.0.1

2016-09-13T09:19:07.191Z - info: All 9 android devices are present

2016-09-13T09:19:07.194Z - info: Disqualifying device with unsupported hardware: LGE-LG-D855

2016-09-13T09:19:07.200Z - info: Disqualifying device with unsupported hardware: LGE-LG-D722

2016-09-13T09:19:07.211Z - info: Starting unit test run on 7 android devices

2016-09-13T09:19:08.122Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-09-13T09:19:08.370Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-09-13T09:19:08.391Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-09-13T09:19:09.620Z - info: Running on android test: 2. emits incomingConnectionState

2016-09-13T09:19:10.053Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-09-13T09:19:10.483Z - info: Running on android test: 4. native server connections all up

2016-09-13T09:19:10.932Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-09-13T09:19:11.288Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-09-13T09:19:11.669Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-09-13T09:19:12.294Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-09-13T09:19:12.674Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-09-13T09:19:14.139Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-09-13T09:19:16.344Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-09-13T09:19:18.019Z - info: Running on android test: 12. #_doImmediateSeqUpdate - server is not there

2016-09-13T09:19:18.510Z - info: Running on android test: 13. #_doImmediateSeqUpdate - server accepts & closes connection

2016-09-13T09:19:18.840Z - info: Running on android test: 14. #_doImmediateSeqUpdate - server always returns 500

2016-09-13T09:19:19.272Z - info: Running on android test: 15. #_doImmediateSeqUpdate - create new seq doc

2016-09-13T09:19:21.009Z - info: Socket to device samsung-SM-G935F disconnected: transport close

2016-09-13T09:19:22.283Z - info: Socket to device samsung-SM-A500FU disconnected: transport close

2016-09-13T09:19:22.324Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-09-13T09:19:22.477Z - info: Socket to device samsung-SM-A300FU disconnected: transport close

2016-09-13T09:21:18.591Z - debug: Too many emit retries to device: samsung-SM-A300FU

2016-09-13T09:21:18.594Z - debug: Too many emit retries to device: samsung-SM-A300FU

2016-09-13T09:21:18.597Z - debug: Too many emit retries to device: samsung-SM-A500FU

2016-09-13T09:21:18.598Z - debug: Too many emit retries to device: samsung-SM-G935F

2016-09-13T09:39:51.864Z - info: Socket to device samsung-SM-T719 disconnected: transport close

2016-09-13T09:40:32.600Z - info: Socket to device samsung-SM-G900F disconnected: transport close

2016-09-13T09:40:34.976Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/846186374ed975d_Returned_setImmediate_workaround_artemjackson/thali01_samsung-SM-G900F.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/846186374ed975d_Returned_setImmediate_workaround_artemjackson/thali01_motorola-Nexus 6.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  LGD855a6933058 Test has  SUCCEEDED
Device test finished on LGD855a6933058 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/846186374ed975d_Returned_setImmediate_workaround_artemjackson/thali02_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/846186374ed975d_Returned_setImmediate_workaround_artemjackson/thali02_LGE-LG-D855.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/846186374ed975d_Returned_setImmediate_workaround_artemjackson/thali03_samsung-SM-A500FU.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/846186374ed975d_Returned_setImmediate_workaround_artemjackson/thali03_samsung-SM-A300FU.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/846186374ed975d_Returned_setImmediate_workaround_artemjackson/thali04_samsung-SM-A300FU.md)

####Node name: thali05
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device e8c09bab app:com.test.thalitest code:0 
child process exited with code 0 on device e8c09bab 
Error! Unexpected exit on device ce061606e320561102 app:com.test.thalitest code:0 
child process exited with code 0 on device ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-T719](https://github.com/ThaliTester/TestResults/blob/846186374ed975d_Returned_setImmediate_workaround_artemjackson/thali05_samsung-SM-T719.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/846186374ed975d_Returned_setImmediate_workaround_artemjackson/thali05_samsung-SM-G935F.md)





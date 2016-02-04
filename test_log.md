#### Test 58259810381ca4f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-04T09:45:17.434Z - info: listening on *:3000

2016-02-04T09:45:18.764Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-02-04T09:45:20.845Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-02-04T09:45:21.220Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:2

2016-02-04T09:45:21.223Z - info: Required number of android devices presented (2)

2016-02-04T09:45:21.230Z - info: Starting unit test run for platform: android

2016-02-04T09:45:21.404Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:3

2016-02-04T09:45:21.406Z - info: Discarding surplus device: LGE-LG-D855

2016-02-04T09:45:22.012Z - debug: Socket disconnected: transport close 3 (LGE-LG-D855)

2016-02-04T09:45:22.067Z - info: Running on android test: multiplex can send data

2016-02-04T09:45:22.197Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:5

2016-02-04T09:45:22.199Z - info: Discarding surplus device: LGE-LG-D722

2016-02-04T09:45:22.306Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:6

2016-02-04T09:45:22.307Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-04T09:45:22.395Z - info: Running on android test: enqueue and run in order

2016-02-04T09:45:22.538Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:7

2016-02-04T09:45:22.539Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-04T09:45:22.712Z - info: Running on android test: basic

2016-02-04T09:45:22.772Z - info: Running on android test: another

2016-02-04T09:45:22.838Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-04T09:45:23.073Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-04T09:45:23.212Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-04T09:45:23.230Z - debug: Socket disconnected: transport close 7 (motorola-Nexus 6)

2016-02-04T09:45:23.273Z - info: Running on android test: failed to get mobile documents path

2016-02-04T09:45:23.321Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-04T09:45:23.378Z - info: Running on android test: #init should register the networkChanged event

2016-02-04T09:45:23.388Z - debug: Socket disconnected: transport close 5 (LGE-LG-D722)

2016-02-04T09:45:23.445Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-04T09:45:23.508Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-04T09:45:23.528Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F)

2016-02-04T09:45:23.554Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-04T09:45:23.594Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-04T09:45:23.631Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-04T09:45:23.671Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-04T09:45:23.727Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T09:45:23.809Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T09:45:23.887Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T09:45:23.960Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T09:45:24.030Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-04T09:45:24.121Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-04T09:45:24.173Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-04T09:45:24.209Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-04T09:45:24.253Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T09:45:25.008Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-02-04T09:45:25.009Z - info: Required number of ios devices presented (2)

2016-02-04T09:45:25.011Z - info: Starting unit test run for platform: ios

2016-02-04T09:45:25.209Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:8

2016-02-04T09:45:25.211Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-04T09:45:25.958Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F)

2016-02-04T09:45:27.139Z - info: Running on ios test: multiplex can send data

2016-02-04T09:45:27.468Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:9

2016-02-04T09:45:27.469Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-04T09:45:28.370Z - debug: Socket disconnected: transport close 9 (samsung-SM-N910C)

2016-02-04T09:45:37.026Z - info: Running on ios test: enqueue and run in order

2016-02-04T09:45:42.426Z - info: Running on ios test: basic

2016-02-04T09:45:50.226Z - info: Running on ios test: another

2016-02-04T09:45:56.672Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-04T09:46:02.323Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-04T09:46:14.369Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-04T09:46:25.425Z - info: Running on ios test: failed to get mobile documents path

2016-02-04T09:46:30.536Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-04T09:46:34.026Z - info: Running on ios test: #init should register the networkChanged event

2016-02-04T09:46:44.532Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-04T09:46:49.275Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-H815)

2016-02-04T09:46:50.185Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-04T09:46:55.106Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-04T09:47:00.119Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-04T09:47:17.207Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-04T09:47:18.019Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-04T09:47:18.634Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T09:47:28.327Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T09:47:36.696Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T09:47:47.101Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T09:47:50.527Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-04T09:47:53.632Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-04T09:48:06.142Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-04T09:48:16.145Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-04T09:48:32.237Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T09:48:43.628Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-04T09:49:03.628Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-04T09:49:17.751Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-04T09:49:21.331Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-04T09:49:28.796Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T09:49:38.186Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T09:49:48.049Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-04T09:50:55.623Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-04T09:51:15.702Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-04T09:51:20.747Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-04T09:51:23.798Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)

2016-02-04T09:58:30.613Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-02-04T10:01:50.017Z - debug: Socket disconnected: transport close 2 (LGE-Nexus 5)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:0 
child process exited with code 0 on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58259810381ca4f_Update_pouchdb_and_related_dependencies__vjrantal/thali09_LGE-Nexus 5.md)





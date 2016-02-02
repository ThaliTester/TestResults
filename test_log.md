#### Test 5797209499148df Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-02T12:38:57.616Z - info: listening on *:3000

2016-02-02T12:38:58.298Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:0

2016-02-02T12:39:00.089Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:1

2016-02-02T12:39:00.091Z - info: Required number of android devices presented (2)

2016-02-02T12:39:00.095Z - info: Starting unit test run for platform: android

2016-02-02T12:39:00.372Z - info: Running on android test: multiplex can send data

2016-02-02T12:39:00.434Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-02-02T12:39:00.535Z - info: Running on android test: enqueue and run in order

2016-02-02T12:39:00.839Z - info: Running on android test: basic

2016-02-02T12:39:00.900Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-02-02T12:39:00.901Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-02T12:39:00.946Z - info: Running on android test: another

2016-02-02T12:39:01.034Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-02T12:39:01.259Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-02T12:39:01.319Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:4

2016-02-02T12:39:01.321Z - info: Discarding surplus device: LGE-LG-D722

2016-02-02T12:39:01.448Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-02T12:39:01.510Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:5

2016-02-02T12:39:01.511Z - info: Discarding surplus device: LGE-LG-D855

2016-02-02T12:39:01.546Z - info: Running on android test: failed to get mobile documents path

2016-02-02T12:39:01.594Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-02T12:39:01.664Z - info: Running on android test: #init should register the networkChanged event

2016-02-02T12:39:01.716Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-02T12:39:01.775Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:6

2016-02-02T12:39:01.780Z - info: Required number of ios devices presented (2)

2016-02-02T12:39:01.781Z - info: Starting unit test run for platform: ios

2016-02-02T12:39:01.793Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-02T12:39:01.900Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-02T12:39:01.950Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-02T12:39:01.993Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-02T12:39:02.038Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-02T12:39:02.093Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-02T12:39:02.113Z - debug: Socket disconnected: transport close 3 (samsung-SM-G900F)

2016-02-02T12:39:02.200Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-02T12:39:02.249Z - debug: Socket disconnected: transport close 5 (LGE-LG-D855)

2016-02-02T12:39:02.291Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-02T12:39:02.354Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-02T12:39:02.375Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:7

2016-02-02T12:39:02.376Z - info: Discarding surplus device: LGE-LG-H815

2016-02-02T12:39:02.427Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-02T12:39:02.475Z - debug: Socket disconnected: transport close 4 (LGE-LG-D722)

2016-02-02T12:39:02.506Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-02T12:39:02.553Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-02T12:39:02.601Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-02T12:39:02.650Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-02T12:39:03.213Z - debug: Socket disconnected: transport close 7 (LGE-LG-H815)

2016-02-02T12:39:04.088Z - info: Running on ios test: multiplex can send data

2016-02-02T12:39:04.177Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-02T12:39:04.178Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-02T12:39:04.874Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-02T12:39:06.374Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-02T12:39:06.375Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-02T12:39:07.172Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-02T12:39:08.046Z - info: Running on ios test: enqueue and run in order

2016-02-02T12:39:08.428Z - info: Running on ios test: basic

2016-02-02T12:39:08.617Z - info: Running on ios test: another

2016-02-02T12:39:08.791Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-02T12:39:12.185Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-02T12:39:25.332Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-02T12:39:27.841Z - info: Running on ios test: failed to get mobile documents path

2016-02-02T12:39:27.917Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-02T12:39:28.001Z - info: Running on ios test: #init should register the networkChanged event

2016-02-02T12:39:28.074Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-02T12:39:28.145Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-02T12:39:28.214Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-02T12:39:28.278Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-02T12:39:28.343Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-02T12:39:28.417Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-02T12:39:28.488Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-02T12:39:28.669Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-02T12:39:28.739Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-02T12:39:28.827Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-02T12:39:28.912Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-02T12:39:28.988Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-02T12:39:29.061Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-02T12:39:29.127Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-02T12:39:29.201Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-02T12:39:29.555Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-02T12:39:29.714Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-02T12:39:30.161Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-02T12:39:30.604Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-02T12:39:35.996Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-02T12:39:41.203Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-02T12:39:45.984Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-02T12:40:27.689Z - debug: Socket disconnected: ping timeout 1 (motorola-Nexus 6)

2016-02-02T12:40:45.709Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-02T12:41:03.564Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-02T12:41:04.047Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-02T12:41:04.332Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-02T12:41:24.754Z - info: Running on ios test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-02T12:41:27.065Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-02-02T12:52:01.380Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-02-02T12:55:45.409Z - debug: Socket disconnected: transport close 0 (LGE-Nexus 5)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali04_samsung-SM-N910C.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5797209499148df_Address_test_setup_issue_vjrantal/thali09_LGE-Nexus 5.md)





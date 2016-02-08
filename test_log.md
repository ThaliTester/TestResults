#### Test 58380500055030c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-08T22:36:02.351Z - info: listening on *:3000

2016-02-08T22:36:03.254Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:0

2016-02-08T22:36:03.639Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:1

2016-02-08T22:36:03.642Z - info: Required number of android devices presented (2)

2016-02-08T22:36:03.645Z - info: Starting unit test run for platform: android

2016-02-08T22:36:03.854Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-02-08T22:36:04.013Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:3

2016-02-08T22:36:04.014Z - info: Discarding surplus device: LGE-LG-D855

2016-02-08T22:36:04.174Z - info: Running on android test: multiplex can send data

2016-02-08T22:36:04.504Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-02-08T22:36:04.507Z - info: Discarding surplus device: LGE-LG-H815

2016-02-08T22:36:04.629Z - debug: Socket disconnected: transport close 3 (LGE-LG-D855)

2016-02-08T22:36:04.741Z - info: Running on android test: enqueue and run in order

2016-02-08T22:36:05.035Z - info: Running on android test: basic

2016-02-08T22:36:05.145Z - info: Running on android test: another

2016-02-08T22:36:05.227Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-08T22:36:05.339Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:5

2016-02-08T22:36:05.341Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-08T22:36:05.415Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-08T22:36:05.517Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-02-08T22:36:05.554Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-08T22:36:05.609Z - info: Running on android test: failed to get mobile documents path

2016-02-08T22:36:05.664Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-08T22:36:05.721Z - info: Running on android test: #init should register the networkChanged event

2016-02-08T22:36:05.766Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:6

2016-02-08T22:36:05.768Z - info: Required number of ios devices presented (2)

2016-02-08T22:36:05.770Z - info: Starting unit test run for platform: ios

2016-02-08T22:36:05.795Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-08T22:36:05.824Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:7

2016-02-08T22:36:05.825Z - info: Discarding surplus device: LGE-LG-D722

2016-02-08T22:36:05.854Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-08T22:36:05.920Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-08T22:36:05.965Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-08T22:36:06.019Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-08T22:36:06.061Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-08T22:36:06.113Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T22:36:06.180Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T22:36:06.257Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T22:36:06.334Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T22:36:06.401Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-08T22:36:06.487Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-08T22:36:06.508Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F)

2016-02-08T22:36:06.527Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-08T22:36:06.592Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-08T22:36:06.687Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T22:36:06.744Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:8

2016-02-08T22:36:06.745Z - info: Discarding surplus device: HTC-HTC One M8s

2016-02-08T22:36:06.937Z - debug: Socket disconnected: transport close 7 (LGE-LG-D722)

2016-02-08T22:36:07.215Z - info: Running on ios test: multiplex can send data

2016-02-08T22:36:07.919Z - debug: Socket disconnected: transport close 8 (HTC-HTC One M8s)

2016-02-08T22:36:09.942Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:9

2016-02-08T22:36:09.943Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-08T22:36:10.485Z - debug: Socket disconnected: transport close 9 (samsung-SM-N910C)

2016-02-08T22:36:11.817Z - info: Running on ios test: enqueue and run in order

2016-02-08T22:36:11.945Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:10

2016-02-08T22:36:11.950Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-08T22:36:12.633Z - debug: Socket disconnected: transport close 10 (samsung-SM-G900F)

2016-02-08T22:36:13.654Z - info: Running on ios test: basic

2016-02-08T22:36:13.857Z - info: Running on ios test: another

2016-02-08T22:36:14.053Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-08T22:36:24.691Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-08T22:36:24.995Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-08T22:36:25.120Z - info: Running on ios test: failed to get mobile documents path

2016-02-08T22:36:25.193Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-08T22:36:25.251Z - info: Running on ios test: #init should register the networkChanged event

2016-02-08T22:36:25.308Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-08T22:36:25.369Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-08T22:36:25.448Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-08T22:36:25.516Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-08T22:36:25.579Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-08T22:36:25.654Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-08T22:36:25.758Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T22:36:25.905Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T22:36:26.001Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T22:36:26.075Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T22:36:26.140Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-08T22:36:26.208Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-08T22:36:26.299Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-08T22:36:26.359Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-08T22:36:26.422Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T22:36:26.866Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-08T22:36:27.341Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-08T22:36:27.453Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-08T22:36:27.811Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-08T22:36:32.650Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T22:36:38.208Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T22:36:47.322Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-08T22:36:56.294Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-08T22:37:04.592Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-08T22:37:04.961Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-08T22:37:05.222Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-08T22:37:26.081Z - info: Running on ios test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T22:37:28.287Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-02-08T22:37:31.715Z - debug: Socket disconnected: ping timeout 1 (motorola-Nexus 6)

2016-02-08T22:42:32.943Z - debug: Socket disconnected: ping timeout 6 (Apple-Iphone6-1)

2016-02-08T22:52:35.028Z - debug: Socket disconnected: transport close 0 (LGE-Nexus 5)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500055030c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_LGE-Nexus 5.md)





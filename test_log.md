#### Test 58380500fccea7e Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-06T00:16:46.752Z - info: listening on *:3000

2016-02-06T00:16:47.267Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-02-06T00:16:48.352Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:1

2016-02-06T00:16:48.355Z - info: Required number of android devices presented (2)

2016-02-06T00:16:48.358Z - info: Starting unit test run for platform: android

2016-02-06T00:16:48.443Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:2

2016-02-06T00:16:48.445Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-06T00:16:48.973Z - info: Running on android test: multiplex can send data

2016-02-06T00:16:49.072Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:3

2016-02-06T00:16:49.073Z - info: Discarding surplus device: HTC-HTC One M8s

2016-02-06T00:16:49.182Z - info: Running on android test: enqueue and run in order

2016-02-06T00:16:49.355Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:4

2016-02-06T00:16:49.357Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-06T00:16:49.502Z - info: Running on android test: basic

2016-02-06T00:16:49.577Z - info: Running on android test: another

2016-02-06T00:16:49.637Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-06T00:16:49.749Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:5

2016-02-06T00:16:49.750Z - info: Discarding surplus device: LGE-LG-D722

2016-02-06T00:16:49.797Z - debug: Socket disconnected: transport close 4 (LGE-Nexus 5)

2016-02-06T00:16:49.863Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-06T00:16:49.980Z - debug: Socket disconnected: transport close 2 (samsung-SM-G900F)

2016-02-06T00:16:50.073Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-06T00:16:50.138Z - info: Running on android test: failed to get mobile documents path

2016-02-06T00:16:50.181Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-06T00:16:50.197Z - debug: Socket disconnected: transport close 3 (HTC-HTC One M8s)

2016-02-06T00:16:50.237Z - info: Running on android test: #init should register the networkChanged event

2016-02-06T00:16:50.290Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-06T00:16:50.338Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-06T00:16:50.392Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-06T00:16:50.437Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-06T00:16:50.494Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-06T00:16:50.551Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-06T00:16:50.615Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-06T00:16:50.676Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-06T00:16:50.862Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-02-06T00:16:50.863Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-06T00:16:50.898Z - debug: Socket disconnected: transport close 5 (LGE-LG-D722)

2016-02-06T00:16:50.932Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-06T00:16:51.070Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-06T00:16:51.165Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-06T00:16:51.243Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:7

2016-02-06T00:16:51.248Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-06T00:16:51.304Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-06T00:16:51.425Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-06T00:16:51.479Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-06T00:16:51.593Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-02-06T00:16:51.780Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:8

2016-02-06T00:16:51.781Z - info: Required number of ios devices presented (2)

2016-02-06T00:16:51.783Z - info: Starting unit test run for platform: ios

2016-02-06T00:16:52.797Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:9

2016-02-06T00:16:52.798Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-06T00:16:53.357Z - debug: Socket disconnected: transport close 9 (samsung-SM-N910C)

2016-02-06T00:16:54.149Z - info: Running on ios test: multiplex can send data

2016-02-06T00:16:56.311Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:11

2016-02-06T00:16:56.312Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-06T00:16:57.066Z - debug: Socket disconnected: transport close 11 (samsung-SM-G900F)

2016-02-06T00:16:57.924Z - info: Running on ios test: enqueue and run in order

2016-02-06T00:17:03.370Z - info: Running on ios test: basic

2016-02-06T00:17:07.671Z - info: Running on ios test: another

2016-02-06T00:17:07.930Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-06T00:17:08.363Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-06T00:17:08.629Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-06T00:17:08.943Z - info: Running on ios test: failed to get mobile documents path

2016-02-06T00:17:09.312Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-06T00:17:09.503Z - info: Running on ios test: #init should register the networkChanged event

2016-02-06T00:17:09.807Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-06T00:17:09.986Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-06T00:17:10.002Z - debug: Device presented: motorola-XT1072 (android) unittest socket:12

2016-02-06T00:17:10.003Z - info: Discarding surplus device: motorola-XT1072

2016-02-06T00:17:10.282Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-06T00:17:10.626Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-06T00:17:10.760Z - debug: Socket disconnected: transport close 12 (motorola-XT1072)

2016-02-06T00:17:14.901Z - debug: Socket disconnected: transport close 10 (NOT YET SET)

2016-02-06T00:17:16.672Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-06T00:17:17.770Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:13

2016-02-06T00:17:17.771Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-06T00:17:19.975Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-06T00:17:20.038Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-06T00:17:20.118Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-06T00:17:20.206Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-06T00:17:20.270Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-06T00:17:20.339Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-06T00:17:20.402Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-06T00:17:20.476Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-06T00:17:20.556Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-06T00:17:20.642Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-06T00:17:21.089Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-06T00:17:21.160Z - debug: Socket disconnected: transport close 13 (Apple-Iphone5-1)

2016-02-06T00:17:22.005Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-06T00:17:28.121Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-06T00:17:30.624Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-06T00:17:35.806Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-06T00:17:40.546Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-06T00:17:45.242Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-06T00:17:50.014Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-06T00:17:56.887Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-06T00:17:57.649Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-06T00:17:57.849Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-06T00:18:16.505Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-H815)

2016-02-06T00:18:27.902Z - debug: Socket disconnected: transport close 8 (Apple-IpadAir2-1)

2016-02-06T00:18:38.083Z - debug: Socket disconnected: transport close 7 (Apple-Iphone6-1)

2016-02-06T00:21:58.531Z - debug: Socket disconnected: ping timeout 1 (LGE-LG-D855)


 
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
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone5-1.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58380500fccea7e_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_LGE-Nexus 5.md)





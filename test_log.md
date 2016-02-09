#### Test 583805004f2b042 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-09T16:39:08.613Z - info: listening on *:3000

2016-02-09T16:39:10.187Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-02-09T16:39:10.425Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:1

2016-02-09T16:39:10.429Z - info: Required number of android devices presented (2)

2016-02-09T16:39:10.434Z - info: Starting unit test run for platform: android

2016-02-09T16:39:10.665Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-02-09T16:39:10.756Z - info: Running on android test: multiplex can send data

2016-02-09T16:39:10.777Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-02-09T16:39:10.780Z - info: Required number of ios devices presented (2)

2016-02-09T16:39:10.781Z - info: Starting unit test run for platform: ios

2016-02-09T16:39:10.943Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:4

2016-02-09T16:39:10.946Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T16:39:10.990Z - info: Running on android test: enqueue and run in order

2016-02-09T16:39:10.995Z - info: Running on ios test: multiplex can send data

2016-02-09T16:39:11.138Z - info: Running on ios test: enqueue and run in order

2016-02-09T16:39:11.373Z - info: Running on android test: basic

2016-02-09T16:39:11.461Z - info: Running on ios test: basic

2016-02-09T16:39:11.478Z - info: Running on android test: another

2016-02-09T16:39:11.544Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-09T16:39:11.625Z - info: Running on ios test: another

2016-02-09T16:39:11.770Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-09T16:39:11.888Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-09T16:39:11.940Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:5

2016-02-09T16:39:11.942Z - info: Discarding surplus device: LGE-LG-D855

2016-02-09T16:39:12.108Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-09T16:39:12.119Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-02-09T16:39:12.122Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-09T16:39:12.166Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T16:39:12.185Z - debug: Socket disconnected: transport close 4 (samsung-SM-G900F)

2016-02-09T16:39:12.323Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T16:39:12.340Z - info: Running on android test: failed to get mobile documents path

2016-02-09T16:39:12.427Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-09T16:39:12.507Z - info: Running on ios test: failed to get mobile documents path

2016-02-09T16:39:12.532Z - info: Running on android test: #init should register the networkChanged event

2016-02-09T16:39:12.558Z - debug: Socket disconnected: transport close 5 (LGE-LG-D855)

2016-02-09T16:39:12.585Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:7

2016-02-09T16:39:12.586Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-09T16:39:12.637Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-09T16:39:12.644Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-09T16:39:12.655Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-02-09T16:39:12.744Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-09T16:39:12.793Z - info: Running on ios test: #init should register the networkChanged event

2016-02-09T16:39:12.831Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-09T16:39:12.932Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-09T16:39:12.939Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-09T16:39:13.030Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-09T16:39:13.047Z - debug: Socket disconnected: transport close 7 (LGE-Nexus 5)

2016-02-09T16:39:13.065Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-09T16:39:13.121Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-09T16:39:13.184Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-09T16:39:13.235Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T16:39:13.311Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-09T16:39:13.336Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T16:39:13.522Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-09T16:39:13.540Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T16:39:13.645Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T16:39:13.675Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-09T16:39:13.754Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T16:39:13.812Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T16:39:13.841Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-09T16:39:13.928Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-09T16:39:13.957Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T16:39:14.019Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-09T16:39:14.103Z - info: Running on android test: #start should fail if called twice in a row

2016-02-09T16:39:14.108Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T16:39:14.217Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-09T16:39:14.252Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T16:39:14.339Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T16:39:14.389Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T16:39:14.437Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-09T16:39:14.516Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-09T16:39:14.534Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T16:39:14.653Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-09T16:39:14.655Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-09T16:39:14.660Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-09T16:39:14.690Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T16:39:14.771Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T16:39:14.792Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-09T16:39:14.929Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-09T16:39:15.094Z - info: Running on ios test: #startListeningForAdvertisements should fail if start not called

2016-02-09T16:39:15.160Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-09T16:39:15.241Z - info: Running on ios test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T16:39:15.361Z - info: Running on ios test: should be able to call #startListeningForAdvertisements many times

2016-02-09T16:39:15.499Z - info: Running on ios test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T16:39:15.794Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T16:39:15.908Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T16:39:16.323Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-09T16:39:17.308Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-09T16:39:21.727Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-09T16:39:21.730Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T16:39:22.596Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-09T16:39:28.240Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-09T16:39:32.086Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-09T16:39:37.970Z - debug: Socket disconnected: transport close 10 (NOT YET SET)

2016-02-09T16:39:39.290Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-09T16:39:44.096Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:11

2016-02-09T16:39:44.098Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-09T16:39:44.958Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-09T16:39:49.206Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-09T16:39:49.215Z - debug: Socket disconnected: transport close 11 (Apple-Iphone5-1)

2016-02-09T16:40:39.855Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-H815)

2016-02-09T16:52:33.716Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-02-09T16:52:33.767Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-02-09T16:55:58.019Z - debug: Socket disconnected: transport close 1 (LGE-LG-D722)


 
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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/583805004f2b042_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_LGE-Nexus 5.md)





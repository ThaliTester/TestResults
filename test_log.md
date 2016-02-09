#### Test 583805004251330 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-09T16:09:19.620Z - info: listening on *:3000

2016-02-09T16:09:21.613Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:0

2016-02-09T16:09:21.649Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-02-09T16:09:21.666Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-02-09T16:09:21.668Z - info: Required number of android devices presented (2)

2016-02-09T16:09:21.672Z - info: Starting unit test run for platform: android

2016-02-09T16:09:21.741Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-02-09T16:09:21.742Z - info: Required number of ios devices presented (2)

2016-02-09T16:09:21.743Z - info: Starting unit test run for platform: ios

2016-02-09T16:09:21.955Z - info: Running on android test: multiplex can send data

2016-02-09T16:09:21.970Z - info: Running on ios test: multiplex can send data

2016-02-09T16:09:22.068Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:4

2016-02-09T16:09:22.070Z - info: Discarding surplus device: LGE-LG-D722

2016-02-09T16:09:22.119Z - info: Running on android test: enqueue and run in order

2016-02-09T16:09:22.446Z - info: Running on android test: basic

2016-02-09T16:09:22.591Z - info: Running on android test: another

2016-02-09T16:09:22.723Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-09T16:09:22.820Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:5

2016-02-09T16:09:22.822Z - info: Discarding surplus device: LGE-LG-D855

2016-02-09T16:09:22.854Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:6

2016-02-09T16:09:22.855Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-09T16:09:23.056Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-09T16:09:23.237Z - debug: Socket disconnected: transport close 4 (LGE-LG-D722)

2016-02-09T16:09:23.255Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T16:09:23.329Z - debug: Socket disconnected: transport close 6 (LGE-Nexus 5)

2016-02-09T16:09:23.345Z - info: Running on android test: failed to get mobile documents path

2016-02-09T16:09:23.426Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-09T16:09:23.484Z - debug: Socket disconnected: transport close 5 (LGE-LG-D855)

2016-02-09T16:09:23.541Z - info: Running on android test: #init should register the networkChanged event

2016-02-09T16:09:23.660Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-09T16:09:23.780Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-09T16:09:23.852Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-09T16:09:23.951Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-09T16:09:24.033Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-09T16:09:24.154Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-09T16:09:24.194Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:8

2016-02-09T16:09:24.197Z - info: Discarding surplus device: HTC-HTC One M8s

2016-02-09T16:09:24.247Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T16:09:24.336Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T16:09:24.430Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T16:09:24.450Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-09T16:09:24.451Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T16:09:24.525Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T16:09:24.606Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T16:09:24.694Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-09T16:09:24.782Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-09T16:09:24.870Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-09T16:09:24.952Z - info: Running on android test: #start should fail if called twice in a row

2016-02-09T16:09:25.055Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-09T16:09:25.131Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T16:09:25.216Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-09T16:09:25.269Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:10

2016-02-09T16:09:25.270Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-09T16:09:25.326Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T16:09:25.451Z - debug: Socket disconnected: transport close 8 (HTC-HTC One M8s)

2016-02-09T16:09:25.504Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T16:09:25.546Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-09T16:09:25.574Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T16:09:25.725Z - debug: Socket disconnected: transport close 10 (samsung-SM-N910C)

2016-02-09T16:09:28.102Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:7

2016-02-09T16:09:28.103Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-09T16:09:28.485Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:11

2016-02-09T16:09:28.486Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T16:09:29.237Z - debug: Socket disconnected: transport close 11 (samsung-SM-G900F)

2016-02-09T16:09:30.954Z - info: Running on ios test: enqueue and run in order

2016-02-09T16:09:31.432Z - info: Running on ios test: basic

2016-02-09T16:09:31.565Z - debug: Socket disconnected: transport close 7 (Apple-Iphone5-1)

2016-02-09T16:09:31.906Z - info: Running on ios test: another

2016-02-09T16:09:32.284Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-09T16:09:32.817Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-09T16:09:33.163Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T16:09:35.899Z - info: Running on ios test: failed to get mobile documents path

2016-02-09T16:09:44.819Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-09T16:09:45.034Z - info: Running on ios test: #init should register the networkChanged event

2016-02-09T16:09:45.382Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-09T16:09:45.705Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-09T16:09:46.041Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-09T16:09:46.726Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-09T16:09:47.103Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-09T16:09:47.251Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-09T16:09:47.379Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T16:09:47.506Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T16:09:47.644Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T16:09:47.772Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T16:09:47.897Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T16:09:48.032Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-09T16:09:48.272Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-09T16:09:48.407Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-09T16:09:48.530Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-09T16:09:48.657Z - info: Running on ios test: #startListeningForAdvertisements should fail if start not called

2016-02-09T16:09:48.860Z - info: Running on ios test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T16:09:48.985Z - info: Running on ios test: should be able to call #startListeningForAdvertisements many times

2016-02-09T16:09:49.138Z - info: Running on ios test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T16:09:49.339Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T16:09:49.459Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T16:09:49.877Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-09T16:09:50.413Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-09T16:09:50.856Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-09T16:09:52.088Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-09T16:09:57.308Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-09T16:10:02.016Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-09T16:10:10.377Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-09T16:10:50.630Z - debug: Socket disconnected: ping timeout 0 (motorola-Nexus 6)

2016-02-09T16:10:50.636Z - debug: Socket disconnected: ping timeout 3 (LGE-LG-H815)

2016-02-09T16:11:45.743Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-09T16:11:53.699Z - info: Running on ios test: #generatePreambleAndBeacons null ECDH for local device

2016-02-09T16:11:54.234Z - info: Running on ios test: #generatePreambleAndBeacons expiration out of range lower

2016-02-09T16:11:54.762Z - info: Running on ios test: #generatePreambleAndBeacons expiration out of range upper

2016-02-09T16:11:55.116Z - info: Running on ios test: #generatePreambleAndBeacons empty keys to notify

2016-02-09T16:11:55.299Z - info: Running on ios test: #generatePreambleAndBeacons multiple keys to notify

2016-02-09T16:11:55.711Z - info: Running on ios test: #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

2016-02-09T16:11:56.041Z - info: Running on ios test: #parseBeacons invalid expiration in beaconStreamWithPreAmble

2016-02-09T16:11:56.198Z - info: Running on ios test: #parseBeacons expiration out of range lower

2016-02-09T16:11:56.343Z - info: Running on ios test: #parseBeacons no beacons returns null

2016-02-09T16:11:56.703Z - info: Running on ios test: #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

2016-02-09T16:11:56.856Z - info: Running on ios test: #parseBeacons addressBookCallback fails decrypt

2016-02-09T16:11:57.298Z - info: Running on ios test: #parseBeacons addressBookCallback returns no matches

2016-02-09T16:11:57.895Z - info: Running on ios test: #parseBeacons addressBookCallback returns public key

2016-02-09T16:11:58.303Z - info: Running on ios test: #parseBeacons with beacons both for and not for the user

2016-02-09T16:11:58.663Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-09T16:12:01.935Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-02-09T16:22:55.889Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-02-09T16:12:07.894Z - error: test server: Device undefined


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/583805004251330_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_LGE-Nexus 5.md)





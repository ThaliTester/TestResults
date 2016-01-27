#### Test 568182540458528 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-27T01:12:54.910Z - info: listening on *:3000

2016-01-27T01:12:55.791Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-01-27T01:12:55.812Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:1

2016-01-27T01:12:55.886Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:2

2016-01-27T01:12:55.888Z - info: Required number of android devices presented (2)

2016-01-27T01:12:55.892Z - info: Starting unit test run for platform: android

2016-01-27T01:12:56.162Z - info: Running on android test: multiplex can send data

2016-01-27T01:12:56.360Z - info: Running on android test: enqueue and run in order

2016-01-27T01:12:56.715Z - info: Running on android test: basic

2016-01-27T01:12:56.807Z - info: Running on android test: another

2016-01-27T01:12:56.855Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-27T01:12:56.870Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:3

2016-01-27T01:12:56.871Z - info: Discarding surplus device: LGE-LG-D722

2016-01-27T01:12:56.938Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-01-27T01:12:56.940Z - info: Required number of ios devices presented (2)

2016-01-27T01:12:56.941Z - info: Starting unit test run for platform: ios

2016-01-27T01:12:57.094Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-01-27T01:12:57.096Z - info: Discarding surplus device: LGE-LG-H815

2016-01-27T01:12:57.118Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-27T01:12:57.302Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-27T01:12:57.354Z - info: Running on android test: failed to get mobile documents path

2016-01-27T01:12:57.395Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-27T01:12:57.441Z - info: Running on android test: #init should register the networkChanged event

2016-01-27T01:12:57.491Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-27T01:12:57.559Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-27T01:12:57.623Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-27T01:12:57.681Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-27T01:12:57.763Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-27T01:12:57.812Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-01-27T01:12:57.813Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-27T01:12:57.817Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-27T01:12:57.881Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-27T01:12:58.030Z - debug: Socket disconnected: transport close 3 (LGE-LG-D722)

2016-01-27T01:12:58.059Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-01-27T01:12:58.082Z - info: Running on ios test: multiplex can send data

2016-01-27T01:12:58.179Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-27T01:12:58.363Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:8

2016-01-27T01:12:58.364Z - info: Discarding surplus device: HTC-HTC One M8s

2016-01-27T01:12:58.373Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-01-27T01:12:58.374Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-27T01:12:58.586Z - debug: Socket disconnected: transport close 6 (samsung-SM-N910C)

2016-01-27T01:12:59.142Z - debug: Socket disconnected: transport close 8 (HTC-HTC One M8s)

2016-01-27T01:12:59.266Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:9

2016-01-27T01:12:59.267Z - info: Discarding surplus device: LGE-LG-D855

2016-01-27T01:12:59.648Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-01-27T01:12:59.833Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:10

2016-01-27T01:12:59.834Z - info: Discarding surplus device: motorola-Nexus 6

2016-01-27T01:12:59.922Z - debug: Socket disconnected: transport close 9 (LGE-LG-D855)

2016-01-27T01:13:00.459Z - debug: Socket disconnected: transport close 10 (motorola-Nexus 6)

2016-01-27T01:13:00.782Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-27T01:13:00.869Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-27T01:13:00.951Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-27T01:13:01.017Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-27T01:13:01.071Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-27T01:13:01.132Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-27T01:13:01.193Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-27T01:13:02.774Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-27T01:13:03.350Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-27T01:13:03.742Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-27T01:13:04.165Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-27T01:13:04.228Z - info: Running on ios test: enqueue and run in order

2016-01-27T01:13:04.501Z - info: Running on android test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-27T01:13:04.613Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-27T01:13:04.687Z - info: Test run on android complete

2016-01-27T01:13:04.691Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-27T01:13:04.693Z - info: PLATFORM: android

2016-01-27T01:13:04.696Z - info: RESULT: PASS

2016-01-27T01:13:04.698Z - info: 31 of 31 tests completed

2016-01-27T01:13:04.700Z - info: 31/31 passed (0 failures)

2016-01-27T01:13:04.701Z - info: --- Test Details ---



2016-01-27T01:13:04.703Z - info: multiplex can send data - pass

2016-01-27T01:13:04.705Z - info: enqueue and run in order - pass

2016-01-27T01:13:04.707Z - info: basic - pass

2016-01-27T01:13:04.708Z - info: another - pass

2016-01-27T01:13:04.713Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-27T01:13:04.715Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-27T01:13:04.716Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-27T01:13:04.718Z - info: failed to get mobile documents path - pass

2016-01-27T01:13:04.720Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-27T01:13:04.721Z - info: #init should register the networkChanged event - pass

2016-01-27T01:13:04.723Z - info: #startBroadcasting should throw on null device name - pass

2016-01-27T01:13:04.725Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-27T01:13:04.726Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-27T01:13:04.728Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-27T01:13:04.729Z - info: #startBroadcasting should throw on negative port - pass

2016-01-27T01:13:04.731Z - info: #startBroadcasting should throw on too large port - pass

2016-01-27T01:13:04.733Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-27T01:13:04.734Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-27T01:13:04.736Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-27T01:13:04.738Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-27T01:13:04.739Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-27T01:13:04.741Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-27T01:13:04.742Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-27T01:13:04.743Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-27T01:13:04.745Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-27T01:13:04.746Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-27T01:13:04.747Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-27T01:13:04.748Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-27T01:13:04.750Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-27T01:13:04.751Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass

2016-01-27T01:13:04.752Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-27T01:13:04.753Z - info: 

-== END ==-

2016-01-27T01:13:07.524Z - info: Running on ios test: basic

2016-01-27T01:13:07.877Z - info: Running on ios test: another

2016-01-27T01:13:08.229Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-27T01:13:08.583Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-27T01:13:08.761Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-27T01:13:09.132Z - info: Running on ios test: failed to get mobile documents path

2016-01-27T01:13:09.448Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-27T01:13:09.595Z - info: Running on ios test: #init should register the networkChanged event

2016-01-27T01:13:09.653Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-27T01:13:09.699Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-27T01:13:09.756Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-27T01:13:09.819Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-27T01:13:12.265Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-27T01:13:16.413Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-27T01:13:16.639Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-27T01:13:16.850Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-27T01:13:17.013Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-27T01:13:17.189Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-27T01:13:17.353Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-27T01:13:17.526Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-27T01:13:17.695Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-27T01:13:17.871Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-27T01:13:18.046Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-27T01:13:18.521Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-27T01:13:19.911Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-27T01:13:21.601Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-27T01:13:21.744Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-27T01:13:27.340Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-27T01:13:31.720Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-27T01:13:36.380Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-27T01:13:43.230Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-27T01:13:50.629Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-27T01:13:51.471Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-27T01:13:51.991Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-27T01:14:25.648Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-27T01:14:28.251Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5s-1)

2016-01-27T01:14:29.686Z - debug: Socket disconnected: ping timeout 1 (LGE-Nexus 5)

2016-01-27T01:14:29.702Z - debug: Socket disconnected: ping timeout 2 (samsung-SM-G900F)

2016-01-27T01:25:35.286Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)


 
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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/568182540458528__317__378_Replication_and_life_cycle_yaronyg/thali09_LGE-Nexus 5.md)





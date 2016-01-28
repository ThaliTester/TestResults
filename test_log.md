#### Test 573480784751f5c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-28T12:56:08.635Z - info: listening on *:3000

2016-01-28T12:56:09.108Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:1

2016-01-28T12:56:09.118Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:0

2016-01-28T12:56:09.121Z - info: Required number of android devices presented (2)

2016-01-28T12:56:09.124Z - info: Starting unit test run for platform: android

2016-01-28T12:56:09.147Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-01-28T12:56:09.506Z - info: Running on android test: multiplex can send data

2016-01-28T12:56:09.740Z - info: Running on android test: enqueue and run in order

2016-01-28T12:56:09.933Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-01-28T12:56:09.934Z - info: Discarding surplus device: LGE-LG-H815

2016-01-28T12:56:10.115Z - info: Running on android test: basic

2016-01-28T12:56:10.224Z - info: Running on android test: another

2016-01-28T12:56:10.304Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-28T12:56:10.341Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:4

2016-01-28T12:56:10.342Z - info: Discarding surplus device: LGE-LG-D722

2016-01-28T12:56:10.520Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-28T12:56:10.770Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-28T12:56:10.837Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-01-28T12:56:10.878Z - info: Running on android test: failed to get mobile documents path

2016-01-28T12:56:10.933Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-28T12:56:10.998Z - info: Running on android test: #init should register the networkChanged event

2016-01-28T12:56:11.044Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-28T12:56:11.093Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-28T12:56:11.171Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-28T12:56:11.216Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-28T12:56:11.265Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-28T12:56:11.330Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-28T12:56:11.393Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-28T12:56:11.466Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-28T12:56:11.524Z - debug: Socket disconnected: transport close 4 (LGE-LG-D722)

2016-01-28T12:56:11.532Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-28T12:56:11.620Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-28T12:56:11.713Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-28T12:56:11.731Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:5

2016-01-28T12:56:11.732Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-28T12:56:11.798Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-28T12:56:11.858Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-28T12:56:11.941Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-28T12:56:12.007Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-28T12:56:12.179Z - debug: Socket disconnected: transport close 5 (LGE-Nexus 5)

2016-01-28T12:56:13.588Z - debug: Device presented: samsung-SM-G800H (android) unittest socket:6

2016-01-28T12:56:13.589Z - info: Discarding surplus device: samsung-SM-G800H

2016-01-28T12:56:13.610Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:7

2016-01-28T12:56:13.611Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-28T12:56:13.652Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:8

2016-01-28T12:56:13.653Z - info: Required number of ios devices presented (2)
2016-01-28T12:56:13.655Z - info: Starting unit test run for platform: ios

2016-01-28T12:56:13.906Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-01-28T12:56:13.909Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-28T12:56:14.367Z - debug: Socket disconnected: transport close 7 (samsung-SM-N910C)

2016-01-28T12:56:14.545Z - info: Running on ios test: multiplex can send data

2016-01-28T12:56:14.755Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-01-28T12:56:15.447Z - debug: Socket disconnected: transport close 6 (samsung-SM-G800H)

2016-01-28T12:56:19.830Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:10

2016-01-28T12:56:19.831Z - info: Discarding surplus device: LGE-LG-D855

2016-01-28T12:56:20.945Z - debug: Socket disconnected: transport close 10 (LGE-LG-D855)

2016-01-28T12:56:23.966Z - info: Running on ios test: enqueue and run in order

2016-01-28T12:56:29.729Z - info: Running on ios test: basic

2016-01-28T12:56:33.307Z - info: Running on ios test: another

2016-01-28T12:56:37.503Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-28T12:56:38.832Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-28T12:56:39.020Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-28T12:56:39.324Z - info: Running on ios test: failed to get mobile documents path

2016-01-28T12:56:39.392Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-28T12:56:39.456Z - info: Running on ios test: #init should register the networkChanged event

2016-01-28T12:56:39.500Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-28T12:56:39.554Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-28T12:56:39.612Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-28T12:56:39.676Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-28T12:56:39.795Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-28T12:56:39.866Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-28T12:56:39.925Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-28T12:56:39.978Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-28T12:56:40.022Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-28T12:56:40.111Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-28T12:56:40.156Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-28T12:56:40.217Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-28T12:56:40.282Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-28T12:56:40.352Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-28T12:56:40.402Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-28T12:56:40.776Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-28T12:56:41.297Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-28T12:56:41.954Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-28T12:56:42.487Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-28T12:56:47.717Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-28T12:56:52.954Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-28T12:56:59.249Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-28T12:57:05.005Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-28T12:57:12.802Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-28T12:57:13.367Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-28T12:57:13.803Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-28T12:57:37.037Z - debug: Socket disconnected: ping timeout 0 (samsung-SM-G900F)

2016-01-28T12:57:51.138Z - info: Running on ios test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-01-28T12:57:52.193Z - info: Running on ios test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-28T12:57:52.667Z - info: Running on ios test: messages with invalid location or USN should be ignored

2016-01-28T12:57:52.729Z - info: Running on ios test: verify that Thali-specific messages are filtered correctly

2016-01-28T12:57:54.037Z - info: Running on ios test: #start should fail if called twice in a row

2016-01-28T12:57:55.991Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-28T12:57:56.735Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-01-28T12:57:56.927Z - info: Running on ios test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-28T12:57:57.419Z - info: Running on ios test: #stop can be called multiple times in a row

2016-01-28T12:58:01.065Z - info: Running on ios test: #startListeningForAdvertisements can be called multiple times in a row

2016-01-28T12:58:02.557Z - info: Running on ios test: #stopListeningForAdvertisements can be called multiple times in a row

2016-01-28T12:58:03.511Z - info: Running on ios test: #stopAdvertisingAndListening can be called multiple times in a row

2016-01-28T12:58:05.629Z - info: Running on ios test: functions are run from a queue in the right order

2016-01-28T12:58:06.633Z - info: Test run on ios complete

2016-01-28T12:58:06.635Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-28T12:58:06.637Z - info: PLATFORM: ios

2016-01-28T12:58:06.641Z - info: RESULT: PASS

2016-01-28T12:58:06.642Z - info: 49 of 49 tests completed

2016-01-28T12:58:06.644Z - info: 49/49 passed (0 failures)
2016-01-28T12:58:06.645Z - info: --- Test Details ---



2016-01-28T12:58:06.646Z - info: multiplex can send data - pass
2016-01-28T12:58:06.647Z - info: enqueue and run in order - pass
2016-01-28T12:58:06.648Z - info: basic - pass
2016-01-28T12:58:06.649Z - info: another - pass

2016-01-28T12:58:06.650Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-28T12:58:06.656Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-28T12:58:06.657Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-28T12:58:06.658Z - info: failed to get mobile documents path - pass
2016-01-28T12:58:06.660Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-28T12:58:06.661Z - info: #init should register the networkChanged event - pass
2016-01-28T12:58:06.662Z - info: #startBroadcasting should throw on null device name - pass

2016-01-28T12:58:06.663Z - info: #startBroadcasting should throw on empty string device name - pass
2016-01-28T12:58:06.664Z - info: #startBroadcasting should throw on non-number port - pass
2016-01-28T12:58:06.665Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-28T12:58:06.666Z - info: #startBroadcasting should throw on negative port - pass

2016-01-28T12:58:06.666Z - info: #startBroadcasting should throw on too large port - pass
2016-01-28T12:58:06.667Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-28T12:58:06.668Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-28T12:58:06.669Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-28T12:58:06.672Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-28T12:58:06.677Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-01-28T12:58:06.678Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-28T12:58:06.680Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-28T12:58:06.681Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-28T12:58:06.682Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-28T12:58:06.683Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-28T12:58:06.684Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-28T12:58:06.686Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-28T12:58:06.687Z - info: ThaliEmitter can discover and connect to peers - pass
2016-01-28T12:58:06.688Z - info: ThaliEmitter can discover and connect to peers and then fail on double connect - pass

2016-01-28T12:58:06.689Z - info: ThaliEmitter can discover and connect to peers and then fail on double disconnect - pass

2016-01-28T12:58:06.690Z - info: ThaliEmitter can connect and send data - pass

2016-01-28T12:58:06.691Z - info: ThaliEmitter handles socket disconnect correctly - pass

2016-01-28T12:58:06.693Z - info: ThaliReplicationManager can call start without error - pass

2016-01-28T12:58:06.694Z - info: ThaliReplicationManager receives identity - pass

2016-01-28T12:58:06.698Z - info: ThaliReplicationManager replicates database - pass

2016-01-28T12:58:06.699Z - info: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-01-28T12:58:06.700Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-28T12:58:06.702Z - info: messages with invalid location or USN should be ignored - pass

2016-01-28T12:58:06.703Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-28T12:58:06.704Z - info: #start should fail if called twice in a row - pass

2016-01-28T12:58:06.705Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-01-28T12:58:06.706Z - info: #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-01-28T12:58:06.707Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-01-28T12:58:06.708Z - info: #stop can be called multiple times in a row - pass
2016-01-28T12:58:06.709Z - info: #startListeningForAdvertisements can be called multiple times in a row - pass
2016-01-28T12:58:06.710Z - info: #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-01-28T12:58:06.711Z - info: #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-01-28T12:58:06.712Z - info: functions are run from a queue in the right order - pass
2016-01-28T12:58:06.713Z - info: 

-== END ==-

2016-01-28T12:58:09.227Z - debug: Socket disconnected: transport close 8 (Apple-IpadAir2-1)

2016-01-28T12:59:31.640Z - debug: Socket disconnected: ping timeout 2 (Apple-Iphone5s-1)

2016-01-28T13:12:52.525Z - debug: Socket disconnected: transport close 1 (motorola-Nexus 6)


 
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
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  954a12ed Test has  SUCCEEDED
Device test finished on 954a12ed 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/573480784751f5c_More_Wifi_infrastructure_features_vjrantal/thali09_LGE-Nexus 5.md)





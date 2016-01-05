#### Test 54970261aa56788 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-05T18:44:33.261Z - info: listening on *:3000

2016-01-05T18:44:33.772Z - debug: Device presented: UNITTEST-0.9987790041443849 (android) unittest socket:0

2016-01-05T18:44:34.033Z - debug: Device presented: UNITTEST-0.5806333934231285 (android) unittest socket:1

2016-01-05T18:44:34.372Z - debug: Device presented: UNITTEST-0.8417947907193201 (android) unittest socket:2

2016-01-05T18:44:34.528Z - debug: Device presented: UNITTEST-0.26201411633422966 (ios) unittest socket:3

2016-01-05T18:44:34.842Z - debug: Device presented: UNITTEST-0.5954402684465913 (android) unittest socket:4

2016-01-05T18:44:35.124Z - debug: Device presented: UNITTEST-0.5115320566123549 (android) unittest socket:5

2016-01-05T18:44:35.223Z - debug: Device presented: UNITTEST-0.04585280893339794 (android) unittest socket:6

2016-01-05T18:44:35.279Z - debug: Device presented: UNITTEST-0.995607637574644 (android) unittest socket:7

2016-01-05T18:44:35.472Z - debug: Device presented: UNITTEST-0.6702391070638255 (android) unittest socket:8

2016-01-05T18:44:35.678Z - debug: Device presented: UNITTEST-0.2506500986627519 (android) unittest socket:9

2016-01-05T18:44:35.895Z - debug: Device presented: UNITTEST-0.4680048956008085 (android) unittest socket:11

2016-01-05T18:44:35.927Z - debug: Device presented: UNITTEST-0.882950362579152 (android) unittest socket:10

2016-01-05T18:44:36.397Z - debug: Device presented: UNITTEST-0.6576463416186857 (android) unittest socket:12

2016-01-05T18:44:36.584Z - debug: Device presented: UNITTEST-0.7632731783222401 (android) unittest socket:13

2016-01-05T18:44:36.615Z - debug: Device presented: UNITTEST-0.4817008968233668 (android) unittest socket:15

2016-01-05T18:44:36.650Z - debug: Device presented: UNITTEST-0.7677130632776895 (android) unittest socket:14

2016-01-05T18:44:36.980Z - debug: Device presented: UNITTEST-0.9232487322604928 (ios) unittest socket:16

2016-01-05T18:44:36.981Z - info: Required number of devices presented

2016-01-05T18:44:36.985Z - info: Starting unit test run for platform: ios

2016-01-05T18:44:37.402Z - info: Running test: multiplex can send data

2016-01-05T18:44:37.530Z - debug: Device presented: UNITTEST-0.972748516906161 (ios) unittest socket:17

2016-01-05T18:44:37.704Z - debug: Device presented: UNITTEST-0.24331125502426576 (android) unittest socket:18

2016-01-05T18:44:38.207Z - info: Running test: basic

2016-01-05T18:44:38.226Z - debug: Device presented: UNITTEST-0.7313901327307667 (ios) unittest socket:19

2016-01-05T18:44:38.644Z - info: Running test: another

2016-01-05T18:44:38.822Z - debug: Device presented: UNITTEST-0.4984776366215323 (android) unittest socket:20

2016-01-05T18:44:38.936Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-05T18:44:39.430Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-05T18:44:39.870Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-05T18:44:40.333Z - info: Running test: failed to get mobile documents path

2016-01-05T18:44:40.620Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-05T18:44:40.925Z - info: Running test: #init should register the networkChanged event

2016-01-05T18:44:41.204Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-05T18:44:41.487Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-05T18:44:41.768Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-05T18:44:42.081Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-05T18:44:42.366Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-05T18:44:42.645Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-05T18:44:42.958Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-05T18:44:43.241Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-05T18:44:43.515Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-05T18:44:43.799Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-05T18:44:44.117Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-05T18:44:44.406Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-05T18:44:44.684Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-05T18:44:44.980Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-05T18:44:45.281Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-05T18:44:45.877Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-05T18:44:46.753Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-05T18:44:49.858Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-05T18:44:50.133Z - debug: Device presented: UNITTEST-0.07740031352063437 (android) unittest socket:21

2016-01-05T18:44:50.401Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-05T18:44:57.267Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-05T18:45:03.728Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-05T18:45:10.736Z - info: Running test: ThaliEmitter handles socket disconnect correctly

2016-01-05T18:45:11.834Z - debug: Device presented: UNITTEST-0.32537202937963816 (android) unittest socket:22

2016-01-05T18:45:11.835Z - info: Required number of devices presented

2016-01-05T18:45:11.836Z - info: Starting unit test run for platform: android

2016-01-05T18:45:13.655Z - info: Running test: multiplex can send data

2016-01-05T18:45:22.914Z - info: Running test: ThaliReplicationManager can call start without error

2016-01-05T18:45:23.130Z - info: Running test: basic

2016-01-05T18:45:23.428Z - info: Running test: ThaliReplicationManager receives identity

2016-01-05T18:45:24.585Z - info: Test run complete

2016-01-05T18:45:24.587Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-05T18:45:24.589Z - info: PLATFORM: ios

2016-01-05T18:45:24.590Z - info: RESULT: PASS

2016-01-05T18:45:24.591Z - info: 33 of 33 tests completed

2016-01-05T18:45:24.592Z - info: 33/33 passed (0 failures)

2016-01-05T18:45:24.593Z - info: ---



2016-01-05T18:45:24.594Z - info: multiplex can send data - pass

2016-01-05T18:45:24.595Z - info: basic - pass

2016-01-05T18:45:24.596Z - info: another - pass

2016-01-05T18:45:24.597Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-05T18:45:24.598Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-05T18:45:24.599Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-05T18:45:24.600Z - info: failed to get mobile documents path - pass

2016-01-05T18:45:24.601Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-05T18:45:24.602Z - info: #init should register the networkChanged event - pass

2016-01-05T18:45:24.606Z - info: #startBroadcasting should throw on null device name - pass

2016-01-05T18:45:24.608Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-05T18:45:24.609Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-05T18:45:24.610Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-05T18:45:24.611Z - info: #startBroadcasting should throw on negative port - pass

2016-01-05T18:45:24.612Z - info: #startBroadcasting should throw on too large port - pass

2016-01-05T18:45:24.613Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-05T18:45:24.613Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-05T18:45:24.614Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-05T18:45:24.616Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-05T18:45:24.617Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-05T18:45:24.618Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-05T18:45:24.619Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-05T18:45:24.620Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-05T18:45:24.621Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-05T18:45:24.622Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-05T18:45:24.623Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-05T18:45:24.624Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-05T18:45:24.624Z - info: ThaliEmitter can discover and connect to peers - pass

2016-01-05T18:45:24.625Z - info: ThaliEmitter can discover and connect to peers and then fail on double connect - pass

2016-01-05T18:45:24.628Z - info: ThaliEmitter can discover and connect to peers and then fail on double disconnect - pass

2016-01-05T18:45:24.629Z - info: ThaliEmitter handles socket disconnect correctly - pass

2016-01-05T18:45:24.630Z - info: ThaliReplicationManager can call start without error - pass

2016-01-05T18:45:24.631Z - info: ThaliReplicationManager receives identity - pass

2016-01-05T18:45:24.632Z - info: 

-== END ==-

2016-01-05T18:45:26.726Z - info: Running test: another

2016-01-05T18:45:27.545Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.9232487322604928)

2016-01-05T18:45:28.104Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.26201411633422966)

2016-01-05T18:45:33.772Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-05T18:45:39.530Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-05T18:45:44.434Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-05T18:45:51.738Z - info: Running test: failed to get mobile documents path

2016-01-05T18:45:57.689Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-05T18:46:06.281Z - info: Running test: #init should register the networkChanged event

2016-01-05T18:46:12.861Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-05T18:46:18.576Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-05T18:46:26.151Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-05T18:46:35.783Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-05T18:46:42.070Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-05T18:46:51.932Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-05T18:47:00.304Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-05T18:47:08.911Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-05T18:47:18.732Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-05T18:47:24.478Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-05T18:47:32.222Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-05T18:47:40.837Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-05T18:47:54.343Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-05T18:48:04.169Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-05T18:48:15.219Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-05T18:48:19.006Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.6702391070638255)

2016-01-05T18:48:19.015Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.32537202937963816)

2016-01-05T18:48:19.032Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.5115320566123549)

2016-01-05T18:48:19.070Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.07740031352063437)

2016-01-05T18:48:20.313Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.4680048956008085)

2016-01-05T18:48:20.581Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.7632731783222401)

2016-01-05T19:06:42.921Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.972748516906161)

2016-01-05T19:06:42.958Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.7313901327307667)

2016-01-05T19:10:44.819Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.2506500986627519)

2016-01-05T19:10:46.438Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.4817008968233668)

2016-01-05T19:10:47.700Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.24331125502426576)

2016-01-05T19:10:48.507Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.882950362579152)

2016-01-05T19:10:48.930Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.6576463416186857)

2016-01-05T19:10:51.140Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.5954402684465913)

2016-01-05T19:11:10.292Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.04585280893339794)

2016-01-05T19:12:00.650Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.995607637574644)

2016-01-05T19:12:02.344Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.8417947907193201)

2016-01-05T19:12:20.563Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.5806333934231285)

2016-01-05T19:12:23.017Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.9987790041443849)

2016-01-05T19:12:25.533Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.7677130632776895)

2016-01-05T19:15:08.040Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.4984776366215323)


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/54970261aa56788_Switch_to_Unit_Tests_tobybrad/thali09_LGE-Nexus 5.md)





#### Test 549702618c0ebdb Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-08T15:35:16.486Z - info: listening on *:3000

2016-01-08T15:35:17.079Z - debug: Device presented: UNITTEST-0.40672412092448307 (ios) unittest socket:0

2016-01-08T15:35:17.655Z - debug: Device presented: UNITTEST-0.2235834327153705 (android) unittest socket:1

2016-01-08T15:35:17.783Z - debug: Device presented: UNITTEST-0.823685870516315 (android) unittest socket:3

2016-01-08T15:35:17.787Z - debug: Device presented: UNITTEST-0.4366214863700907 (android) unittest socket:2

2016-01-08T15:35:17.802Z - debug: Device presented: UNITTEST-0.04134937316777065 (ios) unittest socket:4

2016-01-08T15:35:17.803Z - info: Required number of devices presented

2016-01-08T15:35:17.807Z - info: Starting unit test run for platform: ios

2016-01-08T15:35:18.118Z - info: Running test: multiplex can send data

2016-01-08T15:35:18.282Z - debug: Device presented: UNITTEST-0.8872931509809299 (android) unittest socket:5

2016-01-08T15:35:18.375Z - info: Running test: basic

2016-01-08T15:35:18.469Z - info: Running test: another

2016-01-08T15:35:18.547Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-08T15:35:18.556Z - debug: Device presented: UNITTEST-0.8827122440072309 (ios) unittest socket:6

2016-01-08T15:35:18.557Z - info: Discarding surplus device: UNITTEST-0.8827122440072309

2016-01-08T15:35:18.562Z - debug: Device presented: UNITTEST-0.6226076068156139 (android) unittest socket:8

2016-01-08T15:35:18.579Z - debug: Device presented: UNITTEST-0.7299265902127197 (android) unittest socket:7

2016-01-08T15:35:18.612Z - debug: Device presented: UNITTEST-0.8638715908442798 (android) unittest socket:9

2016-01-08T15:35:18.730Z - debug: Device presented: UNITTEST-0.15524681002600382 (android) unittest socket:10

2016-01-08T15:35:18.821Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-08T15:35:18.911Z - debug: Device presented: UNITTEST-0.3288187409183627 (android) unittest socket:11

2016-01-08T15:35:19.031Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-08T15:35:19.172Z - info: Running test: failed to get mobile documents path

2016-01-08T15:35:19.234Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-08T15:35:19.304Z - info: Running test: #init should register the networkChanged event

2016-01-08T15:35:19.369Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-08T15:35:19.426Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-08T15:35:19.486Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-08T15:35:19.550Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-08T15:35:19.611Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-08T15:35:19.673Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-08T15:35:19.743Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-08T15:35:19.830Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-08T15:35:19.905Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-08T15:35:19.987Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-08T15:35:20.054Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-08T15:35:20.136Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-08T15:35:20.224Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-08T15:35:20.285Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-08T15:35:20.351Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-08T15:35:20.570Z - debug: Device presented: UNITTEST-0.8696615392123256 (android) unittest socket:12

2016-01-08T15:35:20.715Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-08T15:35:20.750Z - debug: Device presented: UNITTEST-0.5874115563640325 (android) unittest socket:13

2016-01-08T15:35:20.812Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-08T15:35:20.820Z - debug: Device presented: UNITTEST-0.5153655719927237 (android) unittest socket:14

2016-01-08T15:35:20.993Z - debug: Device presented: UNITTEST-0.5002934804513961 (android) unittest socket:15

2016-01-08T15:35:21.079Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.8827122440072309)

2016-01-08T15:35:21.136Z - debug: Device presented: UNITTEST-0.5620252998798575 (android) unittest socket:16

2016-01-08T15:35:21.194Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-08T15:35:21.296Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-08T15:35:21.326Z - debug: Device presented: UNITTEST-0.046441835669720044 (android) unittest socket:17

2016-01-08T15:35:21.341Z - debug: Device presented: UNITTEST-0.36550196645983823 (android) unittest socket:18

2016-01-08T15:35:21.488Z - debug: Device presented: UNITTEST-0.36382467979790534 (ios) unittest socket:19

2016-01-08T15:35:21.489Z - info: Discarding surplus device: UNITTEST-0.36382467979790534

2016-01-08T15:35:21.784Z - debug: Device presented: UNITTEST-0.13125909779312206 (android) unittest socket:20

2016-01-08T15:35:24.030Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.36382467979790534)

2016-01-08T15:35:27.657Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-08T15:35:32.448Z - debug: Device presented: UNITTEST-0.6426715909980698 (android) unittest socket:21

2016-01-08T15:35:33.824Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-08T15:35:39.705Z - info: Running test: ThaliEmitter handles socket disconnect correctly

2016-01-08T15:35:48.518Z - debug: Device presented: UNITTEST-0.9111452713250472 (android) unittest socket:22

2016-01-08T15:35:48.520Z - info: Required number of devices presented

2016-01-08T15:35:48.522Z - info: Starting unit test run for platform: android

2016-01-08T15:35:48.598Z - info: Running test: ThaliReplicationManager can call start without error

2016-01-08T15:35:49.971Z - info: Running test: ThaliReplicationManager receives identity

2016-01-08T15:35:50.679Z - info: Test run complete

2016-01-08T15:35:50.683Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-08T15:35:50.684Z - info: PLATFORM: ios

2016-01-08T15:35:50.686Z - info: RESULT: PASS

2016-01-08T15:35:50.687Z - info: 33 of 33 tests completed

2016-01-08T15:35:50.688Z - info: 33/33 passed (0 failures)

2016-01-08T15:35:50.689Z - info: ---



2016-01-08T15:35:50.691Z - info: multiplex can send data - pass

2016-01-08T15:35:50.692Z - info: basic - pass

2016-01-08T15:35:50.693Z - info: another - pass

2016-01-08T15:35:50.694Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-08T15:35:50.695Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-08T15:35:50.696Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-08T15:35:50.697Z - info: failed to get mobile documents path - pass

2016-01-08T15:35:50.698Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-08T15:35:50.699Z - info: #init should register the networkChanged event - pass

2016-01-08T15:35:50.700Z - info: #startBroadcasting should throw on null device name - pass

2016-01-08T15:35:50.701Z - info: #startBroadcasting should throw on empty string device name - pass
2016-01-08T15:35:50.702Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-08T15:35:50.703Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-08T15:35:50.713Z - info: #startBroadcasting should throw on negative port - pass

2016-01-08T15:35:50.715Z - info: #startBroadcasting should throw on too large port - pass

2016-01-08T15:35:50.715Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-08T15:35:50.717Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-08T15:35:50.718Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-08T15:35:50.718Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-08T15:35:50.719Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-08T15:35:50.720Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-08T15:35:50.721Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-08T15:35:50.722Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-08T15:35:50.723Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-08T15:35:50.724Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-08T15:35:50.725Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-08T15:35:50.726Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-08T15:35:50.727Z - info: ThaliEmitter can discover and connect to peers - pass

2016-01-08T15:35:50.730Z - info: ThaliEmitter can discover and connect to peers and then fail on double connect - pass

2016-01-08T15:35:50.731Z - info: ThaliEmitter can discover and connect to peers and then fail on double disconnect - pass

2016-01-08T15:35:50.733Z - info: ThaliEmitter handles socket disconnect correctly - pass

2016-01-08T15:35:50.734Z - info: ThaliReplicationManager can call start without error - pass

2016-01-08T15:35:50.734Z - info: ThaliReplicationManager receives identity - pass

2016-01-08T15:35:50.735Z - info: 

-== END ==-

2016-01-08T15:35:51.776Z - info: Running test: multiplex can send data

2016-01-08T15:35:53.254Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.40672412092448307)

2016-01-08T15:35:54.368Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.04134937316777065)

2016-01-08T15:36:05.122Z - info: Running test: basic

2016-01-08T15:36:10.652Z - info: Running test: another

2016-01-08T15:36:17.226Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-08T15:36:24.810Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-08T15:36:28.688Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-08T15:36:36.064Z - info: Running test: failed to get mobile documents path

2016-01-08T15:36:46.876Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-08T15:36:54.240Z - info: Running test: #init should register the networkChanged event

2016-01-08T15:37:05.287Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-08T15:37:26.581Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-08T15:37:33.532Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-08T15:37:39.289Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-08T15:37:40.907Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-08T15:37:45.814Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-08T15:37:51.950Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-08T15:37:58.928Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-08T15:38:16.416Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-08T15:38:30.044Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-08T15:38:38.427Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-08T15:38:50.897Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-08T15:38:59.706Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-08T15:39:05.640Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-08T15:39:14.859Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-08T15:39:18.053Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.3288187409183627)

2016-01-08T15:39:18.433Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.36550196645983823)

2016-01-08T15:39:18.449Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.9111452713250472)

2016-01-08T15:39:18.922Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.6426715909980698)

2016-01-08T15:39:19.251Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.15524681002600382)

2016-01-08T15:39:19.332Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.5153655719927237)

2016-01-08T16:01:55.966Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.4366214863700907)

2016-01-08T16:01:56.762Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.046441835669720044)

2016-01-08T16:01:57.896Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.2235834327153705)

2016-01-08T16:01:58.129Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.8638715908442798)

2016-01-08T16:02:01.694Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.7299265902127197)

2016-01-08T16:02:03.872Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.5620252998798575)

2016-01-08T16:02:22.853Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.8696615392123256)

2016-01-08T16:03:06.489Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.823685870516315)

2016-01-08T16:03:08.066Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.8872931509809299)

2016-01-08T16:03:33.195Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.5874115563640325)

2016-01-08T16:03:35.207Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.6226076068156139)

2016-01-08T16:03:38.051Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.5002934804513961)

2016-01-08T16:05:37.221Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.13125909779312206)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/549702618c0ebdb_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5s-1.md)



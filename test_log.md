#### Test 5615109370bee58 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-18T14:19:54.026Z - info: listening on *:3000

2016-01-18T14:19:54.479Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:0

2016-01-18T14:19:54.537Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-01-18T14:19:54.803Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:2

2016-01-18T14:19:54.805Z - info: Required number of android devices presented (2)

2016-01-18T14:19:54.808Z - info: Starting unit test run for platform: android

2016-01-18T14:19:55.217Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-01-18T14:19:55.220Z - info: Discarding surplus device: LGE-LG-H815

2016-01-18T14:19:55.232Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:4

2016-01-18T14:19:55.233Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-18T14:19:55.429Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:5

2016-01-18T14:19:55.432Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-18T14:19:55.669Z - debug: Socket disconnected: transport close 4 (LGE-Nexus 5)

2016-01-18T14:19:55.837Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:7

2016-01-18T14:19:55.838Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-18T14:19:55.867Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:6

2016-01-18T14:19:55.868Z - info: Discarding surplus device: LGE-LG-D855

2016-01-18T14:19:55.922Z - info: Running on android test: multiplex can send data

2016-01-18T14:19:56.166Z - debug: Device presented: LGE-LG-D802 (android) unittest socket:8

2016-01-18T14:19:56.167Z - info: Discarding surplus device: LGE-LG-D802

2016-01-18T14:19:56.215Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:9

2016-01-18T14:19:56.217Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-18T14:19:56.267Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-01-18T14:19:56.276Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F)

2016-01-18T14:19:56.308Z - info: Running on android test: basic

2016-01-18T14:19:56.367Z - info: Running on android test: another

2016-01-18T14:19:56.447Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-18T14:19:56.502Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:10

2016-01-18T14:19:56.503Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-18T14:19:56.634Z - debug: Socket disconnected: transport close 6 (LGE-LG-D855)

2016-01-18T14:19:56.646Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-18T14:19:56.709Z - debug: Socket disconnected: transport close 7 (HTC-HTC Desire 820)

2016-01-18T14:19:56.805Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-18T14:19:56.819Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:11

2016-01-18T14:19:56.820Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-18T14:19:56.836Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:12

2016-01-18T14:19:56.837Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-18T14:19:56.842Z - debug: Socket disconnected: transport close 9 (samsung-SM-A300FU)

2016-01-18T14:19:56.861Z - info: Running on android test: failed to get mobile documents path

2016-01-18T14:19:56.903Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-18T14:19:56.962Z - info: Running on android test: #init should register the networkChanged event

2016-01-18T14:19:56.973Z - debug: Socket disconnected: transport close 8 (LGE-LG-D802)

2016-01-18T14:19:57.022Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-18T14:19:57.075Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-18T14:19:57.135Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-18T14:19:57.147Z - debug: Socket disconnected: transport close 10 (samsung-SM-A300FU)

2016-01-18T14:19:57.183Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-18T14:19:57.254Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-18T14:19:57.303Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-18T14:19:57.354Z - debug: Device presented: motorola-XT1072 (android) unittest socket:13

2016-01-18T14:19:57.355Z - info: Discarding surplus device: motorola-XT1072

2016-01-18T14:19:57.366Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-18T14:19:57.415Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-18T14:19:57.485Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-18T14:19:57.554Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-18T14:19:57.624Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-18T14:19:57.704Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-18T14:19:57.749Z - debug: Socket disconnected: transport close 11 (HTC-HTC Desire 820)

2016-01-18T14:19:57.756Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-18T14:19:57.805Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-18T14:19:57.822Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:14

2016-01-18T14:19:57.825Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-18T14:19:57.860Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-18T14:19:57.951Z - debug: Socket disconnected: transport close 12 (samsung-SM-G900F)

2016-01-18T14:19:58.144Z - debug: Socket disconnected: transport close 13 (motorola-XT1072)

2016-01-18T14:19:58.155Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:15

2016-01-18T14:19:58.156Z - info: Required number of ios devices presented (2)

2016-01-18T14:19:58.158Z - info: Starting unit test run for platform: ios

2016-01-18T14:19:58.201Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:16

2016-01-18T14:19:58.202Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-18T14:19:58.515Z - debug: Socket disconnected: transport close 14 (samsung-SM-N910C)

2016-01-18T14:19:58.589Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:17

2016-01-18T14:19:58.590Z - info: Discarding surplus device: LGE-LG-D722

2016-01-18T14:19:58.661Z - debug: Socket disconnected: transport close 16 (LGE-Nexus 5)

2016-01-18T14:19:58.668Z - info: Running on ios test: multiplex can send data

2016-01-18T14:19:58.953Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:18

2016-01-18T14:19:58.954Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-18T14:19:58.963Z - info: Running on ios test: basic

2016-01-18T14:19:59.080Z - info: Running on ios test: another

2016-01-18T14:19:59.170Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-18T14:19:59.213Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:19

2016-01-18T14:19:59.214Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-18T14:19:59.424Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-18T14:19:59.618Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-18T14:19:59.713Z - debug: Socket disconnected: transport close 17 (LGE-LG-D722)

2016-01-18T14:19:59.814Z - info: Running on ios test: failed to get mobile documents path

2016-01-18T14:20:00.207Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-18T14:20:00.324Z - info: Running on ios test: #init should register the networkChanged event

2016-01-18T14:20:00.773Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-18T14:20:00.962Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-18T14:20:01.155Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-18T14:20:01.206Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-18T14:20:01.286Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-18T14:20:01.312Z - debug: Socket disconnected: transport close 18 (Apple-Iphone6-1)

2016-01-18T14:20:01.330Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-18T14:20:01.376Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-18T14:20:01.461Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-18T14:20:01.511Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-18T14:20:01.525Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-18T14:20:01.569Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-18T14:20:01.617Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-18T14:20:01.666Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-18T14:20:01.758Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-18T14:20:01.875Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-18T14:20:01.969Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-18T14:20:02.391Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-18T14:20:02.731Z - debug: Socket disconnected: transport close 19 (Apple-Iphone5-1)

2016-01-18T14:20:03.239Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:20

2016-01-18T14:20:03.240Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-18T14:20:03.299Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-18T14:20:03.584Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-18T14:20:04.237Z - debug: Socket disconnected: transport close 20 (samsung-SM-G800F)

2016-01-18T14:20:05.198Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-18T14:20:05.594Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-18T14:20:06.034Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-18T14:20:06.710Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-18T14:20:06.848Z - info: Running on android test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-18T14:20:06.903Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-18T14:20:06.950Z - info: Test run on android complete

2016-01-18T14:20:06.953Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-18T14:20:06.954Z - info: PLATFORM: android

2016-01-18T14:20:06.955Z - info: RESULT: PASS

2016-01-18T14:20:06.957Z - info: 30 of 30 tests completed
2016-01-18T14:20:06.958Z - info: 30/30 passed (0 failures)
2016-01-18T14:20:06.958Z - info: --- Test Details ---


2016-01-18T14:20:06.959Z - info: multiplex can send data - pass

2016-01-18T14:20:06.960Z - info: basic - pass

2016-01-18T14:20:06.962Z - info: another - pass

2016-01-18T14:20:06.963Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-18T14:20:06.964Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-18T14:20:06.965Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-18T14:20:06.968Z - info: failed to get mobile documents path - pass

2016-01-18T14:20:06.972Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-18T14:20:06.973Z - info: #init should register the networkChanged event - pass

2016-01-18T14:20:06.974Z - info: #startBroadcasting should throw on null device name - pass

2016-01-18T14:20:06.975Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-18T14:20:06.987Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-18T14:20:06.988Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-18T14:20:06.989Z - info: #startBroadcasting should throw on negative port - pass

2016-01-18T14:20:06.990Z - info: #startBroadcasting should throw on too large port - pass

2016-01-18T14:20:06.991Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-18T14:20:06.992Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-18T14:20:06.993Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-18T14:20:06.994Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-18T14:20:06.995Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-18T14:20:06.996Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-18T14:20:06.997Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-18T14:20:06.998Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-18T14:20:06.999Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-18T14:20:07.000Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-18T14:20:07.001Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-18T14:20:07.002Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-18T14:20:07.003Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass
2016-01-18T14:20:07.004Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass
2016-01-18T14:20:07.004Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-18T14:20:07.005Z - info: 

-== END ==-

2016-01-18T14:20:11.897Z - debug: Device presented: motorola-XT1039 (android) unittest socket:21

2016-01-18T14:20:11.898Z - info: Discarding surplus device: motorola-XT1039

2016-01-18T14:20:12.562Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-18T14:20:12.866Z - debug: Socket disconnected: transport close 21 (motorola-XT1039)

2016-01-18T14:20:21.371Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-18T14:20:27.713Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-18T14:20:35.525Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-18T14:20:47.113Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-18T14:20:47.631Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-18T14:20:49.051Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-18T14:21:23.556Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-18T14:21:23.566Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1)

2016-01-18T14:21:31.964Z - debug: Socket disconnected: ping timeout 0 (samsung-SM-A500FU)

2016-01-18T14:21:31.968Z - debug: Socket disconnected: ping timeout 2 (samsung-SM-A500FU)

2016-01-18T14:32:27.328Z - debug: Socket disconnected: transport close 15 (Apple-IpadAir2-1)


 
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
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed. [SUCCESS]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on ZX1C223JKW 
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5615109370bee58_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_LGE-Nexus 5.md)





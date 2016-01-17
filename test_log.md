#### Test 5615109319b4771 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-17T15:37:12.667Z - info: listening on *:3000

2016-01-17T15:37:13.287Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:0

2016-01-17T15:37:13.299Z - debug: Device presented: motorola-XT1072 (android) unittest socket:1

2016-01-17T15:37:13.303Z - info: Required number of android devices presented (2)

2016-01-17T15:37:13.306Z - info: Starting unit test run for platform: android

2016-01-17T15:37:13.339Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-01-17T15:37:13.533Z - info: Running on android test: multiplex can send data

2016-01-17T15:37:13.652Z - info: Running on android test: basic

2016-01-17T15:37:13.691Z - info: Running on android test: another

2016-01-17T15:37:13.763Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-17T15:37:13.912Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-01-17T15:37:13.917Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-17T15:37:13.962Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-17T15:37:14.107Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:4

2016-01-17T15:37:14.108Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-17T15:37:14.128Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-17T15:37:14.183Z - info: Running on android test: failed to get mobile documents path

2016-01-17T15:37:14.249Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-17T15:37:14.325Z - info: Running on android test: #init should register the networkChanged event

2016-01-17T15:37:14.337Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-01-17T15:37:14.339Z - info: Required number of ios devices presented (2)

2016-01-17T15:37:14.340Z - info: Starting unit test run for platform: ios

2016-01-17T15:37:14.391Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-17T15:37:14.452Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-17T15:37:14.458Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:6

2016-01-17T15:37:14.459Z - info: Discarding surplus device: LGE-LG-D722

2016-01-17T15:37:14.495Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-17T15:37:14.548Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-17T15:37:14.603Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-17T15:37:14.651Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C)

2016-01-17T15:37:14.673Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-17T15:37:14.728Z - debug: Socket disconnected: transport close 4 (samsung-SM-A300FU)

2016-01-17T15:37:14.757Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-17T15:37:14.860Z - info: Running on ios test: multiplex can send data

2016-01-17T15:37:14.901Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-17T15:37:14.935Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:7

2016-01-17T15:37:14.936Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-17T15:37:14.991Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-17T15:37:14.997Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:8

2016-01-17T15:37:14.998Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-01-17T15:37:15.017Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:9

2016-01-17T15:37:15.018Z - info: Discarding surplus device: LGE-LG-D855

2016-01-17T15:37:15.058Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-17T15:37:15.117Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-17T15:37:15.190Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-17T15:37:15.237Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-17T15:37:15.288Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-17T15:37:15.360Z - debug: Socket disconnected: transport close 7 (LGE-Nexus 5)

2016-01-17T15:37:15.365Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-17T15:37:15.566Z - debug: Socket disconnected: transport close 6 (LGE-LG-D722)

2016-01-17T15:37:15.615Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:10

2016-01-17T15:37:15.616Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-17T15:37:15.699Z - debug: Socket disconnected: transport close 9 (LGE-LG-D855)

2016-01-17T15:37:15.764Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:12

2016-01-17T15:37:15.765Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-17T15:37:15.774Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:11

2016-01-17T15:37:15.775Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-17T15:37:16.238Z - debug: Socket disconnected: transport close 12 (LGE-Nexus 5)

2016-01-17T15:37:16.249Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:13

2016-01-17T15:37:16.250Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-17T15:37:16.316Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:15

2016-01-17T15:37:16.317Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-17T15:37:16.383Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:14

2016-01-17T15:37:16.384Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-17T15:37:16.512Z - debug: Socket disconnected: transport close 10 (HTC-HTC Desire 820)

2016-01-17T15:37:16.703Z - debug: Socket disconnected: transport close 11 (samsung-SM-G900F)

2016-01-17T15:37:16.865Z - debug: Socket disconnected: transport close 13 (samsung-SM-A500FU)

2016-01-17T15:37:16.992Z - debug: Socket disconnected: transport close 15 (samsung-SM-A500FU)

2016-01-17T15:37:17.200Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:16

2016-01-17T15:37:17.202Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-17T15:37:17.239Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:17

2016-01-17T15:37:17.240Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-17T15:37:17.393Z - debug: Device presented: LGE-LG-D802 (android) unittest socket:18

2016-01-17T15:37:17.394Z - info: Discarding surplus device: LGE-LG-D802

2016-01-17T15:37:17.499Z - debug: Socket disconnected: transport close 8 (Apple-IpadAir2-1)

2016-01-17T15:37:17.538Z - info: Running on ios test: basic

2016-01-17T15:37:17.591Z - info: Running on ios test: another

2016-01-17T15:37:17.649Z - debug: Socket disconnected: transport close 14 (samsung-SM-G900F)

2016-01-17T15:37:17.658Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-17T15:37:17.772Z - debug: Socket disconnected: transport close 16 (samsung-SM-A300FU)

2016-01-17T15:37:17.795Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:19

2016-01-17T15:37:17.796Z - info: Discarding surplus device: LGE-LG-H815

2016-01-17T15:37:17.911Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-17T15:37:18.124Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-17T15:37:18.152Z - debug: Socket disconnected: transport close 18 (LGE-LG-D802)

2016-01-17T15:37:18.245Z - info: Running on ios test: failed to get mobile documents path

2016-01-17T15:37:18.294Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-17T15:37:18.354Z - info: Running on ios test: #init should register the networkChanged event

2016-01-17T15:37:18.402Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-17T15:37:18.455Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-17T15:37:18.506Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-17T15:37:18.560Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-17T15:37:18.566Z - debug: Socket disconnected: transport close 19 (LGE-LG-H815)

2016-01-17T15:37:18.607Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-17T15:37:18.658Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-17T15:37:18.710Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-17T15:37:18.879Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-17T15:37:18.927Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-17T15:37:18.981Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-17T15:37:19.034Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-17T15:37:19.093Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-17T15:37:19.165Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-17T15:37:19.217Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-17T15:37:19.270Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-17T15:37:19.663Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-17T15:37:19.723Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-17T15:37:19.776Z - debug: Socket disconnected: transport close 17 (Apple-Iphone6-1)

2016-01-17T15:37:19.803Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-17T15:37:20.211Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-17T15:37:23.010Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:20

2016-01-17T15:37:23.011Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-17T15:37:24.112Z - debug: Socket disconnected: transport close 20 (samsung-SM-G800F)

2016-01-17T15:37:24.519Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-17T15:37:29.682Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-17T15:37:33.888Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-17T15:37:41.748Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-17T15:37:49.679Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-17T15:37:52.009Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-17T15:37:52.601Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-17T15:37:54.383Z - debug: Device presented: motorola-XT1039 (android) unittest socket:21

2016-01-17T15:37:54.384Z - info: Discarding surplus device: motorola-XT1039

2016-01-17T15:37:55.152Z - debug: Socket disconnected: transport close 21 (motorola-XT1039)

2016-01-17T15:38:29.957Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-17T15:38:30.932Z - info: Running on ios test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-17T15:38:31.856Z - info: Running on ios test: verify that Thali-specific messages are filtered correctly

2016-01-17T15:38:32.437Z - info: Test run on ios complete

2016-01-17T15:38:32.440Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-17T15:38:32.443Z - info: PLATFORM: ios

2016-01-17T15:38:32.446Z - info: RESULT: PASS

2016-01-17T15:38:32.449Z - info: 38 of 38 tests completed

2016-01-17T15:38:32.451Z - info: 38/38 passed (0 failures)

2016-01-17T15:38:32.454Z - info: --- Test Details ---



2016-01-17T15:38:32.461Z - info: multiplex can send data - pass
2016-01-17T15:38:32.462Z - info: basic - pass
2016-01-17T15:38:32.462Z - info: another - pass
2016-01-17T15:38:32.463Z - info: successfully create a new pkcs12 file and return hash value - pass
2016-01-17T15:38:32.464Z - info: successfully read a previous pkcs12 file and return hash value - pass
2016-01-17T15:38:32.464Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-17T15:38:32.465Z - info: failed to get mobile documents path - pass
2016-01-17T15:38:32.466Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-17T15:38:32.466Z - info: #init should register the networkChanged event - pass

2016-01-17T15:38:32.467Z - info: #startBroadcasting should throw on null device name - pass
2016-01-17T15:38:32.468Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-17T15:38:32.468Z - info: #startBroadcasting should throw on non-number port - pass
2016-01-17T15:38:32.469Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-17T15:38:32.470Z - info: #startBroadcasting should throw on negative port - pass
2016-01-17T15:38:32.470Z - info: #startBroadcasting should throw on too large port - pass

2016-01-17T15:38:32.471Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-17T15:38:32.472Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-17T15:38:32.472Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-17T15:38:32.473Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-17T15:38:32.473Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-17T15:38:32.474Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-17T15:38:32.475Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-17T15:38:32.475Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-17T15:38:32.476Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-17T15:38:32.476Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-17T15:38:32.477Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-17T15:38:32.478Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-17T15:38:32.478Z - info: ThaliEmitter can discover and connect to peers - pass

2016-01-17T15:38:32.479Z - info: ThaliEmitter can discover and connect to peers and then fail on double connect - pass
2016-01-17T15:38:32.479Z - info: ThaliEmitter can discover and connect to peers and then fail on double disconnect - pass
2016-01-17T15:38:32.480Z - info: ThaliEmitter can connect and send data - pass
2016-01-17T15:38:32.481Z - info: ThaliEmitter handles socket disconnect correctly - pass
2016-01-17T15:38:32.482Z - info: ThaliReplicationManager can call start without error - pass
2016-01-17T15:38:32.482Z - info: ThaliReplicationManager receives identity - pass
2016-01-17T15:38:32.483Z - info: ThaliReplicationManager replicates database - pass
2016-01-17T15:38:32.484Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass
2016-01-17T15:38:32.485Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass
2016-01-17T15:38:32.485Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-17T15:38:32.486Z - info: 

-== END ==-

2016-01-17T15:38:35.516Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-01-17T15:38:35.694Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)

2016-01-17T15:38:40.390Z - debug: Socket disconnected: ping timeout 0 (HTC-HTC Desire 820)

2016-01-17T15:55:11.553Z - debug: Socket disconnected: transport close 1 (motorola-XT1072)


 
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
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-Nexus 5.md)

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
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_LGE-LG-D855.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on 022678fb504e29b0 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5615109319b4771_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5s-1.md)



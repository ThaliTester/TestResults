#### Test 57132760f6ec045 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-25T21:47:54.296Z - info: listening on *:3000

2016-01-25T21:47:55.147Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:0

2016-01-25T21:47:55.449Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:1

2016-01-25T21:47:55.452Z - info: Required number of android devices presented (2)

2016-01-25T21:47:55.456Z - info: Starting unit test run for platform: android

2016-01-25T21:47:55.768Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-01-25T21:47:56.012Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:3

2016-01-25T21:47:56.013Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-25T21:47:56.080Z - info: Running on android test: multiplex can send data

2016-01-25T21:47:56.295Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:4

2016-01-25T21:47:56.298Z - info: Discarding surplus device: LGE-LG-D722

2016-01-25T21:47:56.499Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-01-25T21:47:56.500Z - info: Required number of ios devices presented (2)

2016-01-25T21:47:56.502Z - info: Starting unit test run for platform: ios

2016-01-25T21:47:56.556Z - debug: Socket disconnected: transport close 3 (LGE-Nexus 5)

2016-01-25T21:47:56.610Z - info: Running on android test: basic

2016-01-25T21:47:56.698Z - info: Running on android test: another

2016-01-25T21:47:56.793Z - info: Running on ios test: multiplex can send data

2016-01-25T21:47:56.855Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:6

2016-01-25T21:47:56.856Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-25T21:47:56.867Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-25T21:47:56.900Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:7

2016-01-25T21:47:56.901Z - info: Discarding surplus device: LGE-LG-H815

2016-01-25T21:47:57.009Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-25T21:47:57.129Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-25T21:47:57.209Z - info: Running on android test: failed to get mobile documents path

2016-01-25T21:47:57.271Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-25T21:47:57.321Z - info: Running on android test: #init should register the networkChanged event

2016-01-25T21:47:57.398Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-25T21:47:57.414Z - debug: Socket disconnected: transport close 4 (LGE-LG-D722)

2016-01-25T21:47:57.466Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-25T21:47:57.483Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:8

2016-01-25T21:47:57.484Z - info: Discarding surplus device: LGE-LG-D855

2016-01-25T21:47:57.542Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-25T21:47:57.580Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:9

2016-01-25T21:47:57.581Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-25T21:47:57.621Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-25T21:47:57.682Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-25T21:47:57.783Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-25T21:47:57.918Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-25T21:47:57.928Z - debug: Socket disconnected: transport close 7 (LGE-LG-H815)

2016-01-25T21:47:57.992Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:10

2016-01-25T21:47:57.995Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-01-25T21:47:58.057Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-25T21:47:58.126Z - debug: Socket disconnected: transport close 8 (LGE-LG-D855)

2016-01-25T21:47:58.137Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-25T21:47:58.222Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-25T21:47:58.236Z - debug: Socket disconnected: transport close 9 (samsung-SM-N910C)

2016-01-25T21:47:58.255Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:11

2016-01-25T21:47:58.257Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-25T21:47:58.299Z - debug: Socket disconnected: transport close 6 (samsung-SM-G800F)

2016-01-25T21:47:58.307Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-25T21:47:58.317Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:12

2016-01-25T21:47:58.318Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-25T21:47:58.376Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-25T21:47:58.437Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-25T21:47:58.487Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-25T21:47:58.538Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-25T21:47:59.548Z - debug: Socket disconnected: transport close 11 (samsung-SM-G900F)

2016-01-25T21:47:59.555Z - info: Running on ios test: basic

2016-01-25T21:47:59.790Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-25T21:47:59.814Z - info: Running on ios test: another

2016-01-25T21:47:59.873Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-25T21:48:00.217Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-25T21:48:00.274Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-25T21:48:00.374Z - debug: Socket disconnected: transport close 10 (Apple-IpadAir2-1)

2016-01-25T21:48:00.455Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-25T21:48:00.610Z - info: Running on ios test: failed to get mobile documents path

2016-01-25T21:48:00.720Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-25T21:48:00.731Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-25T21:48:00.804Z - info: Running on ios test: #init should register the networkChanged event

2016-01-25T21:48:00.867Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-25T21:48:00.952Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-25T21:48:01.055Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-25T21:48:01.116Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-25T21:48:01.182Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-25T21:48:01.202Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-25T21:48:01.245Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-25T21:48:01.305Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-25T21:48:01.372Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-25T21:48:01.453Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-25T21:48:01.473Z - info: Running on android test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-25T21:48:01.535Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-25T21:48:01.566Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-25T21:48:01.607Z - debug: Socket disconnected: transport close 12 (Apple-Iphone5-1)

2016-01-25T21:48:01.613Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-25T21:48:01.653Z - info: Test run on android complete

2016-01-25T21:48:01.657Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-25T21:48:01.659Z - info: PLATFORM: android

2016-01-25T21:48:01.661Z - info: RESULT: PASS

2016-01-25T21:48:01.662Z - info: 30 of 30 tests completed

2016-01-25T21:48:01.663Z - info: 30/30 passed (0 failures)

2016-01-25T21:48:01.664Z - info: --- Test Details ---



2016-01-25T21:48:01.665Z - info: multiplex can send data - pass

2016-01-25T21:48:01.666Z - info: basic - pass

2016-01-25T21:48:01.667Z - info: another - pass

2016-01-25T21:48:01.668Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-25T21:48:01.669Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-25T21:48:01.669Z - info: failed to extract public key because of corrupt pkcs12 file - pass
2016-01-25T21:48:01.670Z - info: failed to get mobile documents path - pass

2016-01-25T21:48:01.671Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-25T21:48:01.672Z - info: #init should register the networkChanged event - pass

2016-01-25T21:48:01.673Z - info: #startBroadcasting should throw on null device name - pass
2016-01-25T21:48:01.673Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-25T21:48:01.674Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-25T21:48:01.675Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-25T21:48:01.676Z - info: #startBroadcasting should throw on negative port - pass
2016-01-25T21:48:01.676Z - info: #startBroadcasting should throw on too large port - pass

2016-01-25T21:48:01.677Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-25T21:48:01.678Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-25T21:48:01.679Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-25T21:48:01.679Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-25T21:48:01.680Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-25T21:48:01.681Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-25T21:48:01.682Z - info: should call Mobile("Disconnect") without an error - pass
2016-01-25T21:48:01.683Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-25T21:48:01.684Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
2016-01-25T21:48:01.688Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-25T21:48:01.689Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-25T21:48:01.689Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-25T21:48:01.690Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-25T21:48:01.691Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass
2016-01-25T21:48:01.692Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-25T21:48:01.693Z - info: 

-== END ==-

2016-01-25T21:48:01.725Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-25T21:48:01.801Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-25T21:48:01.864Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-25T21:48:01.954Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-25T21:48:02.275Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-25T21:48:02.433Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-25T21:48:02.901Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-25T21:48:03.305Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-25T21:48:08.755Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-25T21:48:15.059Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-25T21:48:21.822Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-25T21:48:28.634Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-25T21:48:35.997Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-25T21:48:36.926Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-25T21:48:37.500Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-25T21:49:04.235Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-25T21:49:05.847Z - info: Running on ios test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-25T21:49:06.193Z - info: Running on ios test: verify that Thali-specific messages are filtered correctly

2016-01-25T21:49:06.452Z - info: Test run on ios complete

2016-01-25T21:49:06.453Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-25T21:49:06.454Z - info: PLATFORM: ios

2016-01-25T21:49:06.455Z - info: RESULT: PASS

2016-01-25T21:49:06.456Z - info: 38 of 38 tests completed

2016-01-25T21:49:06.457Z - info: 38/38 passed (0 failures)

2016-01-25T21:49:06.458Z - info: --- Test Details ---


2016-01-25T21:49:06.459Z - info: multiplex can send data - pass
2016-01-25T21:49:06.460Z - info: basic - pass
2016-01-25T21:49:06.461Z - info: another - pass
2016-01-25T21:49:06.462Z - info: successfully create a new pkcs12 file and return hash value - pass
2016-01-25T21:49:06.463Z - info: successfully read a previous pkcs12 file and return hash value - pass
2016-01-25T21:49:06.464Z - info: failed to extract public key because of corrupt pkcs12 file - pass
2016-01-25T21:49:06.465Z - info: failed to get mobile documents path - pass
2016-01-25T21:49:06.466Z - info: #init should register the peerAvailabilityChanged event - pass
2016-01-25T21:49:06.467Z - info: #init should register the networkChanged event - pass
2016-01-25T21:49:06.468Z - info: #startBroadcasting should throw on null device name - pass

2016-01-25T21:49:06.469Z - info: #startBroadcasting should throw on empty string device name - pass
2016-01-25T21:49:06.469Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-25T21:49:06.470Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-25T21:49:06.471Z - info: #startBroadcasting should throw on negative port - pass
2016-01-25T21:49:06.472Z - info: #startBroadcasting should throw on too large port - pass

2016-01-25T21:49:06.473Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-25T21:49:06.474Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-25T21:49:06.474Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-25T21:49:06.475Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-25T21:49:06.476Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-25T21:49:06.477Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-25T21:49:06.478Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-25T21:49:06.482Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-25T21:49:06.483Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-25T21:49:06.483Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-25T21:49:06.494Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-25T21:49:06.495Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-25T21:49:06.496Z - info: ThaliEmitter can discover and connect to peers - pass

2016-01-25T21:49:06.497Z - info: ThaliEmitter can discover and connect to peers and then fail on double connect - pass
2016-01-25T21:49:06.498Z - info: ThaliEmitter can discover and connect to peers and then fail on double disconnect - pass

2016-01-25T21:49:06.498Z - info: ThaliEmitter can connect and send data - pass

2016-01-25T21:49:06.499Z - info: ThaliEmitter handles socket disconnect correctly - pass
2016-01-25T21:49:06.500Z - info: ThaliReplicationManager can call start without error - pass

2016-01-25T21:49:06.501Z - info: ThaliReplicationManager receives identity - pass
2016-01-25T21:49:06.502Z - info: ThaliReplicationManager replicates database - pass

2016-01-25T21:49:06.502Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-25T21:49:06.503Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass

2016-01-25T21:49:06.504Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-25T21:49:06.505Z - info: 

-== END ==-


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
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Device test finished on 320414cd475f91e3 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/57132760f6ec045__378_thaliPeerPoolInterface_yaronyg/iOS_Iphone5s-1.md)



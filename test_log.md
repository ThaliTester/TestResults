#### Test 561510933390750 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-17T12:16:32.102Z - info: listening on *:3000

2016-01-17T12:16:32.894Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:0

2016-01-17T12:16:32.918Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-01-17T12:16:33.106Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-01-17T12:16:33.109Z - info: Required number of android devices presented (2)

2016-01-17T12:16:33.113Z - info: Starting unit test run for platform: android

2016-01-17T12:16:33.157Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:3

2016-01-17T12:16:33.158Z - info: Discarding surplus device: LGE-LG-D855

2016-01-17T12:16:33.289Z - info: Running on android test: basic

2016-01-17T12:16:33.355Z - info: Running on android test: another

2016-01-17T12:16:33.395Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-17T12:16:33.428Z - debug: Device presented: LGE-LG-D802 (android) unittest socket:4

2016-01-17T12:16:33.430Z - info: Discarding surplus device: LGE-LG-D802

2016-01-17T12:16:33.595Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-17T12:16:33.740Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-17T12:16:33.800Z - info: Running on android test: failed to get mobile documents path

2016-01-17T12:16:33.842Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-17T12:16:33.904Z - info: Running on android test: #init should register the networkChanged event

2016-01-17T12:16:33.924Z - debug: Socket disconnected: transport close 3 (LGE-LG-D855)

2016-01-17T12:16:33.986Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-17T12:16:34.043Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-17T12:16:34.069Z - debug: Device presented: motorola-XT1072 (android) unittest socket:5

2016-01-17T12:16:34.070Z - info: Discarding surplus device: motorola-XT1072

2016-01-17T12:16:34.098Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-17T12:16:34.167Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-17T12:16:34.211Z - debug: Socket disconnected: transport close 4 (LGE-LG-D802)

2016-01-17T12:16:34.225Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-17T12:16:34.273Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-17T12:16:34.319Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-17T12:16:34.382Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-17T12:16:34.448Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-17T12:16:34.499Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-17T12:16:34.571Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-17T12:16:34.648Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-17T12:16:34.730Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-17T12:16:34.843Z - debug: Socket disconnected: transport close 5 (motorola-XT1072)

2016-01-17T12:16:34.858Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-17T12:16:34.896Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:7

2016-01-17T12:16:34.897Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-17T12:16:34.927Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:6

2016-01-17T12:16:34.928Z - info: Discarding surplus device: LGE-LG-D722

2016-01-17T12:16:34.933Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-17T12:16:35.089Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:8

2016-01-17T12:16:35.091Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-17T12:16:35.271Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:9

2016-01-17T12:16:35.272Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-17T12:16:35.329Z - debug: Socket disconnected: transport close 7 (LGE-Nexus 5)

2016-01-17T12:16:35.598Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:10

2016-01-17T12:16:35.599Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-17T12:16:35.799Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:11

2016-01-17T12:16:35.800Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-17T12:16:36.007Z - debug: Socket disconnected: transport close 8 (HTC-HTC Desire 820)

2016-01-17T12:16:36.033Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:12

2016-01-17T12:16:36.035Z - info: Discarding surplus device: HTC-HTC One M8s

2016-01-17T12:16:36.071Z - debug: Socket disconnected: transport close 9 (HTC-HTC Desire 820)

2016-01-17T12:16:36.119Z - debug: Socket disconnected: transport close 6 (LGE-LG-D722)

2016-01-17T12:16:36.134Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:13

2016-01-17T12:16:36.136Z - info: Required number of ios devices presented (2)

2016-01-17T12:16:36.138Z - info: Starting unit test run for platform: ios

2016-01-17T12:16:36.409Z - debug: Socket disconnected: transport close 11 (samsung-SM-A500FU)

2016-01-17T12:16:36.439Z - debug: Socket disconnected: transport close 10 (samsung-SM-G900F)

2016-01-17T12:16:36.459Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:15

2016-01-17T12:16:36.460Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-17T12:16:36.472Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:14

2016-01-17T12:16:36.473Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-17T12:16:36.652Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:16

2016-01-17T12:16:36.653Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-17T12:16:36.766Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:17

2016-01-17T12:16:36.768Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-17T12:16:36.925Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:18

2016-01-17T12:16:36.926Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-17T12:16:36.936Z - debug: Socket disconnected: transport close 12 (HTC-HTC One M8s)

2016-01-17T12:16:36.944Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:19

2016-01-17T12:16:36.946Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-17T12:16:36.984Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:20

2016-01-17T12:16:36.985Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-17T12:16:37.203Z - debug: Socket disconnected: transport close 15 (samsung-SM-N910C)

2016-01-17T12:16:37.347Z - debug: Socket disconnected: transport close 14 (samsung-SM-G900F)

2016-01-17T12:16:37.401Z - debug: Socket disconnected: transport close 17 (samsung-SM-A500FU)

2016-01-17T12:16:37.441Z - debug: Socket disconnected: transport close 19 (LGE-Nexus 5)

2016-01-17T12:16:37.503Z - debug: Socket disconnected: transport close 18 (samsung-SM-A300FU)

2016-01-17T12:16:37.772Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-17T12:16:38.588Z - info: Running on ios test: basic

2016-01-17T12:16:39.011Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-17T12:16:39.496Z - debug: Socket disconnected: transport close 20 (Apple-Iphone6-1)

2016-01-17T12:16:39.860Z - debug: Socket disconnected: transport close 16 (Apple-Iphone5-1)

2016-01-17T12:16:40.475Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-17T12:16:41.838Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-17T12:16:41.985Z - info: Running on android test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-17T12:16:42.186Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-17T12:16:42.378Z - info: Test run on android complete

2016-01-17T12:16:42.380Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-17T12:16:42.381Z - info: PLATFORM: android

2016-01-17T12:16:42.383Z - info: RESULT: PASS

2016-01-17T12:16:42.384Z - info: 29 of 29 tests completed

2016-01-17T12:16:42.385Z - info: 29/29 passed (0 failures)

2016-01-17T12:16:42.386Z - info: --- Test Details ---



2016-01-17T12:16:42.387Z - info: basic - pass

2016-01-17T12:16:42.388Z - info: another - pass

2016-01-17T12:16:42.389Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-17T12:16:42.390Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-17T12:16:42.391Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-17T12:16:42.392Z - info: failed to get mobile documents path - pass

2016-01-17T12:16:42.395Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-17T12:16:42.396Z - info: #init should register the networkChanged event - pass

2016-01-17T12:16:42.397Z - info: #startBroadcasting should throw on null device name - pass

2016-01-17T12:16:42.398Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-17T12:16:42.399Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-17T12:16:42.400Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-17T12:16:42.401Z - info: #startBroadcasting should throw on negative port - pass

2016-01-17T12:16:42.402Z - info: #startBroadcasting should throw on too large port - pass

2016-01-17T12:16:42.403Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-17T12:16:42.404Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-17T12:16:42.405Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-17T12:16:42.406Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-17T12:16:42.406Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-17T12:16:42.407Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-17T12:16:42.412Z - info: should call Mobile("Disconnect") without an error - pass
2016-01-17T12:16:42.413Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-17T12:16:42.414Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
2016-01-17T12:16:42.414Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-17T12:16:42.415Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-17T12:16:42.416Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-17T12:16:42.417Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-17T12:16:42.418Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass

2016-01-17T12:16:42.419Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-17T12:16:42.420Z - info: 

-== END ==-

2016-01-17T12:16:45.986Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:21

2016-01-17T12:16:45.987Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-17T12:16:47.078Z - debug: Socket disconnected: transport close 21 (samsung-SM-G800F)

2016-01-17T12:16:50.148Z - debug: Device presented: motorola-XT1039 (android) unittest socket:22

2016-01-17T12:16:50.152Z - info: Discarding surplus device: motorola-XT1039

2016-01-17T12:16:51.063Z - debug: Socket disconnected: transport close 22 (motorola-XT1039)

2016-01-17T12:18:07.508Z - debug: Socket disconnected: ping timeout 0 (samsung-SM-A300FU)

2016-01-17T12:18:07.518Z - debug: Socket disconnected: ping timeout 2 (LGE-LG-H815)

2016-01-17T12:29:10.554Z - debug: Socket disconnected: transport close 13 (Apple-IpadAir2-1)

2016-01-17T12:29:10.650Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : No Error

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_server.md)




###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
Device test finished on TA4750HV7I 
Android task is completed. [SUCCESS]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on HT574YC04723 
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/561510933390750_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_LGE-Nexus 5.md)



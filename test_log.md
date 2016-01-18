#### Test 56151093f6e24ff Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-18T13:57:15.414Z - info: listening on *:3000

2016-01-18T13:57:15.967Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:0

2016-01-18T13:57:15.989Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:1

2016-01-18T13:57:15.992Z - info: Required number of android devices presented (2)

2016-01-18T13:57:15.995Z - info: Starting unit test run for platform: android

2016-01-18T13:57:16.126Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-01-18T13:57:16.196Z - info: Running on android test: multiplex can send data

2016-01-18T13:57:16.229Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:3

2016-01-18T13:57:16.231Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-18T13:57:16.324Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:4

2016-01-18T13:57:16.325Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-18T13:57:16.654Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:5

2016-01-18T13:57:16.655Z - info: Discarding surplus device: LGE-LG-D855

2016-01-18T13:57:16.661Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:6

2016-01-18T13:57:16.662Z - info: Required number of ios devices presented (2)

2016-01-18T13:57:16.663Z - info: Starting unit test run for platform: ios

2016-01-18T13:57:17.012Z - debug: Socket disconnected: transport close 4 (samsung-SM-A500FU)

2016-01-18T13:57:17.053Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:7

2016-01-18T13:57:17.057Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-18T13:57:17.128Z - debug: Socket disconnected: transport close 3 (HTC-HTC Desire 820)

2016-01-18T13:57:17.176Z - info: Running on ios test: multiplex can send data

2016-01-18T13:57:17.522Z - debug: Socket disconnected: transport close 7 (LGE-Nexus 5)

2016-01-18T13:57:17.772Z - debug: Device presented: motorola-XT1072 (android) unittest socket:8

2016-01-18T13:57:17.773Z - info: Discarding surplus device: motorola-XT1072

2016-01-18T13:57:17.801Z - info: Running on android test: basic

2016-01-18T13:57:18.088Z - debug: Socket disconnected: transport close 5 (LGE-LG-D855)

2016-01-18T13:57:18.541Z - debug: Socket disconnected: transport close 8 (motorola-XT1072)

2016-01-18T13:57:18.548Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:9

2016-01-18T13:57:18.549Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-18T13:57:18.562Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:10

2016-01-18T13:57:18.565Z - info: Discarding surplus device: LGE-LG-H815

2016-01-18T13:57:18.806Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:11

2016-01-18T13:57:18.807Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-18T13:57:18.833Z - info: Running on ios test: basic

2016-01-18T13:57:18.899Z - info: Running on android test: another

2016-01-18T13:57:19.005Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:12

2016-01-18T13:57:19.006Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-18T13:57:19.019Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:13

2016-01-18T13:57:19.020Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-18T13:57:19.237Z - debug: Socket disconnected: transport close 9 (samsung-SM-A300FU)

2016-01-18T13:57:19.394Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:14

2016-01-18T13:57:19.395Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-18T13:57:19.400Z - debug: Socket disconnected: transport close 10 (LGE-LG-H815)

2016-01-18T13:57:19.415Z - debug: Socket disconnected: transport close 11 (samsung-SM-A500FU)

2016-01-18T13:57:19.544Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:15

2016-01-18T13:57:19.545Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-18T13:57:19.919Z - debug: Socket disconnected: transport close 12 (HTC-HTC Desire 820)

2016-01-18T13:57:19.981Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:16

2016-01-18T13:57:19.982Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-18T13:57:20.358Z - debug: Socket disconnected: transport close 15 (samsung-SM-N910C)

2016-01-18T13:57:20.478Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-18T13:57:20.544Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:17

2016-01-18T13:57:20.545Z - info: Discarding surplus device: LGE-LG-D722

2016-01-18T13:57:20.689Z - debug: Device presented: LGE-LG-D802 (android) unittest socket:18

2016-01-18T13:57:20.690Z - info: Discarding surplus device: LGE-LG-D802

2016-01-18T13:57:20.742Z - debug: Socket disconnected: transport close 14 (samsung-SM-G900F)

2016-01-18T13:57:20.747Z - debug: Socket disconnected: transport close 16 (samsung-SM-A300FU)

2016-01-18T13:57:21.082Z - info: Running on ios test: another

2016-01-18T13:57:21.099Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:19

2016-01-18T13:57:21.100Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-01-18T13:57:21.660Z - debug: Socket disconnected: transport close 18 (LGE-LG-D802)

2016-01-18T13:57:22.045Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-18T13:57:22.058Z - debug: Socket disconnected: transport close 13 (Apple-Iphone5-1)

2016-01-18T13:57:22.320Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-18T13:57:22.381Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:20

2016-01-18T13:57:22.382Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-18T13:57:23.387Z - debug: Socket disconnected: transport close 20 (samsung-SM-G900F)

2016-01-18T13:57:23.754Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-18T13:57:23.991Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-18T13:57:24.001Z - debug: Socket disconnected: transport close 19 (Apple-Iphone5s-1)

2016-01-18T13:57:24.053Z - debug: Socket disconnected: transport close 17 (LGE-LG-D722)

2016-01-18T13:57:25.577Z - info: Running on android test: failed to get mobile documents path

2016-01-18T13:57:25.768Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-18T13:57:27.580Z - info: Running on ios test: failed to get mobile documents path

2016-01-18T13:57:27.910Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-18T13:57:29.056Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-18T13:57:30.472Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:21

2016-01-18T13:57:30.474Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-18T13:57:30.514Z - info: Running on android test: #init should register the networkChanged event

2016-01-18T13:57:31.140Z - info: Running on ios test: #init should register the networkChanged event

2016-01-18T13:57:31.871Z - debug: Socket disconnected: transport close 21 (samsung-SM-G800F)

2016-01-18T13:57:32.604Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-18T13:57:33.048Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-18T13:57:34.343Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-18T13:57:34.713Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-18T13:57:35.663Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-18T13:57:37.166Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-18T13:57:37.469Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-18T13:57:39.049Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-18T13:57:39.413Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-18T13:57:40.194Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-18T13:57:40.665Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-18T13:57:41.284Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-18T13:57:42.646Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-18T13:57:43.058Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-18T13:57:43.749Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-18T13:57:44.139Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-18T13:57:45.325Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-18T13:57:45.380Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-18T13:57:46.556Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-18T13:57:46.900Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-18T13:57:47.772Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-18T13:57:48.035Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-18T13:57:48.996Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-18T13:57:49.260Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-18T13:57:50.284Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-18T13:57:50.302Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-18T13:57:51.436Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-18T13:57:52.203Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-18T13:57:52.729Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-18T13:57:53.504Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-18T13:57:55.208Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-18T13:57:56.307Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-18T13:57:58.453Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-18T13:57:58.915Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-18T13:58:00.136Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-18T13:58:00.264Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-18T13:58:02.497Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-18T13:58:03.410Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-18T13:58:03.757Z - info: Running on android test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-18T13:58:04.974Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-18T13:58:06.186Z - info: Test run on android complete

2016-01-18T13:58:06.188Z - info: 

-== UNIT TEST RESULTS ==-
2016-01-18T13:58:06.189Z - info: PLATFORM: android

2016-01-18T13:58:06.199Z - info: RESULT: PASS

2016-01-18T13:58:06.200Z - info: 30 of 30 tests completed

2016-01-18T13:58:06.201Z - info: 30/30 passed (0 failures)
2016-01-18T13:58:06.201Z - info: --- Test Details ---



2016-01-18T13:58:06.202Z - info: multiplex can send data - pass
2016-01-18T13:58:06.203Z - info: basic - pass

2016-01-18T13:58:06.204Z - info: another - pass

2016-01-18T13:58:06.206Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-18T13:58:06.210Z - info: successfully read a previous pkcs12 file and return hash value - pass
2016-01-18T13:58:06.211Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-18T13:58:06.211Z - info: failed to get mobile documents path - pass
2016-01-18T13:58:06.212Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-18T13:58:06.213Z - info: #init should register the networkChanged event - pass
2016-01-18T13:58:06.213Z - info: #startBroadcasting should throw on null device name - pass

2016-01-18T13:58:06.214Z - info: #startBroadcasting should throw on empty string device name - pass
2016-01-18T13:58:06.215Z - info: #startBroadcasting should throw on non-number port - pass
2016-01-18T13:58:06.215Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-18T13:58:06.216Z - info: #startBroadcasting should throw on negative port - pass
2016-01-18T13:58:06.216Z - info: #startBroadcasting should throw on too large port - pass
2016-01-18T13:58:06.217Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-18T13:58:06.217Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-18T13:58:06.218Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-18T13:58:06.219Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-18T13:58:06.219Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-01-18T13:58:06.220Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-18T13:58:06.221Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-18T13:58:06.222Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-18T13:58:06.222Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
2016-01-18T13:58:06.223Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-18T13:58:06.224Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-18T13:58:06.224Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-18T13:58:06.225Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-18T13:58:06.226Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass
2016-01-18T13:58:06.226Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-18T13:58:06.227Z - info: 

-== END ==-

2016-01-18T13:58:07.855Z - debug: Device presented: motorola-XT1039 (android) unittest socket:22

2016-01-18T13:58:07.856Z - info: Discarding surplus device: motorola-XT1039

2016-01-18T13:58:08.602Z - debug: Socket disconnected: transport close 22 (motorola-XT1039)

2016-01-18T13:58:23.971Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-18T13:58:49.414Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-18T13:59:18.893Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-18T13:59:31.190Z - debug: Socket disconnected: ping timeout 0 (HTC-HTC One M8s)

2016-01-18T13:59:31.201Z - debug: Socket disconnected: ping timeout 1 (LGE-Nexus 5)

2016-01-18T14:00:48.083Z - debug: Socket disconnected: ping timeout 6 (Apple-Iphone6-1)

2016-01-18T14:09:46.192Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)


 
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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true

```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_server.md)




###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on HT574YC04723 
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56151093f6e24ff_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_LGE-Nexus 5.md)



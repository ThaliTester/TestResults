#### Test 56151093914d164 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-17T15:06:26.952Z - info: listening on *:3000

2016-01-17T15:06:27.391Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:0

2016-01-17T15:06:27.414Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-01-17T15:06:28.452Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:2

2016-01-17T15:06:28.455Z - info: Required number of android devices presented (2)

2016-01-17T15:06:28.458Z - info: Starting unit test run for platform: android

2016-01-17T15:06:28.542Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-01-17T15:06:28.544Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-17T15:06:28.714Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:4

2016-01-17T15:06:28.715Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-17T15:06:28.815Z - info: Running on android test: multiplex can send data

2016-01-17T15:06:29.227Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:5

2016-01-17T15:06:29.228Z - info: Discarding surplus device: HTC-HTC One M8s

2016-01-17T15:06:29.246Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:6

2016-01-17T15:06:29.247Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-17T15:06:29.294Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C)

2016-01-17T15:06:29.325Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-01-17T15:06:29.326Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-17T15:06:29.354Z - debug: Socket disconnected: transport close 4 (samsung-SM-A300FU)

stage: start_test platform: android test: multiplex can send data toComplete: 2

2016-01-17T15:06:29.934Z - debug: Socket disconnected: transport close 6 (samsung-SM-A300FU)

2016-01-17T15:06:29.963Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:8

2016-01-17T15:06:29.964Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-17T15:06:30.054Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:9

2016-01-17T15:06:30.055Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-17T15:06:30.221Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-01-17T15:06:30.231Z - debug: Socket disconnected: transport close 5 (HTC-HTC One M8s)

2016-01-17T15:06:30.569Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:10

2016-01-17T15:06:30.573Z - info: Required number of ios devices presented (2)

2016-01-17T15:06:30.574Z - info: Starting unit test run for platform: ios

2016-01-17T15:06:30.662Z - debug: Socket disconnected: transport close 9 (samsung-SM-A500FU)

2016-01-17T15:06:30.784Z - info: Running on ios test: multiplex can send data

stage: start_test platform: ios test: multiplex can send data toComplete: 2

stage: start_test platform: ios test: multiplex can send data toComplete: 1

stage: teardown platform: ios test: multiplex can send data toComplete: 2

2016-01-17T15:06:30.868Z - debug: Socket disconnected: transport close 8 (HTC-HTC Desire 820)

stage: teardown platform: ios test: multiplex can send data toComplete: 1

2016-01-17T15:06:30.925Z - info: Running on ios test: basic

stage: start_test platform: ios test: basic toComplete: 2

stage: start_test platform: ios test: basic toComplete: 1

2016-01-17T15:06:30.958Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:11

2016-01-17T15:06:30.959Z - info: Discarding surplus device: LGE-LG-H815

stage: teardown platform: ios test: basic toComplete: 2

stage: teardown platform: ios test: basic toComplete: 1

2016-01-17T15:06:31.001Z - info: Running on ios test: another

stage: start_test platform: ios test: another toComplete: 2

stage: start_test platform: ios test: another toComplete: 1

stage: teardown platform: ios test: another toComplete: 2

2016-01-17T15:06:31.047Z - debug: Device presented: LGE-LG-D802 (android) unittest socket:12

2016-01-17T15:06:31.048Z - info: Discarding surplus device: LGE-LG-D802

stage: teardown platform: ios test: another toComplete: 1

2016-01-17T15:06:31.082Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

stage: start_test platform: ios test: successfully create a new pkcs12 file and return hash value toComplete: 2

stage: start_test platform: ios test: successfully create a new pkcs12 file and return hash value toComplete: 1

stage: teardown platform: ios test: successfully create a new pkcs12 file and return hash value toComplete: 2

stage: teardown platform: ios test: successfully create a new pkcs12 file and return hash value toComplete: 1

2016-01-17T15:06:31.302Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

stage: start_test platform: ios test: successfully read a previous pkcs12 file and return hash value toComplete: 2

stage: start_test platform: ios test: successfully read a previous pkcs12 file and return hash value toComplete: 1

stage: teardown platform: ios test: successfully read a previous pkcs12 file and return hash value toComplete: 2

stage: teardown platform: ios test: successfully read a previous pkcs12 file and return hash value toComplete: 1

2016-01-17T15:06:31.474Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:13

2016-01-17T15:06:31.475Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-17T15:06:31.479Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-17T15:06:31.492Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:14

2016-01-17T15:06:31.495Z - info: Discarding surplus device: LGE-Nexus 5

stage: start_test platform: ios test: failed to extract public key because of corrupt pkcs12 file toComplete: 2

stage: start_test platform: ios test: failed to extract public key because of corrupt pkcs12 file toComplete: 1

2016-01-17T15:06:31.554Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:15

2016-01-17T15:06:31.555Z - info: Discarding surplus device: samsung-SM-A500FU

stage: teardown platform: ios test: failed to extract public key because of corrupt pkcs12 file toComplete: 2

stage: teardown platform: ios test: failed to extract public key because of corrupt pkcs12 file toComplete: 1

2016-01-17T15:06:31.601Z - info: Running on ios test: failed to get mobile documents path

stage: start_test platform: ios test: failed to get mobile documents path toComplete: 2

stage: start_test platform: ios test: failed to get mobile documents path toComplete: 1

stage: teardown platform: ios test: failed to get mobile documents path toComplete: 2

stage: teardown platform: ios test: failed to get mobile documents path toComplete: 1

2016-01-17T15:06:31.649Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:16

2016-01-17T15:06:31.650Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-17T15:06:31.656Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

stage: start_test platform: ios test: #init should register the peerAvailabilityChanged event toComplete: 2

stage: start_test platform: ios test: #init should register the peerAvailabilityChanged event toComplete: 1

stage: teardown platform: ios test: #init should register the peerAvailabilityChanged event toComplete: 2

stage: teardown platform: ios test: #init should register the peerAvailabilityChanged event toComplete: 1

2016-01-17T15:06:31.702Z - info: Running on ios test: #init should register the networkChanged event

stage: start_test platform: ios test: #init should register the networkChanged event toComplete: 2

stage: start_test platform: ios test: #init should register the networkChanged event toComplete: 1

stage: teardown platform: ios test: #init should register the networkChanged event toComplete: 2

stage: teardown platform: ios test: #init should register the networkChanged event toComplete: 1

2016-01-17T15:06:31.778Z - debug: Socket disconnected: transport close 11 (LGE-LG-H815)

2016-01-17T15:06:31.785Z - info: Running on ios test: #startBroadcasting should throw on null device name

stage: start_test platform: ios test: #startBroadcasting should throw on null device name toComplete: 2

stage: start_test platform: ios test: #startBroadcasting should throw on null device name toComplete: 1

stage: teardown platform: ios test: #startBroadcasting should throw on null device name toComplete: 2

stage: teardown platform: ios test: #startBroadcasting should throw on null device name toComplete: 1

2016-01-17T15:06:31.841Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-17T15:06:31.849Z - debug: Socket disconnected: transport close 12 (LGE-LG-D802)

stage: start_test platform: ios test: #startBroadcasting should throw on empty string device name toComplete: 2

stage: start_test platform: ios test: #startBroadcasting should throw on empty string device name toComplete: 1

2016-01-17T15:06:31.871Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:17

2016-01-17T15:06:31.872Z - info: Discarding surplus device: HTC-HTC Desire 820

stage: teardown platform: ios test: #startBroadcasting should throw on empty string device name toComplete: 2

stage: teardown platform: ios test: #startBroadcasting should throw on empty string device name toComplete: 1

2016-01-17T15:06:31.904Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:18

2016-01-17T15:06:31.905Z - info: Discarding surplus device: LGE-LG-D722

2016-01-17T15:06:31.932Z - info: Running on ios test: #startBroadcasting should throw on non-number port

stage: start_test platform: ios test: #startBroadcasting should throw on non-number port toComplete: 2

stage: start_test platform: ios test: #startBroadcasting should throw on non-number port toComplete: 1

2016-01-17T15:06:31.979Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:19

2016-01-17T15:06:31.980Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-17T15:06:31.985Z - debug: Socket disconnected: transport close 14 (LGE-Nexus 5)

stage: teardown platform: ios test: #startBroadcasting should throw on non-number port toComplete: 2

stage: teardown platform: ios test: #startBroadcasting should throw on non-number port toComplete: 1

2016-01-17T15:06:32.006Z - info: Running on ios test: #startBroadcasting should throw on NaN port

stage: start_test platform: ios test: #startBroadcasting should throw on NaN port toComplete: 2

stage: start_test platform: ios test: #startBroadcasting should throw on NaN port toComplete: 1

2016-01-17T15:06:32.032Z - debug: Device presented: motorola-XT1072 (android) unittest socket:20

2016-01-17T15:06:32.033Z - info: Discarding surplus device: motorola-XT1072

stage: teardown platform: ios test: #startBroadcasting should throw on NaN port toComplete: 2
stage: teardown platform: ios test: #startBroadcasting should throw on NaN port toComplete: 1

2016-01-17T15:06:32.064Z - info: Running on ios test: #startBroadcasting should throw on negative port

stage: start_test platform: ios test: #startBroadcasting should throw on negative port toComplete: 2

stage: start_test platform: ios test: #startBroadcasting should throw on negative port toComplete: 1

stage: teardown platform: ios test: #startBroadcasting should throw on negative port toComplete: 2

stage: teardown platform: ios test: #startBroadcasting should throw on negative port toComplete: 1

2016-01-17T15:06:32.117Z - info: Running on ios test: #startBroadcasting should throw on too large port

stage: start_test platform: ios test: #startBroadcasting should throw on too large port toComplete: 2

2016-01-17T15:06:32.140Z - debug: Socket disconnected: transport close 15 (samsung-SM-A500FU)

stage: start_test platform: ios test: #startBroadcasting should throw on too large port toComplete: 1

stage: teardown platform: ios test: #startBroadcasting should throw on too large port toComplete: 2

stage: teardown platform: ios test: #startBroadcasting should throw on too large port toComplete: 1

2016-01-17T15:06:32.213Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

stage: start_test platform: ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error toComplete: 2

stage: start_test platform: ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error toComplete: 1

stage: teardown platform: ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error toComplete: 2

stage: teardown platform: ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error toComplete: 1

2016-01-17T15:06:32.273Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

stage: start_test platform: ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error toComplete: 2

stage: start_test platform: ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error toComplete: 1

stage: teardown platform: ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error toComplete: 2

stage: teardown platform: ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error toComplete: 1

2016-01-17T15:06:32.348Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

stage: start_test platform: ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error toComplete: 2

stage: start_test platform: ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error toComplete: 1

stage: teardown platform: ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error toComplete: 2

stage: teardown platform: ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error toComplete: 1

2016-01-17T15:06:32.426Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

stage: start_test platform: ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error toComplete: 2

stage: start_test platform: ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error toComplete: 1

stage: teardown platform: ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error toComplete: 2

2016-01-17T15:06:32.472Z - debug: Socket disconnected: transport close 13 (samsung-SM-G900F)

stage: teardown platform: ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error toComplete: 1

2016-01-17T15:06:32.494Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

stage: start_test platform: ios test: #connect should call Mobile("Connect") with a port and without an error toComplete: 2

stage: start_test platform: ios test: #connect should call Mobile("Connect") with a port and without an error toComplete: 1

stage: teardown platform: ios test: #connect should call Mobile("Connect") with a port and without an error toComplete: 2

stage: teardown platform: ios test: #connect should call Mobile("Connect") with a port and without an error toComplete: 1

2016-01-17T15:06:32.536Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

stage: start_test platform: ios test: #connect should call Mobile("Connect") and handle an error toComplete: 2

stage: start_test platform: ios test: #connect should call Mobile("Connect") and handle an error toComplete: 1

stage: teardown platform: ios test: #connect should call Mobile("Connect") and handle an error toComplete: 2

stage: teardown platform: ios test: #connect should call Mobile("Connect") and handle an error toComplete: 1

2016-01-17T15:06:32.606Z - info: Running on ios test: should call Mobile("Disconnect") without an error

stage: start_test platform: ios test: should call Mobile("Disconnect") without an error toComplete: 2

stage: start_test platform: ios test: should call Mobile("Disconnect") without an error toComplete: 1

stage: teardown platform: ios test: should call Mobile("Disconnect") without an error toComplete: 2

stage: teardown platform: ios test: should call Mobile("Disconnect") without an error toComplete: 1

2016-01-17T15:06:32.665Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

stage: start_test platform: ios test: should call Mobile("Disconnect") and handle an error toComplete: 2

stage: start_test platform: ios test: should call Mobile("Disconnect") and handle an error toComplete: 1

stage: teardown platform: ios test: should call Mobile("Disconnect") and handle an error toComplete: 2

stage: teardown platform: ios test: should call Mobile("Disconnect") and handle an error toComplete: 1

2016-01-17T15:06:32.714Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

stage: start_test platform: ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error toComplete: 2

stage: start_test platform: ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error toComplete: 1

2016-01-17T15:06:32.831Z - debug: Socket disconnected: transport close 20 (motorola-XT1072)

2016-01-17T15:06:32.875Z - debug: Socket disconnected: transport close 17 (HTC-HTC Desire 820)

stage: teardown platform: ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error toComplete: 2

stage: teardown platform: ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error toComplete: 1

2016-01-17T15:06:33.017Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

stage: start_test platform: ios test: ThaliEmitter calls startBroadcasting twice with error toComplete: 2

stage: start_test platform: ios test: ThaliEmitter calls startBroadcasting twice with error toComplete: 1

stage: teardown platform: ios test: ThaliEmitter calls startBroadcasting twice with error toComplete: 2

stage: teardown platform: ios test: ThaliEmitter calls startBroadcasting twice with error toComplete: 1

2016-01-17T15:06:33.097Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-17T15:06:33.106Z - debug: Device presented: motorola-XT1039 (android) unittest socket:21

2016-01-17T15:06:33.107Z - info: Discarding surplus device: motorola-XT1039

stage: start_test platform: ios test: ThaliEmitter throws on connection to bad peer toComplete: 2

stage: start_test platform: ios test: ThaliEmitter throws on connection to bad peer toComplete: 1

2016-01-17T15:06:33.123Z - debug: Socket disconnected: transport close 18 (LGE-LG-D722)

stage: teardown platform: ios test: ThaliEmitter throws on connection to bad peer toComplete: 2

stage: teardown platform: ios test: ThaliEmitter throws on connection to bad peer toComplete: 1

2016-01-17T15:06:33.175Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

stage: start_test platform: ios test: ThaliEmitter throws on disconnect to bad peer toComplete: 2

stage: start_test platform: ios test: ThaliEmitter throws on disconnect to bad peer toComplete: 1

stage: teardown platform: ios test: ThaliEmitter throws on disconnect to bad peer toComplete: 2

stage: teardown platform: ios test: ThaliEmitter throws on disconnect to bad peer toComplete: 1

2016-01-17T15:06:33.516Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

stage: start_test platform: ios test: ThaliEmitter can discover and connect to peers toComplete: 2

stage: start_test platform: ios test: ThaliEmitter can discover and connect to peers toComplete: 1

2016-01-17T15:06:33.828Z - debug: Socket disconnected: transport close 21 (motorola-XT1039)

2016-01-17T15:06:34.180Z - debug: Socket disconnected: transport close 16 (Apple-Iphone6-1)

2016-01-17T15:06:35.107Z - debug: Socket disconnected: transport close 19 (Apple-Iphone5-1)

2016-01-17T15:06:38.039Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:22

2016-01-17T15:06:38.042Z - info: Discarding surplus device: samsung-SM-G800F

stage: teardown platform: ios test: ThaliEmitter can discover and connect to peers toComplete: 2

2016-01-17T15:06:39.232Z - debug: Socket disconnected: transport close 22 (samsung-SM-G800F)

stage: teardown platform: ios test: ThaliEmitter can discover and connect to peers toComplete: 1

2016-01-17T15:06:40.554Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

stage: start_test platform: ios test: ThaliEmitter can discover and connect to peers and then fail on double connect toComplete: 2

stage: start_test platform: ios test: ThaliEmitter can discover and connect to peers and then fail on double connect toComplete: 1

stage: teardown platform: ios test: ThaliEmitter can discover and connect to peers and then fail on double connect toComplete: 2

stage: teardown platform: ios test: ThaliEmitter can discover and connect to peers and then fail on double connect toComplete: 1

2016-01-17T15:06:46.331Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

stage: start_test platform: ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect toComplete: 2

stage: start_test platform: ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect toComplete: 1

stage: teardown platform: ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect toComplete: 2

stage: teardown platform: ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect toComplete: 1

2016-01-17T15:06:54.177Z - info: Running on ios test: ThaliEmitter can connect and send data

stage: start_test platform: ios test: ThaliEmitter can connect and send data toComplete: 2

stage: start_test platform: ios test: ThaliEmitter can connect and send data toComplete: 1

stage: teardown platform: ios test: ThaliEmitter can connect and send data toComplete: 2

stage: teardown platform: ios test: ThaliEmitter can connect and send data toComplete: 1

2016-01-17T15:07:04.002Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

stage: start_test platform: ios test: ThaliEmitter handles socket disconnect correctly toComplete: 2

stage: start_test platform: ios test: ThaliEmitter handles socket disconnect correctly toComplete: 1

stage: teardown platform: ios test: ThaliEmitter handles socket disconnect correctly toComplete: 2

stage: teardown platform: ios test: ThaliEmitter handles socket disconnect correctly toComplete: 1

2016-01-17T15:07:16.616Z - info: Running on ios test: ThaliReplicationManager can call start without error

stage: start_test platform: ios test: ThaliReplicationManager can call start without error toComplete: 2

stage: start_test platform: ios test: ThaliReplicationManager can call start without error toComplete: 1

stage: teardown platform: ios test: ThaliReplicationManager can call start without error toComplete: 2

stage: teardown platform: ios test: ThaliReplicationManager can call start without error toComplete: 1

2016-01-17T15:07:16.983Z - info: Running on ios test: ThaliReplicationManager receives identity

stage: start_test platform: ios test: ThaliReplicationManager receives identity toComplete: 2

stage: start_test platform: ios test: ThaliReplicationManager receives identity toComplete: 1

stage: teardown platform: ios test: ThaliReplicationManager receives identity toComplete: 2

stage: teardown platform: ios test: ThaliReplicationManager receives identity toComplete: 1

2016-01-17T15:07:17.133Z - info: Running on ios test: ThaliReplicationManager replicates database

stage: start_test platform: ios test: ThaliReplicationManager replicates database toComplete: 2

stage: start_test platform: ios test: ThaliReplicationManager replicates database toComplete: 1

stage: teardown platform: ios test: ThaliReplicationManager replicates database toComplete: 2

stage: teardown platform: ios test: ThaliReplicationManager replicates database toComplete: 1

2016-01-17T15:07:48.686Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

stage: start_test platform: ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available toComplete: 2

stage: start_test platform: ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available toComplete: 1

stage: teardown platform: ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available toComplete: 2

2016-01-17T15:07:52.067Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-01-17T15:18:47.564Z - debug: Socket disconnected: transport close 10 (Apple-Iphone5s-1)

2016-01-17T15:22:34.577Z - debug: Socket disconnected: transport close 2 (LGE-Nexus 5)

2016-01-17T15:26:35.765Z - debug: Socket disconnected: transport close 0 (LGE-LG-D855)


 
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
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Device test finished on 022678fb504e29b0 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on HT574YC04723 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56151093914d164_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_LGE-Nexus 5.md)





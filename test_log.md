#### Test 5635717154d1b6f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-18T15:59:09.041Z - info: listening on *:3000

2016-01-18T15:59:09.590Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:0

2016-01-18T15:59:09.658Z - debug: Device presented: LGE-LG-D802 (android) unittest socket:1

2016-01-18T15:59:09.662Z - info: Required number of android devices presented (2)

2016-01-18T15:59:09.665Z - info: Starting unit test run for platform: android

2016-01-18T15:59:09.968Z - info: Running on android test: multiplex can send data

2016-01-18T15:59:10.043Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:2

2016-01-18T15:59:10.046Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-18T15:59:10.163Z - info: Running on android test: basic

2016-01-18T15:59:10.209Z - info: Running on android test: another

2016-01-18T15:59:10.229Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:3

2016-01-18T15:59:10.364Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-18T15:59:10.554Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-18T15:59:10.581Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:4

2016-01-18T15:59:10.582Z - info: Discarding surplus device: HTC-HTC One M8s

2016-01-18T15:59:10.707Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:5

2016-01-18T15:59:10.708Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-18T15:59:10.719Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:6

2016-01-18T15:59:10.720Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-18T15:59:10.748Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:7

2016-01-18T15:59:10.749Z - info: Discarding surplus device: LGE-LG-D855

2016-01-18T15:59:10.765Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-18T15:59:10.873Z - info: Running on android test: failed to get mobile documents path

2016-01-18T15:59:10.892Z - debug: Device presented: motorola-XT1072 (android) unittest socket:8

2016-01-18T15:59:10.893Z - info: Discarding surplus device: motorola-XT1072

2016-01-18T15:59:10.977Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-18T15:59:11.002Z - debug: Socket disconnected: transport close 2 (HTC-HTC Desire 820)

2016-01-18T15:59:11.034Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:10

2016-01-18T15:59:11.036Z - info: Required number of ios devices presented (2)

2016-01-18T15:59:11.040Z - info: Starting unit test run for platform: ios

2016-01-18T15:59:11.051Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-01-18T15:59:11.052Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-18T15:59:11.074Z - info: Running on android test: #init should register the networkChanged event

2016-01-18T15:59:11.181Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-18T15:59:11.226Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-18T15:59:11.236Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:11

2016-01-18T15:59:11.237Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-18T15:59:11.285Z - debug: Socket disconnected: transport close 4 (HTC-HTC One M8s)

2016-01-18T15:59:11.295Z - debug: Socket disconnected: transport close 5 (samsung-SM-A300FU)

2016-01-18T15:59:11.319Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-18T15:59:11.372Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-18T15:59:11.391Z - debug: Socket disconnected: transport close 6 (samsung-SM-A300FU)

2016-01-18T15:59:11.459Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-18T15:59:11.538Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-18T15:59:11.552Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:12

2016-01-18T15:59:11.553Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-18T15:59:11.563Z - debug: Socket disconnected: transport close 8 (motorola-XT1072)

2016-01-18T15:59:11.623Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-18T15:59:11.708Z - debug: Socket disconnected: transport close 7 (LGE-LG-D855)

2016-01-18T15:59:11.713Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-18T15:59:11.744Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:13

2016-01-18T15:59:11.745Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-01-18T15:59:11.776Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-18T15:59:11.852Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-18T15:59:11.905Z - debug: Socket disconnected: transport close 11 (samsung-SM-A500FU)

2016-01-18T15:59:11.910Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-01-18T15:59:11.918Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-18T15:59:12.019Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-18T15:59:12.079Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-18T15:59:12.136Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-18T15:59:12.184Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-18T15:59:12.584Z - debug: Socket disconnected: transport close 12 (HTC-HTC Desire 820)

2016-01-18T15:59:12.636Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:14

2016-01-18T15:59:12.639Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-18T15:59:12.935Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:15

2016-01-18T15:59:12.936Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-18T15:59:13.075Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:16

2016-01-18T15:59:13.077Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-18T15:59:13.149Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:17

2016-01-18T15:59:13.150Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-18T15:59:13.185Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:18

2016-01-18T15:59:13.186Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-18T15:59:13.355Z - info: Running on ios test: multiplex can send data

2016-01-18T15:59:13.549Z - debug: Socket disconnected: transport close 16 (LGE-Nexus 5)

2016-01-18T15:59:13.616Z - debug: Socket disconnected: transport close 18 (LGE-Nexus 5)

2016-01-18T15:59:13.629Z - debug: Socket disconnected: transport close 14 (samsung-SM-G900F)

2016-01-18T15:59:13.634Z - debug: Socket disconnected: transport close 15 (samsung-SM-A500FU)

2016-01-18T15:59:13.706Z - info: Running on ios test: basic

2016-01-18T15:59:13.883Z - info: Running on ios test: another

2016-01-18T15:59:14.076Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-18T15:59:14.112Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:19

2016-01-18T15:59:14.113Z - info: Discarding surplus device: LGE-LG-H815

2016-01-18T15:59:14.280Z - debug: Socket disconnected: transport close 13 (Apple-Iphone5s-1)

2016-01-18T15:59:14.336Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:20

2016-01-18T15:59:14.337Z - info: Discarding surplus device: LGE-LG-D722

2016-01-18T15:59:14.822Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-18T15:59:15.162Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-18T15:59:15.246Z - debug: Socket disconnected: transport close 19 (LGE-LG-H815)

2016-01-18T15:59:15.345Z - info: Running on ios test: failed to get mobile documents path

2016-01-18T15:59:15.484Z - debug: Socket disconnected: transport close 20 (LGE-LG-D722)

2016-01-18T15:59:16.039Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-18T15:59:16.175Z - debug: Socket disconnected: transport close 17 (Apple-Iphone5-1)

2016-01-18T15:59:16.822Z - info: Running on ios test: #init should register the networkChanged event

2016-01-18T15:59:17.704Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-18T15:59:18.077Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-18T15:59:18.225Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-18T15:59:18.266Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-18T15:59:18.343Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-18T15:59:18.426Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-18T15:59:18.554Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-18T15:59:18.739Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-18T15:59:18.902Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-18T15:59:19.086Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-18T15:59:19.242Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-18T15:59:19.611Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-18T15:59:19.829Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-18T15:59:19.957Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:21

2016-01-18T15:59:19.959Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-18T15:59:20.090Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-18T15:59:20.301Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-18T15:59:20.842Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-18T15:59:21.305Z - debug: Socket disconnected: transport close 21 (samsung-SM-G800F)

2016-01-18T15:59:21.319Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-18T15:59:21.403Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-18T15:59:21.756Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-18T15:59:26.747Z - debug: Device presented: motorola-XT1039 (android) unittest socket:22

2016-01-18T15:59:26.748Z - info: Discarding surplus device: motorola-XT1039

2016-01-18T15:59:27.496Z - debug: Socket disconnected: transport close 22 (motorola-XT1039)

2016-01-18T15:59:27.627Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-18T15:59:36.068Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-18T15:59:44.419Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-18T15:59:57.299Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-18T16:00:09.019Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-18T16:00:14.594Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-18T16:00:15.642Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-18T16:00:37.215Z - debug: Socket disconnected: ping timeout 1 (LGE-LG-D802)

2016-01-18T16:01:58.572Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-18T16:02:05.492Z - info: Running on ios test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-18T16:03:50.056Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone6-1)

2016-01-18T16:11:35.737Z - debug: Socket disconnected: transport close 10 (Apple-IpadAir2-1)

2016-01-18T16:17:02.909Z - debug: Socket disconnected: transport close 0 (samsung-SM-N910C)


 
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
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on HT574YC04723 
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5635717154d1b6f_Forward-integrate_from_story_001_vjrantal/thali09_LGE-Nexus 5.md)





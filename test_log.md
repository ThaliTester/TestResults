#### Test 5590220275263c8 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-13T14:36:32.447Z - info: listening on *:3000

2016-01-13T14:36:32.835Z - debug: Device presented: UNITTEST-0.001387778071169965 (ios) unittest socket:0

2016-01-13T14:36:32.916Z - debug: Device presented: UNITTEST-0.1458359637431711 (ios) unittest socket:1

2016-01-13T14:36:32.919Z - info: Required number of ios devices presented (2)

2016-01-13T14:36:32.923Z - info: Starting unit test run for platform: ios

2016-01-13T14:36:32.975Z - debug: Device presented: UNITTEST-0.6922477995724867 (android) unittest socket:2

2016-01-13T14:36:32.996Z - debug: Device presented: UNITTEST-0.371709923792337 (ios) unittest socket:3

2016-01-13T14:36:32.997Z - info: Discarding surplus device: UNITTEST-0.371709923792337

2016-01-13T14:36:33.103Z - info: Running test: multiplex can send data

2016-01-13T14:36:33.415Z - debug: Device presented: UNITTEST-0.9695572644479188 (android) unittest socket:5

2016-01-13T14:36:33.416Z - info: Required number of android devices presented (2)

2016-01-13T14:36:33.418Z - info: Starting unit test run for platform: android

2016-01-13T14:36:33.436Z - debug: Device presented: UNITTEST-0.7991668439108733 (android) unittest socket:4

2016-01-13T14:36:33.437Z - info: Discarding surplus device: UNITTEST-0.7991668439108733

2016-01-13T14:36:33.672Z - info: Running test: multiplex can send data

2016-01-13T14:36:34.127Z - debug: Device presented: UNITTEST-0.6470912122045528 (android) unittest socket:6

2016-01-13T14:36:34.130Z - info: Discarding surplus device: UNITTEST-0.6470912122045528

2016-01-13T14:36:34.293Z - debug: Device presented: UNITTEST-0.909009119211784 (ios) unittest socket:7

2016-01-13T14:36:34.296Z - info: Discarding surplus device: UNITTEST-0.909009119211784

2016-01-13T14:36:34.370Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.7991668439108733)

2016-01-13T14:36:34.640Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.6470912122045528)

2016-01-13T14:36:34.703Z - debug: Device presented: UNITTEST-0.398629514363654 (android) unittest socket:8

2016-01-13T14:36:34.706Z - info: Discarding surplus device: UNITTEST-0.398629514363654

2016-01-13T14:36:34.941Z - debug: Device presented: UNITTEST-0.8545692506006063 (android) unittest socket:9

2016-01-13T14:36:34.943Z - info: Discarding surplus device: UNITTEST-0.8545692506006063

2016-01-13T14:36:35.108Z - debug: Device presented: UNITTEST-0.8479388441053552 (android) unittest socket:10

2016-01-13T14:36:35.111Z - info: Discarding surplus device: UNITTEST-0.8479388441053552

2016-01-13T14:36:35.154Z - debug: Device presented: UNITTEST-0.23297684760232495 (android) unittest socket:11

2016-01-13T14:36:35.155Z - info: Discarding surplus device: UNITTEST-0.23297684760232495

2016-01-13T14:36:35.264Z - debug: Device presented: UNITTEST-0.5474624030119383 (android) unittest socket:12

2016-01-13T14:36:35.269Z - info: Discarding surplus device: UNITTEST-0.5474624030119383

2016-01-13T14:36:35.300Z - info: Running test: basic

2016-01-13T14:36:35.484Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.398629514363654)

2016-01-13T14:36:35.531Z - debug: Device presented: UNITTEST-0.7481528393605053 (android) unittest socket:13

2016-01-13T14:36:35.534Z - info: Discarding surplus device: UNITTEST-0.7481528393605053

2016-01-13T14:36:35.737Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.23297684760232495)

2016-01-13T14:36:35.770Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.8545692506006063)

2016-01-13T14:36:35.784Z - debug: Device presented: UNITTEST-0.342351819326278 (android) unittest socket:14

2016-01-13T14:36:35.787Z - info: Discarding surplus device: UNITTEST-0.342351819326278

2016-01-13T14:36:35.811Z - info: Running test: basic

2016-01-13T14:36:35.881Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.5474624030119383)

2016-01-13T14:36:35.907Z - debug: Device presented: UNITTEST-0.499337572086329 (android) unittest socket:15

2016-01-13T14:36:35.910Z - info: Discarding surplus device: UNITTEST-0.499337572086329

2016-01-13T14:36:36.094Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.8479388441053552)

2016-01-13T14:36:36.124Z - debug: Device presented: UNITTEST-0.036721579109221136 (android) unittest socket:16

2016-01-13T14:36:36.125Z - info: Discarding surplus device: UNITTEST-0.036721579109221136

2016-01-13T14:36:36.271Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.371709923792337)

2016-01-13T14:36:36.355Z - debug: Device presented: UNITTEST-0.21611781276084063 (android) unittest socket:17

2016-01-13T14:36:36.358Z - info: Discarding surplus device: UNITTEST-0.21611781276084063

2016-01-13T14:36:36.424Z - info: Running test: another

2016-01-13T14:36:36.448Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.7481528393605053)

2016-01-13T14:36:36.556Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.036721579109221136)

2016-01-13T14:36:36.562Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.342351819326278)

2016-01-13T14:36:36.841Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.499337572086329)

2016-01-13T14:36:36.851Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.909009119211784)

2016-01-13T14:36:36.883Z - debug: Device presented: UNITTEST-0.8457609928153136 (android) unittest socket:18

2016-01-13T14:36:36.885Z - info: Discarding surplus device: UNITTEST-0.8457609928153136

2016-01-13T14:36:37.406Z - debug: Device presented: UNITTEST-0.9816626522173088 (android) unittest socket:19

2016-01-13T14:36:37.407Z - info: Discarding surplus device: UNITTEST-0.9816626522173088

2016-01-13T14:36:37.452Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.21611781276084063)

2016-01-13T14:36:37.519Z - debug: Device presented: UNITTEST-0.4267307457080659 (android) unittest socket:20

2016-01-13T14:36:37.521Z - info: Discarding surplus device: UNITTEST-0.4267307457080659

2016-01-13T14:36:37.663Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-13T14:36:37.679Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.8457609928153136)

2016-01-13T14:36:38.166Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.4267307457080659)

2016-01-13T14:36:38.475Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.9816626522173088)

2016-01-13T14:36:38.776Z - info: Running test: another

2016-01-13T14:36:39.822Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-13T14:36:41.055Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-13T14:36:41.632Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-13T14:36:42.158Z - info: Running test: failed to get mobile documents path

2016-01-13T14:36:43.375Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-13T14:36:44.616Z - info: Running test: #init should register the networkChanged event

2016-01-13T14:36:44.862Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-13T14:36:45.847Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-13T14:36:46.026Z - debug: Device presented: UNITTEST-0.9936712213243509 (android) unittest socket:21

2016-01-13T14:36:46.027Z - info: Discarding surplus device: UNITTEST-0.9936712213243509

2016-01-13T14:36:46.835Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.9936712213243509)

2016-01-13T14:36:47.073Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-13T14:36:48.171Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-13T14:36:48.911Z - debug: Device presented: UNITTEST-0.7893307593733302 (android) unittest socket:22

2016-01-13T14:36:48.912Z - info: Discarding surplus device: UNITTEST-0.7893307593733302

2016-01-13T14:36:50.011Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.7893307593733302)

2016-01-13T14:36:50.310Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-13T14:36:50.726Z - info: Running test: failed to get mobile documents path

2016-01-13T14:36:51.586Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-13T14:36:53.727Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-13T14:36:53.988Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-13T14:36:55.675Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-13T14:36:56.781Z - info: Running test: #init should register the networkChanged event

2016-01-13T14:36:56.918Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-13T14:36:57.886Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-13T14:36:58.112Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-13T14:36:59.746Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-13T14:37:00.671Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-13T14:37:00.979Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-13T14:37:02.207Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-13T14:37:03.458Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-13T14:37:03.744Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-13T14:37:04.657Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-13T14:37:05.897Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-13T14:37:06.794Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-13T14:37:07.113Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-13T14:37:09.669Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-13T14:37:11.226Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-13T14:37:12.755Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-13T14:37:14.706Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-13T14:37:15.629Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-13T14:37:17.692Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-13T14:37:18.514Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-13T14:37:20.437Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-13T14:37:22.907Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-13T14:37:25.861Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-13T14:37:28.527Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-13T14:37:31.595Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-13T14:37:34.838Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-13T14:37:37.932Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-13T14:37:39.613Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-13T14:37:40.591Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-13T14:37:44.381Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-13T14:37:47.995Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-13T14:37:49.509Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-13T14:37:51.156Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-13T14:37:58.062Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-13T14:38:06.348Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-13T14:38:13.246Z - info: Running test: ThaliEmitter can connect and send data

2016-01-13T14:38:20.586Z - info: Running test: ThaliEmitter handles socket disconnect correctly

2016-01-13T14:38:24.101Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.001387778071169965)

2016-01-13T14:38:24.258Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.1458359637431711)

2016-01-13T15:03:00.443Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.9695572644479188)

2016-01-13T15:03:05.772Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.6922477995724867)


 
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
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/iOS_Iphone5s-1.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
Android task is completed. [SUCCESS]
```
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali03_LGE-LG-D855.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Device test finished on 7970f88c 
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5590220275263c8_Story001_fix_muxserverbridgetest_tobybrad/thali09_LGE-Nexus 5.md)





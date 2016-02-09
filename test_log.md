#### Test 58751238ee11130 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-09T14:24:31.211Z - info: listening on *:3000

2016-02-09T14:24:32.580Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-02-09T14:24:32.590Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:1

2016-02-09T14:24:32.749Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:2

2016-02-09T14:24:32.751Z - info: Required number of android devices presented (2)

2016-02-09T14:24:32.754Z - info: Starting unit test run for platform: android

2016-02-09T14:24:32.830Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:3

2016-02-09T14:24:32.832Z - info: Discarding surplus device: LGE-LG-D855

2016-02-09T14:24:33.485Z - debug: Socket disconnected: transport close 3 (LGE-LG-D855)

2016-02-09T14:24:33.547Z - info: Running on android test: multiplex can send data

2016-02-09T14:24:34.237Z - info: Running on android test: enqueue and run in order

2016-02-09T14:24:34.418Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:4

2016-02-09T14:24:34.419Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T14:24:34.580Z - info: Running on android test: basic

2016-02-09T14:24:34.722Z - info: Running on android test: another

2016-02-09T14:24:34.793Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-09T14:24:35.188Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-09T14:24:35.276Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-02-09T14:24:35.276Z - info: Discarding surplus device: LGE-LG-H815

2016-02-09T14:24:35.454Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T14:24:35.566Z - info: Running on android test: failed to get mobile documents path

2016-02-09T14:24:35.621Z - debug: Socket disconnected: transport close 4 (samsung-SM-G900F)

2016-02-09T14:24:35.659Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:6

2016-02-09T14:24:35.660Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-09T14:24:35.665Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-09T14:24:35.760Z - info: Running on android test: #init should register the networkChanged event

2016-02-09T14:24:35.866Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-09T14:24:35.981Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-09T14:24:36.082Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-09T14:24:36.104Z - debug: Socket disconnected: transport close 6 (LGE-Nexus 5)

2016-02-09T14:24:36.119Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:7

2016-02-09T14:24:36.120Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-09T14:24:36.190Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-09T14:24:36.257Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-02-09T14:24:36.270Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-09T14:24:36.358Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-09T14:24:36.461Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T14:24:36.493Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:8

2016-02-09T14:24:36.494Z - info: Required number of ios devices presented (2)

2016-02-09T14:24:36.496Z - info: Starting unit test run for platform: ios

2016-02-09T14:24:36.540Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T14:24:36.634Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T14:24:36.721Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T14:24:36.753Z - info: Running on ios test: multiplex can send data

2016-02-09T14:24:36.796Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T14:24:36.877Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-09T14:24:36.923Z - debug: Socket disconnected: transport close 7 (samsung-SM-N910C)

2016-02-09T14:24:36.963Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-09T14:24:37.051Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-09T14:24:37.137Z - info: Running on android test: #start should fail if called twice in a row

2016-02-09T14:24:37.233Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-09T14:24:37.342Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T14:24:37.362Z - info: Running on ios test: enqueue and run in order

2016-02-09T14:24:37.444Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-09T14:24:37.531Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T14:24:37.769Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T14:24:37.879Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T14:24:38.053Z - info: Running on ios test: basic

2016-02-09T14:24:38.521Z - info: Running on ios test: another

2016-02-09T14:24:38.888Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-09T14:24:39.421Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-09T14:24:39.629Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-09T14:24:39.630Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T14:24:39.761Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T14:24:40.113Z - info: Running on ios test: failed to get mobile documents path

2016-02-09T14:24:40.294Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-09T14:24:41.185Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-09T14:24:41.315Z - info: Running on ios test: #init should register the networkChanged event

2016-02-09T14:24:41.481Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-09T14:24:41.615Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-09T14:24:41.738Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-09T14:24:41.862Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-09T14:24:42.032Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-09T14:24:42.156Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-09T14:24:42.279Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T14:24:42.396Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T14:24:42.536Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T14:24:42.691Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T14:24:42.868Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T14:24:43.000Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-09T14:24:43.139Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-09T14:24:43.263Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-09T14:24:43.401Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-09T14:24:43.533Z - info: Running on ios test: #startListeningForAdvertisements should fail if start not called

2016-02-09T14:24:43.658Z - info: Running on ios test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T14:24:43.952Z - info: Running on ios test: should be able to call #startListeningForAdvertisements many times

2016-02-09T14:24:44.097Z - info: Running on ios test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T14:24:44.272Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T14:24:44.423Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T14:24:44.930Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-09T14:24:45.411Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-09T14:24:45.841Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-09T14:24:45.999Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-09T14:24:51.561Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-09T14:24:58.572Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-09T14:25:19.015Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-09T14:25:26.338Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-09T14:25:46.070Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-09T14:25:46.653Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-09T14:25:47.570Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-09T14:26:02.988Z - debug: Socket disconnected: ping timeout 1 (motorola-Nexus 6)

2016-02-09T14:26:08.735Z - info: Running on ios test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-09T14:26:11.156Z - debug: Socket disconnected: transport close 8 (Apple-Iphone6-1)

2016-02-09T14:38:06.648Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-02-09T14:41:15.995Z - debug: Socket disconnected: transport close 2 (LGE-LG-D722)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-02-09T14:25:07.603Z - error: test server: Device undefined


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58751238ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali09_LGE-Nexus 5.md)





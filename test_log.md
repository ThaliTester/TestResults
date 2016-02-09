#### Test 58741471ee11130 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-09T13:09:31.375Z - info: listening on *:3000

2016-02-09T13:09:31.776Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-02-09T13:09:32.286Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-02-09T13:09:32.775Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-02-09T13:09:32.778Z - info: Required number of android devices presented (2)

2016-02-09T13:09:32.782Z - info: Starting unit test run for platform: android

2016-02-09T13:09:32.975Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:4

2016-02-09T13:09:32.977Z - info: Discarding surplus device: LGE-LG-D855

2016-02-09T13:09:33.421Z - info: Running on android test: multiplex can send data

2016-02-09T13:09:33.733Z - info: Running on android test: enqueue and run in order

2016-02-09T13:09:33.788Z - debug: Socket disconnected: transport close 4 (LGE-LG-D855)

2016-02-09T13:09:34.119Z - info: Running on android test: basic

2016-02-09T13:09:34.263Z - info: Running on android test: another

2016-02-09T13:09:34.351Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-09T13:09:34.624Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-09T13:09:34.810Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T13:09:34.884Z - info: Running on android test: failed to get mobile documents path

2016-02-09T13:09:35.043Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-09T13:09:35.076Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-02-09T13:09:35.077Z - info: Required number of ios devices presented (2)

2016-02-09T13:09:35.078Z - info: Starting unit test run for platform: ios

2016-02-09T13:09:35.188Z - info: Running on android test: #init should register the networkChanged event

2016-02-09T13:09:35.300Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-09T13:09:35.386Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-02-09T13:09:35.389Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-09T13:09:35.463Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-09T13:09:35.511Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:6

2016-02-09T13:09:35.523Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-09T13:09:35.556Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-09T13:09:35.667Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-09T13:09:35.782Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-09T13:09:35.896Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-09T13:09:35.981Z - debug: Socket disconnected: transport close 5 (motorola-Nexus 6)

2016-02-09T13:09:35.998Z - debug: Socket disconnected: transport close 6 (LGE-Nexus 5)

2016-02-09T13:09:36.014Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T13:09:36.117Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T13:09:36.201Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T13:09:36.297Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T13:09:36.458Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T13:09:36.465Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:7

2016-02-09T13:09:36.469Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-09T13:09:36.571Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-09T13:09:36.670Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-09T13:09:36.747Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-09T13:09:36.850Z - info: Running on android test: #start should fail if called twice in a row

2016-02-09T13:09:36.967Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-09T13:09:37.071Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T13:09:37.174Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-09T13:09:37.280Z - debug: Socket disconnected: transport close 7 (samsung-SM-N910C)

2016-02-09T13:09:37.305Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T13:09:37.505Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T13:09:37.586Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T13:09:38.565Z - info: Running on ios test: multiplex can send data

2016-02-09T13:09:40.299Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:8

2016-02-09T13:09:40.300Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T13:09:41.110Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F)

2016-02-09T13:09:44.519Z - info: Running on ios test: enqueue and run in order

2016-02-09T13:09:45.607Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:9

2016-02-09T13:09:45.608Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-09T13:09:49.505Z - info: Running on ios test: basic

2016-02-09T13:09:59.944Z - info: Running on ios test: another

2016-02-09T13:10:00.211Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-09T13:10:00.696Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-09T13:10:00.736Z - debug: Socket disconnected: transport close 9 (Apple-Iphone5-1)

2016-02-09T13:10:00.971Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T13:10:01.304Z - info: Running on ios test: failed to get mobile documents path

2016-02-09T13:10:01.469Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-09T13:10:01.621Z - info: Running on ios test: #init should register the networkChanged event

2016-02-09T13:10:01.768Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-09T13:10:01.938Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-09T13:10:02.124Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-09T13:10:02.256Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-09T13:10:02.393Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-09T13:10:02.506Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-09T13:10:02.632Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T13:10:02.789Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T13:10:02.907Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T13:10:03.057Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T13:10:03.171Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T13:10:03.310Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-09T13:10:03.462Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-09T13:10:03.582Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-09T13:10:03.718Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-09T13:10:03.847Z - info: Running on ios test: #startListeningForAdvertisements should fail if start not called

2016-02-09T13:10:03.973Z - info: Running on ios test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T13:10:04.226Z - info: Running on ios test: should be able to call #startListeningForAdvertisements many times

2016-02-09T13:10:04.355Z - info: Running on ios test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T13:10:04.537Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T13:10:04.695Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T13:10:05.166Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-09T13:10:06.575Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-09T13:10:07.601Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-09T13:10:07.865Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-09T13:10:12.576Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-09T13:10:17.708Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-09T13:10:22.527Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-09T13:10:31.402Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-09T13:10:39.782Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-09T13:10:40.629Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-09T13:10:41.101Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-09T13:10:59.227Z - info: Running on ios test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-09T13:11:01.704Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-02-09T13:11:02.640Z - debug: Socket disconnected: ping timeout 1 (LGE-LG-H815)

2016-02-09T13:11:02.647Z - debug: Socket disconnected: ping timeout 3 (samsung-SM-G900F)

2016-02-09T13:22:51.020Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-02-09T13:11:08.249Z - error: test server: Device undefined


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58741471ee11130_Update_to_jxcore-cordova_0_1_1_vjrantal/thali09_LGE-Nexus 5.md)





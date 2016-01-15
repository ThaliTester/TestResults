#### Test 561517803567b2a Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-15T11:04:00.281Z - info: listening on *:3000

2016-01-15T11:04:00.861Z - debug: Device presented: UNITTEST-0.6990590446148921 (android) unittest socket:0

2016-01-15T11:04:00.944Z - debug: Device presented: UNITTEST-0.71324935102655 (android) unittest socket:1

2016-01-15T11:04:00.946Z - info: Required number of android devices presented (2)

2016-01-15T11:04:00.950Z - info: Starting unit test run for platform: android

2016-01-15T11:04:00.991Z - debug: Device presented: UNITTEST-0.4124414541631878 (ios) unittest socket:2

2016-01-15T11:04:01.194Z - debug: Device presented: UNITTEST-0.937070998782911 (android) unittest socket:3

2016-01-15T11:04:01.195Z - info: Discarding surplus device: UNITTEST-0.937070998782911

2016-01-15T11:04:01.259Z - info: Running test: multiplex can send data

2016-01-15T11:04:01.420Z - info: Running test: basic

2016-01-15T11:04:01.463Z - debug: Device presented: UNITTEST-0.1685408083634733 (ios) unittest socket:4

2016-01-15T11:04:01.464Z - info: Required number of ios devices presented (2)

2016-01-15T11:04:01.466Z - info: Starting unit test run for platform: ios

2016-01-15T11:04:01.486Z - info: Running test: another

2016-01-15T11:04:01.541Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-15T11:04:01.696Z - info: Running test: multiplex can send data

2016-01-15T11:04:01.830Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-15T11:04:01.985Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-15T11:04:02.010Z - debug: Device presented: UNITTEST-0.5667948736027668 (android) unittest socket:5

2016-01-15T11:04:02.011Z - info: Discarding surplus device: UNITTEST-0.5667948736027668

2016-01-15T11:04:02.050Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.937070998782911)

2016-01-15T11:04:02.098Z - info: Running test: failed to get mobile documents path

2016-01-15T11:04:02.156Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-15T11:04:02.163Z - debug: Device presented: UNITTEST-0.953979593291633 (ios) unittest socket:6

2016-01-15T11:04:02.166Z - info: Discarding surplus device: UNITTEST-0.953979593291633

2016-01-15T11:04:02.212Z - info: Running test: #init should register the networkChanged event

2016-01-15T11:04:02.256Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-15T11:04:02.290Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-15T11:04:02.329Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-15T11:04:02.372Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-15T11:04:02.412Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-15T11:04:02.446Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-15T11:04:02.490Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-15T11:04:02.540Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-15T11:04:02.612Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-15T11:04:02.715Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-15T11:04:02.767Z - debug: Device presented: UNITTEST-0.4042686434408188 (ios) unittest socket:7

2016-01-15T11:04:02.768Z - info: Discarding surplus device: UNITTEST-0.4042686434408188

2016-01-15T11:04:02.803Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-15T11:04:02.878Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-15T11:04:02.923Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-15T11:04:02.964Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-15T11:04:03.009Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-15T11:04:03.261Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.5667948736027668)

2016-01-15T11:04:03.486Z - debug: Device presented: UNITTEST-0.623142644629252 (android) unittest socket:8

2016-01-15T11:04:03.487Z - info: Discarding surplus device: UNITTEST-0.623142644629252

2016-01-15T11:04:03.678Z - debug: Device presented: UNITTEST-0.6545033205777513 (android) unittest socket:9

2016-01-15T11:04:03.679Z - info: Discarding surplus device: UNITTEST-0.6545033205777513

2016-01-15T11:04:03.719Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-15T11:04:03.892Z - debug: Device presented: UNITTEST-0.5894569062003534 (android) unittest socket:10

2016-01-15T11:04:03.893Z - info: Discarding surplus device: UNITTEST-0.5894569062003534

2016-01-15T11:04:04.179Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-15T11:04:04.545Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.6545033205777513)

2016-01-15T11:04:04.563Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-15T11:04:04.590Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.623142644629252)

2016-01-15T11:04:04.608Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.953979593291633)

2016-01-15T11:04:04.635Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.5894569062003534)

2016-01-15T11:04:04.964Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-15T11:04:05.142Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.4042686434408188)

2016-01-15T11:04:10.850Z - debug: Device presented: UNITTEST-0.5530765514077324 (android) unittest socket:11

2016-01-15T11:04:10.851Z - info: Discarding surplus device: UNITTEST-0.5530765514077324

2016-01-15T11:04:11.484Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.5530765514077324)

2016-01-15T11:04:16.472Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-15T11:26:33.254Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.4124414541631878)

2016-01-15T11:26:33.308Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.1685408083634733)

2016-01-15T11:30:33.307Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.6990590446148921)

2016-01-15T11:30:35.112Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.71324935102655)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/561517803567b2a_Update_to_jxcore-cordova_0_1_0_vjrantal/thali09_LGE-Nexus 5.md)





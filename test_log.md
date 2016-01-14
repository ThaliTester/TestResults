#### Test 55613145b105d0b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-14T09:35:54.921Z - info: listening on *:3000

2016-01-14T09:35:55.348Z - debug: Device presented: UNITTEST-0.31230290659051363 (android) unittest socket:0

2016-01-14T09:35:55.362Z - debug: Device presented: UNITTEST-0.5157912526404818 (android) unittest socket:1

2016-01-14T09:35:55.365Z - info: Required number of android devices presented (2)

2016-01-14T09:35:55.369Z - info: Starting unit test run for platform: android

2016-01-14T09:35:56.377Z - debug: Device presented: UNITTEST-0.026242778796162436 (android) unittest socket:2

2016-01-14T09:35:56.379Z - info: Discarding surplus device: UNITTEST-0.026242778796162436

2016-01-14T09:35:56.384Z - debug: Device presented: UNITTEST-0.1684196159648983 (android) unittest socket:3

2016-01-14T09:35:56.385Z - info: Discarding surplus device: UNITTEST-0.1684196159648983

2016-01-14T09:35:56.391Z - debug: Device presented: UNITTEST-0.11550049086541847 (android) unittest socket:4

2016-01-14T09:35:56.392Z - info: Discarding surplus device: UNITTEST-0.11550049086541847

2016-01-14T09:35:56.460Z - debug: Device presented: UNITTEST-0.8948920618749739 (ios) unittest socket:6

2016-01-14T09:35:56.555Z - debug: Device presented: UNITTEST-0.2138513305720875 (android) unittest socket:8

2016-01-14T09:35:56.556Z - info: Discarding surplus device: UNITTEST-0.2138513305720875

2016-01-14T09:35:56.618Z - debug: Device presented: UNITTEST-0.8776141541289685 (ios) unittest socket:10

2016-01-14T09:35:56.619Z - info: Required number of ios devices presented (2)

2016-01-14T09:35:56.620Z - info: Starting unit test run for platform: ios

2016-01-14T09:35:56.643Z - debug: Device presented: UNITTEST-0.27945505371945 (android) unittest socket:9

2016-01-14T09:35:56.644Z - info: Discarding surplus device: UNITTEST-0.27945505371945

2016-01-14T09:35:56.795Z - debug: Device presented: UNITTEST-0.9594729897167759 (android) unittest socket:7

2016-01-14T09:35:56.796Z - info: Discarding surplus device: UNITTEST-0.9594729897167759

2016-01-14T09:35:56.807Z - debug: Device presented: UNITTEST-0.5879389034854248 (android) unittest socket:5

2016-01-14T09:35:56.808Z - info: Discarding surplus device: UNITTEST-0.5879389034854248

2016-01-14T09:35:56.849Z - info: Running test: multiplex can send data

2016-01-14T09:35:56.949Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.11550049086541847)

2016-01-14T09:35:56.969Z - info: Running test: basic

2016-01-14T09:35:57.017Z - info: Running test: another

2016-01-14T09:35:57.086Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.2138513305720875)

2016-01-14T09:35:57.094Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-14T09:35:57.121Z - debug: Device presented: UNITTEST-0.5883397710904272 (ios) unittest socket:11

2016-01-14T09:35:57.122Z - info: Discarding surplus device: UNITTEST-0.5883397710904272

2016-01-14T09:35:57.343Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-14T09:35:57.404Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.5879389034854248)

2016-01-14T09:35:57.456Z - debug: Device presented: UNITTEST-0.9644096574028326 (android) unittest socket:12

2016-01-14T09:35:57.457Z - info: Discarding surplus device: UNITTEST-0.9644096574028326

2016-01-14T09:35:57.501Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-14T09:35:57.616Z - info: Running test: failed to get mobile documents path

2016-01-14T09:35:57.623Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.9594729897167759)

2016-01-14T09:35:57.696Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-14T09:35:57.703Z - debug: Device presented: UNITTEST-0.2585009690264267 (ios) unittest socket:13

2016-01-14T09:35:57.704Z - info: Discarding surplus device: UNITTEST-0.2585009690264267

2016-01-14T09:35:57.734Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.27945505371945)

2016-01-14T09:35:57.742Z - info: Running test: #init should register the networkChanged event

2016-01-14T09:35:57.794Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-14T09:35:57.886Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-14T09:35:57.943Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-14T09:35:57.996Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-14T09:35:58.047Z - debug: Device presented: UNITTEST-0.2605685727766546 (android) unittest socket:14

2016-01-14T09:35:58.048Z - info: Discarding surplus device: UNITTEST-0.2605685727766546

2016-01-14T09:35:58.102Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.9644096574028326)

2016-01-14T09:35:58.108Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-14T09:35:58.160Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-14T09:35:58.195Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.026242778796162436)

2016-01-14T09:35:58.236Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-14T09:35:58.254Z - debug: Device presented: UNITTEST-0.4803976622058147 (android) unittest socket:16

2016-01-14T09:35:58.255Z - info: Discarding surplus device: UNITTEST-0.4803976622058147

2016-01-14T09:35:58.292Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-14T09:35:58.373Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-14T09:35:58.433Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-14T09:35:58.441Z - debug: Device presented: UNITTEST-0.4027009771452147 (android) unittest socket:15

2016-01-14T09:35:58.442Z - info: Discarding surplus device: UNITTEST-0.4027009771452147

2016-01-14T09:35:58.499Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-14T09:35:58.546Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-14T09:35:58.594Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-14T09:35:58.641Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-14T09:35:58.689Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-14T09:35:58.861Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.2605685727766546)

2016-01-14T09:35:58.899Z - debug: Device presented: UNITTEST-0.5994832426935086 (android) unittest socket:17

2016-01-14T09:35:58.900Z - info: Discarding surplus device: UNITTEST-0.5994832426935086

2016-01-14T09:35:58.933Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.1684196159648983)

2016-01-14T09:35:58.985Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-14T09:35:59.051Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-14T09:35:59.118Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-14T09:35:59.148Z - debug: Device presented: UNITTEST-0.3003587713322593 (android) unittest socket:18

2016-01-14T09:35:59.149Z - info: Discarding surplus device: UNITTEST-0.3003587713322593

2016-01-14T09:35:59.192Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-14T09:35:59.211Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.4803976622058147)

2016-01-14T09:35:59.357Z - info: Running test: multiplex can send data

2016-01-14T09:35:59.549Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.5994832426935086)

2016-01-14T09:35:59.707Z - debug: Device presented: UNITTEST-0.2216702156780176 (android) unittest socket:19

2016-01-14T09:35:59.708Z - info: Discarding surplus device: UNITTEST-0.2216702156780176

2016-01-14T09:35:59.762Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.4027009771452147)

2016-01-14T09:35:59.908Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.3003587713322593)

2016-01-14T09:36:00.206Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.2585009690264267)

2016-01-14T09:36:00.413Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.5883397710904272)

2016-01-14T09:36:00.446Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.2216702156780176)

2016-01-14T09:36:01.005Z - debug: Device presented: UNITTEST-0.8386463355145196 (android) unittest socket:20

2016-01-14T09:36:01.008Z - info: Discarding surplus device: UNITTEST-0.8386463355145196

2016-01-14T09:36:01.637Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.8386463355145196)

2016-01-14T09:36:04.523Z - info: Running test: basic

2016-01-14T09:36:07.054Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-14T09:36:15.182Z - debug: Device presented: UNITTEST-0.44302355359651446 (android) unittest socket:21

2016-01-14T09:36:15.183Z - info: Discarding surplus device: UNITTEST-0.44302355359651446

2016-01-14T09:36:16.249Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.44302355359651446)

2016-01-14T09:36:16.357Z - info: Running test: another

2016-01-14T09:36:19.634Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-14T09:36:20.445Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-14T09:36:20.585Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-14T09:36:20.664Z - info: Running test: failed to get mobile documents path

2016-01-14T09:36:20.723Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-14T09:36:20.801Z - info: Running test: #init should register the networkChanged event

2016-01-14T09:36:20.861Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-14T09:36:20.945Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-14T09:36:21.037Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-14T09:36:21.180Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-14T09:36:21.248Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-14T09:36:21.325Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-14T09:36:21.367Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-14T09:36:21.419Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-14T09:36:21.463Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-14T09:36:21.846Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-14T09:36:22.302Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-14T09:36:22.879Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-14T09:36:23.257Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-14T09:36:23.609Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-14T09:36:24.004Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-14T09:36:35.369Z - debug: Device presented: UNITTEST-0.3478221914163967 (android) unittest socket:22

2016-01-14T09:36:35.373Z - info: Discarding surplus device: UNITTEST-0.3478221914163967

2016-01-14T09:36:36.133Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.3478221914163967)

2016-01-14T09:37:49.133Z - debug: Socket disconnected: ping timeout 1 (UNITTEST-0.5157912526404818)

2016-01-14T09:38:50.953Z - debug: Socket disconnected: ping timeout 6 (UNITTEST-0.8948920618749739)

2016-01-14T09:58:08.488Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.8776141541289685)

2016-01-14T10:02:12.890Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.31230290659051363)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55613145b105d0b_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali09_LGE-Nexus 5.md)





#### Test 55613145c131883 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-14T12:21:14.104Z - info: listening on *:3000

2016-01-14T12:21:15.023Z - debug: Device presented: UNITTEST-0.1423602662306127 (android) unittest socket:1

2016-01-14T12:21:15.222Z - debug: Device presented: UNITTEST-0.451735756902921 (android) unittest socket:2

2016-01-14T12:21:15.225Z - info: Required number of android devices presented (2)

2016-01-14T12:21:15.228Z - info: Starting unit test run for platform: android

2016-01-14T12:21:15.437Z - debug: Device presented: UNITTEST-0.9446792162913837 (android) unittest socket:4

2016-01-14T12:21:15.439Z - info: Discarding surplus device: UNITTEST-0.9446792162913837

2016-01-14T12:21:15.470Z - debug: Device presented: UNITTEST-0.8371278046893859 (android) unittest socket:3

2016-01-14T12:21:15.472Z - info: Discarding surplus device: UNITTEST-0.8371278046893859

2016-01-14T12:21:15.528Z - debug: Device presented: UNITTEST-0.4863356361874661 (ios) unittest socket:5

2016-01-14T12:21:15.674Z - debug: Device presented: UNITTEST-0.4806254041486734 (ios) unittest socket:0

2016-01-14T12:21:15.675Z - info: Required number of ios devices presented (2)

2016-01-14T12:21:15.676Z - info: Starting unit test run for platform: ios

2016-01-14T12:21:15.692Z - info: Running test: multiplex can send data

2016-01-14T12:21:15.894Z - info: Running test: multiplex can send data

2016-01-14T12:21:15.907Z - info: Running test: basic

2016-01-14T12:21:15.957Z - info: Running test: another

2016-01-14T12:21:16.022Z - info: Running test: basic

2016-01-14T12:21:16.062Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-14T12:21:16.067Z - info: Running test: another

2016-01-14T12:21:16.077Z - debug: Device presented: UNITTEST-0.6084649195763627 (android) unittest socket:6

2016-01-14T12:21:16.078Z - info: Discarding surplus device: UNITTEST-0.6084649195763627

2016-01-14T12:21:16.134Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.9446792162913837)

2016-01-14T12:21:16.149Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-14T12:21:16.341Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-14T12:21:16.366Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-14T12:21:16.443Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.8371278046893859)

2016-01-14T12:21:16.491Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-14T12:21:16.534Z - info: Running test: failed to get mobile documents path

2016-01-14T12:21:16.546Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-14T12:21:16.595Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-14T12:21:16.600Z - debug: Device presented: UNITTEST-0.056605409144689145 (android) unittest socket:7

2016-01-14T12:21:16.601Z - info: Discarding surplus device: UNITTEST-0.056605409144689145

2016-01-14T12:21:16.646Z - info: Running test: #init should register the networkChanged event

2016-01-14T12:21:16.676Z - info: Running test: failed to get mobile documents path

2016-01-14T12:21:16.693Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-14T12:21:16.739Z - debug: Device presented: UNITTEST-0.12017520432383544 (android) unittest socket:8

2016-01-14T12:21:16.740Z - info: Discarding surplus device: UNITTEST-0.12017520432383544

2016-01-14T12:21:16.750Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.6084649195763627)

2016-01-14T12:21:16.782Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-14T12:21:16.793Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-14T12:21:16.873Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-14T12:21:16.886Z - info: Running test: #init should register the networkChanged event

2016-01-14T12:21:16.956Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-14T12:21:16.962Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-14T12:21:17.026Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-14T12:21:17.032Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-14T12:21:17.079Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-14T12:21:17.090Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-14T12:21:17.101Z - debug: Device presented: UNITTEST-0.9396569074108395 (ios) unittest socket:9

2016-01-14T12:21:17.102Z - info: Discarding surplus device: UNITTEST-0.9396569074108395

2016-01-14T12:21:17.144Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-14T12:21:17.153Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-14T12:21:17.194Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-14T12:21:17.237Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-14T12:21:17.244Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-14T12:21:17.300Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-14T12:21:17.309Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-14T12:21:17.327Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.056605409144689145)

2016-01-14T12:21:17.381Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-14T12:21:17.400Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-14T12:21:17.424Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-14T12:21:17.444Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-14T12:21:17.466Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-14T12:21:17.491Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-14T12:21:17.513Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-14T12:21:17.549Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-14T12:21:17.556Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-14T12:21:17.629Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-14T12:21:17.639Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-14T12:21:17.686Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-14T12:21:17.709Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.12017520432383544)

2016-01-14T12:21:17.729Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-14T12:21:17.799Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-14T12:21:17.850Z - debug: Device presented: UNITTEST-0.35221519374786847 (ios) unittest socket:10

2016-01-14T12:21:17.851Z - info: Discarding surplus device: UNITTEST-0.35221519374786847

2016-01-14T12:21:18.005Z - debug: Device presented: UNITTEST-0.10370840310115381 (android) unittest socket:11

2016-01-14T12:21:18.006Z - info: Discarding surplus device: UNITTEST-0.10370840310115381

2016-01-14T12:21:18.094Z - debug: Device presented: UNITTEST-0.576313718203208 (android) unittest socket:12

2016-01-14T12:21:18.095Z - info: Discarding surplus device: UNITTEST-0.576313718203208

2016-01-14T12:21:18.149Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-14T12:21:18.159Z - debug: Device presented: UNITTEST-0.911165894164025 (android) unittest socket:13

2016-01-14T12:21:18.160Z - info: Discarding surplus device: UNITTEST-0.911165894164025

2016-01-14T12:21:18.263Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-14T12:21:18.272Z - debug: Device presented: UNITTEST-0.8919688095188787 (android) unittest socket:14

2016-01-14T12:21:18.274Z - info: Discarding surplus device: UNITTEST-0.8919688095188787

2016-01-14T12:21:18.322Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-14T12:21:18.464Z - debug: Device presented: UNITTEST-0.9675713108699406 (android) unittest socket:15

2016-01-14T12:21:18.466Z - info: Discarding surplus device: UNITTEST-0.9675713108699406

2016-01-14T12:21:18.528Z - debug: Device presented: UNITTEST-0.7692273478736635 (android) unittest socket:16

2016-01-14T12:21:18.529Z - info: Discarding surplus device: UNITTEST-0.7692273478736635

2016-01-14T12:21:18.580Z - debug: Device presented: UNITTEST-0.5835817505821597 (android) unittest socket:17

2016-01-14T12:21:18.581Z - info: Discarding surplus device: UNITTEST-0.5835817505821597

2016-01-14T12:21:18.653Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-14T12:21:18.709Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.576313718203208)

2016-01-14T12:21:18.755Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.8919688095188787)

2016-01-14T12:21:18.770Z - debug: Device presented: UNITTEST-0.3279370021364526 (android) unittest socket:18

2016-01-14T12:21:18.772Z - info: Discarding surplus device: UNITTEST-0.3279370021364526

2016-01-14T12:21:18.838Z - debug: Device presented: UNITTEST-0.0016258175912930994 (android) unittest socket:19

2016-01-14T12:21:18.839Z - info: Discarding surplus device: UNITTEST-0.0016258175912930994

2016-01-14T12:21:18.956Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.911165894164025)

2016-01-14T12:21:19.296Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.10370840310115381)

2016-01-14T12:21:19.301Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.5835817505821597)

2016-01-14T12:21:19.405Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.3279370021364526)

2016-01-14T12:21:19.434Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.9675713108699406)

2016-01-14T12:21:19.839Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.0016258175912930994)

2016-01-14T12:21:20.240Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.9396569074108395)

2016-01-14T12:21:20.321Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-14T12:21:20.326Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.35221519374786847)

2016-01-14T12:21:20.638Z - debug: Device presented: UNITTEST-0.46737098491699547 (android) unittest socket:20

2016-01-14T12:21:20.640Z - info: Discarding surplus device: UNITTEST-0.46737098491699547

2016-01-14T12:21:20.782Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-14T12:21:21.252Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-14T12:21:21.604Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.46737098491699547)

2016-01-14T12:21:21.821Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-14T12:21:22.761Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.7692273478736635)

2016-01-14T12:21:23.008Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-14T12:21:27.751Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-14T12:21:30.589Z - debug: Device presented: UNITTEST-0.2679330586936042 (android) unittest socket:21

2016-01-14T12:21:30.591Z - info: Discarding surplus device: UNITTEST-0.2679330586936042

2016-01-14T12:21:32.363Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.2679330586936042)

2016-01-14T12:21:34.017Z - info: Running test: ThaliEmitter can connect and send data

2016-01-14T12:21:36.742Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-14T12:21:42.933Z - debug: Device presented: UNITTEST-0.21924178977777953 (android) unittest socket:22

2016-01-14T12:21:42.934Z - info: Discarding surplus device: UNITTEST-0.21924178977777953

2016-01-14T12:21:43.764Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.21924178977777953)

2016-01-14T12:21:43.945Z - info: Running test: ThaliEmitter handles socket disconnect correctly

2016-01-14T12:22:05.466Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.4806254041486734)

2016-01-14T12:22:08.438Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.4863356361874661)

2016-01-14T12:47:24.289Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.451735756902921)

2016-01-14T12:49:00.333Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.1423602662306127)


 
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
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/iOS_Iphone5s-1.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on ZX1C223JKW 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Device test finished on 7970f88c 
Device test finished on 022678fb504e29b0 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on HT574YC04723 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55613145c131883_Add_support_for_installing_jxcore-cordova_plugin_using_JXC_vjrantal/thali09_LGE-Nexus 5.md)





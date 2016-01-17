#### Test 56151093c886730 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-17T12:42:04.905Z - info: listening on *:3000

2016-01-17T12:42:05.269Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-01-17T12:42:05.310Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:1

2016-01-17T12:42:05.329Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:2

2016-01-17T12:42:05.331Z - info: Required number of android devices presented (2)

2016-01-17T12:42:05.335Z - info: Starting unit test run for platform: android

2016-01-17T12:42:05.369Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-01-17T12:42:05.371Z - info: Required number of ios devices presented (2)

2016-01-17T12:42:05.372Z - info: Starting unit test run for platform: ios

2016-01-17T12:42:05.511Z - info: Running on ios test: multiplex can send data

2016-01-17T12:42:05.559Z - info: Running on android test: multiplex can send data

2016-01-17T12:42:05.612Z - info: Running on ios test: basic

2016-01-17T12:42:05.635Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:4

2016-01-17T12:42:05.638Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-17T12:42:05.660Z - info: Running on ios test: another

2016-01-17T12:42:05.703Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-17T12:42:05.929Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-17T12:42:05.951Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:5

2016-01-17T12:42:05.952Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-17T12:42:06.074Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-17T12:42:06.186Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:6

2016-01-17T12:42:06.187Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-17T12:42:06.200Z - info: Running on ios test: failed to get mobile documents path

2016-01-17T12:42:06.246Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-17T12:42:06.278Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:7

2016-01-17T12:42:06.280Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-17T12:42:06.304Z - info: Running on ios test: #init should register the networkChanged event

2016-01-17T12:42:06.348Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-17T12:42:06.399Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-17T12:42:06.443Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-17T12:42:06.496Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-17T12:42:06.543Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-17T12:42:06.586Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-17T12:42:06.608Z - debug: Socket disconnected: transport close 5 (samsung-SM-A300FU)

2016-01-17T12:42:06.664Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-17T12:42:06.708Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-17T12:42:06.718Z - debug: Socket disconnected: transport close 4 (HTC-HTC Desire 820)

2016-01-17T12:42:06.774Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-17T12:42:06.791Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:8

2016-01-17T12:42:06.792Z - info: Discarding surplus device: LGE-LG-H815

2016-01-17T12:42:06.846Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-17T12:42:06.869Z - debug: Socket disconnected: transport close 7 (samsung-SM-A500FU)

2016-01-17T12:42:06.945Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-17T12:42:06.959Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F)

2016-01-17T12:42:07.046Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-17T12:42:07.052Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:9

2016-01-17T12:42:07.053Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-17T12:42:07.097Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-17T12:42:07.138Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-17T12:42:07.183Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-17T12:42:07.430Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:10

2016-01-17T12:42:07.431Z - info: Discarding surplus device: LGE-LG-D855

2016-01-17T12:42:07.489Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:11

2016-01-17T12:42:07.490Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-17T12:42:07.497Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-17T12:42:07.559Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-17T12:42:07.624Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-17T12:42:07.691Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-17T12:42:07.709Z - debug: Socket disconnected: transport close 8 (LGE-LG-H815)

2016-01-17T12:42:08.091Z - debug: Socket disconnected: transport close 11 (samsung-SM-N910C)

2016-01-17T12:42:08.119Z - debug: Socket disconnected: transport close 10 (LGE-LG-D855)

2016-01-17T12:42:08.256Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:12

2016-01-17T12:42:08.257Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-17T12:42:08.533Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:14

2016-01-17T12:42:08.534Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-17T12:42:08.580Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:13

2016-01-17T12:42:08.581Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-17T12:42:08.698Z - debug: Socket disconnected: transport close 12 (LGE-Nexus 5)

2016-01-17T12:42:08.847Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:15

2016-01-17T12:42:08.848Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-01-17T12:42:08.913Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:16

2016-01-17T12:42:08.915Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-17T12:42:09.054Z - debug: Device presented: LGE-LG-D802 (android) unittest socket:17

2016-01-17T12:42:09.055Z - info: Discarding surplus device: LGE-LG-D802

2016-01-17T12:42:09.090Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:18

2016-01-17T12:42:09.091Z - info: Discarding surplus device: LGE-LG-D722

2016-01-17T12:42:09.144Z - debug: Socket disconnected: transport close 14 (samsung-SM-A300FU)

2016-01-17T12:42:09.352Z - debug: Device presented: motorola-XT1072 (android) unittest socket:19

2016-01-17T12:42:09.353Z - info: Discarding surplus device: motorola-XT1072

2016-01-17T12:42:09.452Z - debug: Socket disconnected: transport close 13 (samsung-SM-G900F)

2016-01-17T12:42:09.511Z - debug: Socket disconnected: transport close 16 (samsung-SM-A500FU)

2016-01-17T12:42:09.876Z - debug: Socket disconnected: transport close 17 (LGE-LG-D802)

2016-01-17T12:42:10.017Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:20

2016-01-17T12:42:10.018Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-17T12:42:10.166Z - debug: Socket disconnected: transport close 19 (motorola-XT1072)

2016-01-17T12:42:10.340Z - debug: Socket disconnected: transport close 9 (Apple-Iphone5-1)

2016-01-17T12:42:10.530Z - debug: Socket disconnected: transport close 20 (LGE-Nexus 5)

2016-01-17T12:42:11.387Z - debug: Socket disconnected: transport close 15 (Apple-IpadAir2-1)

2016-01-17T12:42:12.805Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-17T12:42:12.810Z - debug: Socket disconnected: transport close 18 (LGE-LG-D722)

2016-01-17T12:42:13.480Z - debug: Device presented: motorola-XT1039 (android) unittest socket:21

2016-01-17T12:42:13.481Z - info: Discarding surplus device: motorola-XT1039

2016-01-17T12:42:14.295Z - debug: Socket disconnected: transport close 21 (motorola-XT1039)

2016-01-17T12:42:14.313Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:22

2016-01-17T12:42:14.314Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-17T12:42:16.838Z - debug: Socket disconnected: transport close 22 (samsung-SM-G800F)

2016-01-17T12:42:41.551Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-17T12:44:15.722Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone6-1)

2016-01-17T12:54:43.666Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-01-17T12:58:43.976Z - debug: Socket disconnected: transport close 1 (HTC-HTC Desire 820)

2016-01-17T12:59:26.725Z - debug: Socket disconnected: transport close 2 (HTC-HTC One M8s)


 
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
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Device test finished on 320414cd475f91e3 
Android task is completed. [SUCCESS]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on HT574YC04723 
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:0 
child process exited with code 0 on device CC51WYC03425 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56151093c886730_Wifi-based_mocks_for_the_current_version_vjrantal/thali09_LGE-Nexus 5.md)





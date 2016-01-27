#### Test 57321924b5e4f25 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-27T07:32:51.314Z - info: listening on *:3000

2016-01-27T07:32:52.599Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:0

2016-01-27T07:32:52.652Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-01-27T07:32:52.657Z - info: Required number of android devices presented (2)

2016-01-27T07:32:52.660Z - info: Starting unit test run for platform: android

2016-01-27T07:32:52.716Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:2

2016-01-27T07:32:52.719Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-27T07:32:52.760Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:3

2016-01-27T07:32:52.761Z - info: Discarding surplus device: LGE-LG-D722

2016-01-27T07:32:52.806Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-01-27T07:32:52.883Z - info: Running on android test: multiplex can send data

2016-01-27T07:32:53.103Z - info: Running on android test: enqueue and run in order

2016-01-27T07:32:53.440Z - info: Running on android test: basic

2016-01-27T07:32:53.459Z - debug: Socket disconnected: transport close 2 (samsung-SM-N910C)

2016-01-27T07:32:53.526Z - info: Running on android test: another

2016-01-27T07:32:53.631Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-27T07:32:53.700Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-01-27T07:32:53.701Z - info: Required number of ios devices presented (2)

2016-01-27T07:32:53.702Z - info: Starting unit test run for platform: ios

2016-01-27T07:32:53.919Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-27T07:32:53.955Z - debug: Socket disconnected: transport close 3 (LGE-LG-D722)

2016-01-27T07:32:54.000Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-01-27T07:32:54.003Z - info: Discarding surplus device: motorola-Nexus 6

2016-01-27T07:32:54.230Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-01-27T07:32:54.231Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-27T07:32:54.247Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-27T07:32:54.316Z - info: Running on android test: failed to get mobile documents path

2016-01-27T07:32:54.448Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-27T07:32:54.523Z - info: Running on android test: #init should register the networkChanged event

2016-01-27T07:32:54.605Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:8

2016-01-27T07:32:54.606Z - info: Discarding surplus device: HTC-HTC One M8s

2016-01-27T07:32:54.653Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-01-27T07:32:55.194Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:9

2016-01-27T07:32:55.195Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-27T07:32:55.332Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-01-27T07:32:55.780Z - debug: Socket disconnected: transport close 8 (HTC-HTC One M8s)

2016-01-27T07:32:56.367Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:10

2016-01-27T07:32:56.368Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-27T07:32:56.514Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:11

2016-01-27T07:32:56.515Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-27T07:32:56.552Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:12

2016-01-27T07:32:56.553Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-27T07:32:56.576Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-27T07:32:56.798Z - debug: Socket disconnected: transport close 10 (LGE-Nexus 5)

2016-01-27T07:32:57.492Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:13

2016-01-27T07:32:57.494Z - info: Discarding surplus device: LGE-LG-D855

2016-01-27T07:32:57.686Z - debug: Socket disconnected: transport close 11 (samsung-SM-G900F)

2016-01-27T07:32:57.843Z - debug: Socket disconnected: transport close 9 (Apple-Iphone6-1)

2016-01-27T07:32:58.253Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-27T07:32:58.318Z - debug: Socket disconnected: transport close 13 (LGE-LG-D855)

2016-01-27T07:32:58.412Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-27T07:32:58.543Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-27T07:32:58.595Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-27T07:32:58.772Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-27T07:32:58.951Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-27T07:32:59.109Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-27T07:32:59.351Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-27T07:32:59.515Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-27T07:32:59.573Z - debug: Socket disconnected: transport close 12 (Apple-Iphone5-1)

2016-01-27T07:32:59.639Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-27T07:32:59.697Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-27T07:32:59.871Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-27T07:33:00.313Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-27T07:33:00.410Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-27T07:33:00.611Z - info: Running on ios test: multiplex can send data

2016-01-27T07:33:01.428Z - info: Running on ios test: enqueue and run in order

2016-01-27T07:33:01.946Z - info: Running on ios test: basic

2016-01-27T07:33:03.333Z - info: Running on ios test: another

2016-01-27T07:33:03.653Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-27T07:33:12.084Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-27T07:33:15.254Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-27T07:33:17.764Z - info: Running on ios test: failed to get mobile documents path

2016-01-27T07:33:18.008Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-27T07:33:18.064Z - info: Running on ios test: #init should register the networkChanged event

2016-01-27T07:33:18.111Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-27T07:33:18.213Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-27T07:33:18.307Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-27T07:33:18.361Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-27T07:33:18.423Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-27T07:33:18.488Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-27T07:33:18.539Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-27T07:33:18.605Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-27T07:33:18.710Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-27T07:33:18.777Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-27T07:33:18.831Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-27T07:33:18.881Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-27T07:33:18.928Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-27T07:33:19.064Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-27T07:33:19.123Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-27T07:33:19.431Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-27T07:33:20.599Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-27T07:33:22.209Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-27T07:33:22.645Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-27T07:33:27.436Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-27T07:33:32.182Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-27T07:33:36.925Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-27T07:33:44.245Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-27T07:33:55.151Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-27T07:33:56.408Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-27T07:33:57.262Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-27T07:34:25.438Z - debug: Socket disconnected: ping timeout 0 (LGE-Nexus 5)

2016-01-27T07:34:29.745Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-27T07:34:32.597Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-01-27T07:46:17.818Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-01-27T07:49:17.008Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)


 
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
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57321924b5e4f25_Use_leveldown-mobile_also_on_desktop__vjrantal/thali09_LGE-Nexus 5.md)





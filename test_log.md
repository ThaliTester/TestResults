#### Test 57617811ecc172f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-29T10:32:41.054Z - info: listening on *:3000

2016-01-29T10:32:41.673Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:1

2016-01-29T10:32:41.754Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:2

2016-01-29T10:32:41.757Z - info: Required number of android devices presented (2)

2016-01-29T10:32:41.760Z - info: Starting unit test run for platform: android

2016-01-29T10:32:42.109Z - info: Running on android test: multiplex can send data

2016-01-29T10:32:42.259Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-01-29T10:32:42.321Z - info: Running on android test: enqueue and run in order

2016-01-29T10:32:42.347Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:4

2016-01-29T10:32:42.349Z - info: Discarding surplus device: motorola-Nexus 6

2016-01-29T10:32:42.671Z - info: Running on android test: basic

2016-01-29T10:32:42.753Z - info: Running on android test: another

2016-01-29T10:32:42.797Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-29T10:32:42.847Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:5

2016-01-29T10:32:42.851Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-29T10:32:42.856Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:6

2016-01-29T10:32:42.857Z - info: Discarding surplus device: LGE-LG-H815

2016-01-29T10:32:42.998Z - debug: Socket disconnected: transport close 4 (motorola-Nexus 6)

2016-01-29T10:32:43.168Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-29T10:32:43.313Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:7

2016-01-29T10:32:43.314Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-29T10:32:43.420Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-29T10:32:43.517Z - info: Running on android test: failed to get mobile documents path

2016-01-29T10:32:43.588Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-29T10:32:43.652Z - info: Running on android test: #init should register the networkChanged event

2016-01-29T10:32:43.733Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-29T10:32:43.807Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-29T10:32:43.817Z - debug: Socket disconnected: transport close 6 (LGE-LG-H815)

2016-01-29T10:32:43.826Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F)

2016-01-29T10:32:43.845Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:8

2016-01-29T10:32:43.849Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-29T10:32:43.854Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:9

2016-01-29T10:32:43.855Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-29T10:32:43.919Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:10

2016-01-29T10:32:43.920Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-29T10:32:43.925Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-29T10:32:44.034Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-29T10:32:44.077Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-29T10:32:44.148Z - debug: Socket disconnected: transport close 7 (samsung-SM-N910C)

2016-01-29T10:32:44.156Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-29T10:32:44.219Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-29T10:32:44.310Z - debug: Socket disconnected: transport close 9 (LGE-Nexus 5)

2016-01-29T10:32:44.382Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-29T10:32:44.448Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-29T10:32:44.515Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:0

2016-01-29T10:32:44.516Z - info: Required number of ios devices presented (2)
2016-01-29T10:32:44.518Z - info: Starting unit test run for platform: ios

2016-01-29T10:32:44.532Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-29T10:32:44.615Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-29T10:32:44.685Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-29T10:32:44.742Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-29T10:32:44.797Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-29T10:32:44.853Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-29T10:32:44.886Z - debug: Socket disconnected: transport close 8 (HTC-HTC Desire 820)

2016-01-29T10:32:44.972Z - info: Running on ios test: multiplex can send data

2016-01-29T10:32:44.994Z - debug: Socket disconnected: transport close 10 (HTC-HTC Desire 820)

2016-01-29T10:32:46.000Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:11

2016-01-29T10:32:46.001Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-29T10:32:46.015Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-29T10:32:46.400Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-29T10:32:46.997Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-29T10:32:47.443Z - info: Running on android test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-01-29T10:32:47.714Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-29T10:32:47.857Z - info: Running on android test: messages with invalid location or USN should be ignored

2016-01-29T10:32:48.021Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-29T10:32:48.129Z - info: Running on android test: #start should fail if called twice in a row

2016-01-29T10:32:48.206Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-29T10:32:48.303Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-01-29T10:32:48.419Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-29T10:32:48.597Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-29T10:32:48.654Z - info: Running on android test: #startListeningForAdvertisements can be called multiple times in a row

2016-01-29T10:32:48.768Z - info: Running on android test: #stopListeningForAdvertisements can be called multiple times in a row

2016-01-29T10:32:48.952Z - info: Running on android test: #stopAdvertisingAndListening can be called multiple times in a row

2016-01-29T10:32:49.067Z - info: Running on android test: functions are run from a queue in the right order

2016-01-29T10:32:49.186Z - info: Test run on android complete

2016-01-29T10:32:49.189Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-29T10:32:49.190Z - info: PLATFORM: android

2016-01-29T10:32:49.191Z - info: RESULT: PASS

2016-01-29T10:32:49.193Z - info: 41 of 41 tests completed

2016-01-29T10:32:49.194Z - info: 41/41 passed (0 failures)

2016-01-29T10:32:49.195Z - info: --- Test Details ---



2016-01-29T10:32:49.196Z - info: multiplex can send data - pass

2016-01-29T10:32:49.197Z - info: enqueue and run in order - pass

2016-01-29T10:32:49.198Z - info: basic - pass

2016-01-29T10:32:49.199Z - info: another - pass

2016-01-29T10:32:49.200Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-29T10:32:49.201Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-29T10:32:49.202Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-29T10:32:49.204Z - info: failed to get mobile documents path - pass

2016-01-29T10:32:49.205Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-29T10:32:49.206Z - info: #init should register the networkChanged event - pass

2016-01-29T10:32:49.208Z - info: #startBroadcasting should throw on null device name - pass

2016-01-29T10:32:49.209Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-29T10:32:49.210Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-29T10:32:49.211Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-29T10:32:49.212Z - info: #startBroadcasting should throw on negative port - pass

2016-01-29T10:32:49.213Z - info: #startBroadcasting should throw on too large port - pass

2016-01-29T10:32:49.214Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-29T10:32:49.224Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-29T10:32:49.225Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-29T10:32:49.226Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-29T10:32:49.227Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-29T10:32:49.228Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-29T10:32:49.229Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-29T10:32:49.230Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-29T10:32:49.231Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-29T10:32:49.232Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-29T10:32:49.233Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-29T10:32:49.234Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-29T10:32:49.235Z - info: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-01-29T10:32:49.236Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-01-29T10:32:49.237Z - info: messages with invalid location or USN should be ignored - pass
2016-01-29T10:32:49.238Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-29T10:32:49.239Z - info: #start should fail if called twice in a row - pass

2016-01-29T10:32:49.240Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-01-29T10:32:49.241Z - info: #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-01-29T10:32:49.241Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-01-29T10:32:49.246Z - info: #stop can be called multiple times in a row - pass

2016-01-29T10:32:49.247Z - info: #startListeningForAdvertisements can be called multiple times in a row - pass

2016-01-29T10:32:49.248Z - info: #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-01-29T10:32:49.249Z - info: #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-01-29T10:32:49.250Z - info: functions are run from a queue in the right order - pass

2016-01-29T10:32:49.251Z - info: 

-== END ==-

2016-01-29T10:32:49.273Z - debug: Socket disconnected: transport close 11 (Apple-Iphone5-1)

2016-01-29T10:32:50.717Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:12

2016-01-29T10:32:50.718Z - info: Discarding surplus device: LGE-LG-D855

2016-01-29T10:32:51.680Z - debug: Socket disconnected: transport close 12 (LGE-LG-D855)

2016-01-29T10:33:01.363Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:13

2016-01-29T10:33:01.364Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-29T10:33:02.657Z - debug: Socket disconnected: transport close 13 (samsung-SM-G800F)

2016-01-29T10:34:14.203Z - debug: Socket disconnected: ping timeout 2 (LGE-LG-D722)

2016-01-29T10:34:14.210Z - debug: Socket disconnected: ping timeout 1 (samsung-SM-G900F)

2016-01-29T10:45:53.862Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-01-29T10:45:53.940Z - debug: Socket disconnected: transport close 0 (Apple-Iphone5s-1)


 
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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on HT574YC04723 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57617811ecc172f_Use_leveldown-mobile_also_on_desktop__vjrantal/thali09_LGE-Nexus 5.md)





#### Test 5761781115ba656 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-29T08:32:00.109Z - info: listening on *:3000

2016-01-29T08:32:00.802Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:0

2016-01-29T08:32:01.469Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-01-29T08:32:01.472Z - info: Required number of android devices presented (2)

2016-01-29T08:32:01.475Z - info: Starting unit test run for platform: android

2016-01-29T08:32:01.741Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:2

2016-01-29T08:32:01.742Z - info: Discarding surplus device: motorola-Nexus 6

2016-01-29T08:32:02.022Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-01-29T08:32:02.300Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-01-29T08:32:02.303Z - info: Required number of ios devices presented (2)

2016-01-29T08:32:02.304Z - info: Starting unit test run for platform: ios

2016-01-29T08:32:02.328Z - debug: Socket disconnected: transport close 2 (motorola-Nexus 6)

2016-01-29T08:32:02.613Z - info: Running on android test: multiplex can send data

2016-01-29T08:32:02.669Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:5

2016-01-29T08:32:02.670Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-29T08:32:02.675Z - info: Running on ios test: multiplex can send data

2016-01-29T08:32:03.173Z - debug: Socket disconnected: transport close 5 (LGE-Nexus 5)

2016-01-29T08:32:03.567Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-01-29T08:32:03.568Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-29T08:32:04.286Z - info: Running on ios test: enqueue and run in order

2016-01-29T08:32:04.341Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-01-29T08:32:04.342Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-29T08:32:04.583Z - debug: Socket disconnected: transport close 6 (samsung-SM-N910C)

2016-01-29T08:32:04.798Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-01-29T08:32:04.803Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-29T08:32:04.824Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:10

2016-01-29T08:32:04.827Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-29T08:32:04.840Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:8

2016-01-29T08:32:04.841Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-29T08:32:05.026Z - info: Running on ios test: basic

2016-01-29T08:32:05.328Z - info: Running on android test: enqueue and run in order

2016-01-29T08:32:05.576Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-01-29T08:32:05.654Z - info: Running on android test: basic

2016-01-29T08:32:05.674Z - info: Running on ios test: another

2016-01-29T08:32:05.768Z - debug: Socket disconnected: transport close 10 (HTC-HTC Desire 820)

2016-01-29T08:32:05.781Z - info: Running on android test: another

2016-01-29T08:32:05.823Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-29T08:32:05.966Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-01-29T08:32:06.090Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-29T08:32:06.186Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-29T08:32:06.445Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-29T08:32:06.712Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-29T08:32:06.832Z - info: Running on android test: failed to get mobile documents path

2016-01-29T08:32:07.045Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-29T08:32:07.108Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-29T08:32:07.268Z - info: Running on android test: #init should register the networkChanged event

2016-01-29T08:32:07.401Z - info: Running on ios test: failed to get mobile documents path

2016-01-29T08:32:07.442Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-29T08:32:07.480Z - debug: Socket disconnected: transport close 8 (Apple-Iphone6-1)

2016-01-29T08:32:07.485Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-29T08:32:07.521Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-29T08:32:07.610Z - info: Running on ios test: #init should register the networkChanged event

2016-01-29T08:32:07.671Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-29T08:32:07.775Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-29T08:32:07.800Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-29T08:32:07.887Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-29T08:32:07.899Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-29T08:32:07.964Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-29T08:32:07.982Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-29T08:32:08.084Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-29T08:32:08.093Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-29T08:32:08.148Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-29T08:32:08.165Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-29T08:32:08.320Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-29T08:32:08.374Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-29T08:32:08.422Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-29T08:32:08.521Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-29T08:32:08.579Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-29T08:32:08.632Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-29T08:32:08.687Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-29T08:32:08.763Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:11

2016-01-29T08:32:08.764Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-29T08:32:09.344Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:12

2016-01-29T08:32:09.345Z - info: Discarding surplus device: LGE-LG-D855

2016-01-29T08:32:09.833Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-29T08:32:10.125Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-29T08:32:10.261Z - debug: Socket disconnected: transport close 12 (LGE-LG-D855)

2016-01-29T08:32:10.705Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-29T08:32:11.257Z - info: Running on android test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-01-29T08:32:11.558Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-29T08:32:11.976Z - info: Running on android test: messages with invalid location or USN should be ignored

2016-01-29T08:32:12.043Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-29T08:32:12.111Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-29T08:32:12.268Z - debug: Socket disconnected: transport close 11 (Apple-Iphone5-1)

2016-01-29T08:32:12.282Z - info: Running on android test: #start should fail if called twice in a row

2016-01-29T08:32:12.464Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-29T08:32:12.602Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-01-29T08:32:12.793Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-29T08:32:13.030Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-29T08:32:13.091Z - info: Running on android test: #startListeningForAdvertisements can be called multiple times in a row

2016-01-29T08:32:13.193Z - info: Running on android test: #stopListeningForAdvertisements can be called multiple times in a row

2016-01-29T08:32:13.290Z - info: Running on android test: #stopAdvertisingAndListening can be called multiple times in a row

2016-01-29T08:32:13.406Z - info: Running on android test: functions are run from a queue in the right order

2016-01-29T08:32:13.532Z - info: Test run on android complete

2016-01-29T08:32:13.534Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-29T08:32:13.535Z - info: PLATFORM: android

2016-01-29T08:32:13.538Z - info: RESULT: PASS

2016-01-29T08:32:13.539Z - info: 41 of 41 tests completed

2016-01-29T08:32:13.541Z - info: 41/41 passed (0 failures)

2016-01-29T08:32:13.542Z - info: --- Test Details ---



2016-01-29T08:32:13.543Z - info: multiplex can send data - pass

2016-01-29T08:32:13.544Z - info: enqueue and run in order - pass

2016-01-29T08:32:13.545Z - info: basic - pass
2016-01-29T08:32:13.546Z - info: another - pass

2016-01-29T08:32:13.547Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-29T08:32:13.547Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-29T08:32:13.548Z - info: failed to extract public key because of corrupt pkcs12 file - pass
2016-01-29T08:32:13.549Z - info: failed to get mobile documents path - pass

2016-01-29T08:32:13.550Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-29T08:32:13.551Z - info: #init should register the networkChanged event - pass

2016-01-29T08:32:13.552Z - info: #startBroadcasting should throw on null device name - pass
2016-01-29T08:32:13.553Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-29T08:32:13.554Z - info: #startBroadcasting should throw on non-number port - pass
2016-01-29T08:32:13.555Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-29T08:32:13.556Z - info: #startBroadcasting should throw on negative port - pass
2016-01-29T08:32:13.556Z - info: #startBroadcasting should throw on too large port - pass

2016-01-29T08:32:13.557Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-29T08:32:13.562Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-29T08:32:13.562Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-29T08:32:13.563Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-29T08:32:13.564Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-01-29T08:32:13.565Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-29T08:32:13.566Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-29T08:32:13.567Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-29T08:32:13.568Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-29T08:32:13.569Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-29T08:32:13.572Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-29T08:32:13.574Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-29T08:32:13.575Z - info: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-01-29T08:32:13.576Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-01-29T08:32:13.576Z - info: messages with invalid location or USN should be ignored - pass

2016-01-29T08:32:13.579Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-29T08:32:13.583Z - info: #start should fail if called twice in a row - pass
2016-01-29T08:32:13.583Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-01-29T08:32:13.584Z - info: #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-01-29T08:32:13.585Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-01-29T08:32:13.586Z - info: #stop can be called multiple times in a row - pass
2016-01-29T08:32:13.586Z - info: #startListeningForAdvertisements can be called multiple times in a row - pass
2016-01-29T08:32:13.587Z - info: #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-01-29T08:32:13.588Z - info: #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-01-29T08:32:13.588Z - info: functions are run from a queue in the right order - pass
2016-01-29T08:32:13.589Z - info: 

-== END ==-

2016-01-29T08:32:15.100Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-29T08:32:18.203Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-29T08:32:18.550Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-29T08:32:18.868Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-29T08:32:19.077Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-29T08:32:19.487Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-29T08:32:19.944Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-29T08:32:23.492Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-29T08:33:38.547Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-D722)

2016-01-29T08:33:38.552Z - debug: Socket disconnected: ping timeout 1 (LGE-LG-H815)

2016-01-29T08:33:51.795Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone5s-1)

2016-01-29T08:35:56.813Z - debug: Socket disconnected: transport close 13 (NOT YET SET)

2016-01-29T08:35:56.838Z - debug: Socket disconnected: transport close 14 (NOT YET SET)

2016-01-29T08:40:00.005Z - debug: Socket disconnected: transport close 15 (NOT YET SET)

2016-01-29T08:45:25.444Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-01-29T08:45:25.646Z - debug: Socket disconnected: transport close 16 (NOT YET SET)


 
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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5761781115ba656_Use_leveldown-mobile_also_on_desktop__vjrantal/thali09_LGE-Nexus 5.md)





#### Test 558973767bac5c9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-13T13:55:54.259Z - info: listening on *:3000

2016-01-13T13:55:55.607Z - debug: Device presented: UNITTEST-0.5892447698106175 (android) unittest socket:0

2016-01-13T13:55:55.710Z - debug: Device presented: UNITTEST-0.09787621166615967 (android) unittest socket:1

2016-01-13T13:55:55.715Z - info: Required number of android devices presented (2)

2016-01-13T13:55:55.718Z - info: Starting unit test run for platform: android

2016-01-13T13:55:56.116Z - info: Running test: multiplex can send data

2016-01-13T13:55:56.287Z - debug: Device presented: UNITTEST-0.08137123695908977 (ios) unittest socket:2

2016-01-13T13:55:56.422Z - info: Running test: basic

2016-01-13T13:55:56.507Z - info: Running test: another

2016-01-13T13:55:56.598Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-13T13:55:56.618Z - debug: Device presented: UNITTEST-0.4484029113283746 (android) unittest socket:3

2016-01-13T13:55:56.619Z - info: Discarding surplus device: UNITTEST-0.4484029113283746

2016-01-13T13:55:56.765Z - debug: Device presented: UNITTEST-0.8317381896937186 (android) unittest socket:4

2016-01-13T13:55:56.767Z - info: Discarding surplus device: UNITTEST-0.8317381896937186

2016-01-13T13:55:56.801Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-13T13:55:56.826Z - debug: Device presented: UNITTEST-0.03604546751864657 (ios) unittest socket:5

2016-01-13T13:55:56.827Z - info: Required number of ios devices presented (2)

2016-01-13T13:55:56.828Z - info: Starting unit test run for platform: ios

2016-01-13T13:55:56.964Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-13T13:55:57.019Z - info: Running test: failed to get mobile documents path

2016-01-13T13:55:57.080Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-13T13:55:57.163Z - info: Running test: #init should register the networkChanged event

2016-01-13T13:55:57.171Z - debug: Device presented: UNITTEST-0.07056146580652889 (android) unittest socket:6

2016-01-13T13:55:57.172Z - info: Discarding surplus device: UNITTEST-0.07056146580652889

2016-01-13T13:55:57.244Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-13T13:55:57.293Z - debug: Device presented: UNITTEST-0.2988918931935862 (ios) unittest socket:7

2016-01-13T13:55:57.294Z - info: Discarding surplus device: UNITTEST-0.2988918931935862

2016-01-13T13:55:57.304Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-13T13:55:57.384Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-13T13:55:57.466Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-13T13:55:57.547Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.4484029113283746)

2016-01-13T13:55:57.566Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-13T13:55:57.578Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.8317381896937186)

2016-01-13T13:55:57.597Z - debug: Device presented: UNITTEST-0.2878818174602965 (android) unittest socket:8

2016-01-13T13:55:57.598Z - info: Discarding surplus device: UNITTEST-0.2878818174602965

2016-01-13T13:55:57.632Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-13T13:55:57.656Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.07056146580652889)

2016-01-13T13:55:57.722Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-13T13:55:57.804Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-13T13:55:57.883Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-13T13:55:57.954Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-13T13:55:58.036Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-13T13:55:58.113Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-13T13:55:58.208Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-13T13:55:58.258Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-13T13:55:58.300Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-13T13:55:58.342Z - debug: Device presented: UNITTEST-0.423378345847788 (android) unittest socket:9

2016-01-13T13:55:58.343Z - info: Discarding surplus device: UNITTEST-0.423378345847788

2016-01-13T13:55:58.572Z - debug: Device presented: UNITTEST-0.733160752934076 (ios) unittest socket:10

2016-01-13T13:55:58.573Z - info: Discarding surplus device: UNITTEST-0.733160752934076

2016-01-13T13:55:58.772Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.2878818174602965)

2016-01-13T13:55:58.811Z - info: Running test: multiplex can send data

2016-01-13T13:55:59.491Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.423378345847788)

2016-01-13T13:55:59.651Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.2988918931935862)

2016-01-13T13:56:00.893Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-13T13:56:01.311Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-13T13:56:01.757Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-13T13:56:01.798Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.733160752934076)

2016-01-13T13:56:02.217Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-13T13:56:04.402Z - debug: Device presented: UNITTEST-0.43105774185810053 (android) unittest socket:11

2016-01-13T13:56:04.404Z - info: Discarding surplus device: UNITTEST-0.43105774185810053

2016-01-13T13:56:05.012Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.43105774185810053)

2016-01-13T13:56:13.302Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-13T14:18:32.119Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.03604546751864657)

2016-01-13T14:18:32.165Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.08137123695908977)

2016-01-13T14:24:07.485Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.5892447698106175)

2016-01-13T14:24:09.846Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.09787621166615967)


 
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
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/558973767bac5c9_Update_to_jxcore-cordova_0_1_0__vjrantal/thali09_LGE-Nexus 5.md)





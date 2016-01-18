#### Test 563583788793eb6 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-18T16:27:38.970Z - info: listening on *:3000

2016-01-18T16:27:40.373Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:0

2016-01-18T16:27:40.535Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-01-18T16:27:41.481Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-01-18T16:27:41.483Z - info: Required number of android devices presented (2)

2016-01-18T16:27:41.486Z - info: Starting unit test run for platform: android

2016-01-18T16:27:41.507Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:3

2016-01-18T16:27:41.510Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-18T16:27:41.785Z - info: Running on android test: multiplex can send data

2016-01-18T16:27:42.002Z - info: Running on android test: basic

2016-01-18T16:27:42.021Z - debug: Socket disconnected: transport close 3 (LGE-Nexus 5)

2016-01-18T16:27:42.039Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-01-18T16:27:42.040Z - info: Required number of ios devices presented (2)

2016-01-18T16:27:42.042Z - info: Starting unit test run for platform: ios

2016-01-18T16:27:42.099Z - info: Running on android test: another

2016-01-18T16:27:42.223Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-18T16:27:42.263Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:5

2016-01-18T16:27:42.264Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-18T16:27:42.367Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:6

2016-01-18T16:27:42.368Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-18T16:27:42.416Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-18T16:27:42.460Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:7

2016-01-18T16:27:42.461Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-18T16:27:42.580Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-18T16:27:42.650Z - info: Running on ios test: multiplex can send data

2016-01-18T16:27:42.663Z - info: Running on android test: failed to get mobile documents path

2016-01-18T16:27:42.722Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-18T16:27:42.789Z - info: Running on android test: #init should register the networkChanged event

2016-01-18T16:27:42.842Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-18T16:27:42.891Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-18T16:27:42.961Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-18T16:27:43.022Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-18T16:27:43.085Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-18T16:27:43.137Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-18T16:27:43.187Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-18T16:27:43.251Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-18T16:27:43.293Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F)

2016-01-18T16:27:43.320Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F)

2016-01-18T16:27:43.328Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-18T16:27:43.456Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-18T16:27:43.566Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-18T16:27:43.576Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-01-18T16:27:43.577Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-18T16:27:43.651Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-18T16:27:43.738Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-18T16:27:43.804Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-18T16:27:43.862Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-18T16:27:44.228Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:9

2016-01-18T16:27:44.229Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-18T16:27:44.265Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:10

2016-01-18T16:27:44.266Z - info: Discarding surplus device: LGE-LG-D722

2016-01-18T16:27:44.345Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-01-18T16:27:44.814Z - debug: Socket disconnected: transport close 7 (Apple-Iphone6-1)

2016-01-18T16:27:45.074Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-18T16:27:45.412Z - debug: Socket disconnected: transport close 10 (LGE-LG-D722)

2016-01-18T16:27:45.584Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-18T16:27:46.145Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-18T16:27:46.737Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-18T16:27:46.852Z - info: Running on android test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-18T16:27:46.924Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-18T16:27:46.971Z - info: Test run on android complete

2016-01-18T16:27:46.975Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-18T16:27:46.976Z - info: PLATFORM: android

2016-01-18T16:27:46.977Z - info: RESULT: PASS

2016-01-18T16:27:46.979Z - info: 30 of 30 tests completed

2016-01-18T16:27:46.980Z - info: 30/30 passed (0 failures)

2016-01-18T16:27:46.981Z - info: --- Test Details ---


2016-01-18T16:27:46.982Z - info: multiplex can send data - pass

2016-01-18T16:27:46.983Z - info: basic - pass

2016-01-18T16:27:46.984Z - info: another - pass

2016-01-18T16:27:46.985Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-18T16:27:46.986Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-18T16:27:46.987Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-18T16:27:46.988Z - info: failed to get mobile documents path - pass
2016-01-18T16:27:46.989Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-18T16:27:46.990Z - info: #init should register the networkChanged event - pass

2016-01-18T16:27:46.991Z - info: #startBroadcasting should throw on null device name - pass

2016-01-18T16:27:46.992Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-18T16:27:46.993Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-18T16:27:46.994Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-18T16:27:46.995Z - info: #startBroadcasting should throw on negative port - pass

2016-01-18T16:27:46.998Z - info: #startBroadcasting should throw on too large port - pass

2016-01-18T16:27:46.999Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-18T16:27:47.001Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-18T16:27:47.002Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-18T16:27:47.003Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-18T16:27:47.004Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-18T16:27:47.005Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-18T16:27:47.006Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-18T16:27:47.007Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-18T16:27:47.008Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-18T16:27:47.009Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-18T16:27:47.010Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-18T16:27:47.011Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-18T16:27:47.012Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-18T16:27:47.013Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass

2016-01-18T16:27:47.014Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-18T16:27:47.015Z - info: 

-== END ==-

2016-01-18T16:27:47.248Z - debug: Socket disconnected: transport close 9 (Apple-Iphone5-1)

2016-01-18T16:29:11.983Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-D855)

2016-01-18T16:29:11.989Z - debug: Socket disconnected: ping timeout 2 (LGE-LG-H815)

2016-01-18T16:40:00.466Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-01-18T16:40:00.517Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5s-1)


 
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
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/563583788793eb6_Update_to_jxcore-cordova_0_1_0__vjrantal/thali09_LGE-Nexus 5.md)





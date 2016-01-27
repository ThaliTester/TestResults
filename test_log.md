#### Test 57348078846ce9d Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-27T13:59:55.987Z - info: listening on *:3000

2016-01-27T13:59:56.383Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:0

2016-01-27T13:59:56.413Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-01-27T13:59:56.417Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:1

2016-01-27T13:59:56.420Z - info: Required number of android devices presented (2)

2016-01-27T13:59:56.426Z - info: Starting unit test run for platform: android

2016-01-27T13:59:56.752Z - info: Running on android test: multiplex can send data

2016-01-27T13:59:56.987Z - info: Running on android test: enqueue and run in order

2016-01-27T13:59:57.022Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-01-27T13:59:57.023Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-27T13:59:57.291Z - info: Running on android test: basic

2016-01-27T13:59:57.397Z - info: Running on android test: another

2016-01-27T13:59:57.480Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-27T13:59:57.628Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-01-27T13:59:57.629Z - info: Required number of ios devices presented (2)

2016-01-27T13:59:57.631Z - info: Starting unit test run for platform: ios

2016-01-27T13:59:57.845Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-01-27T13:59:57.846Z - info: Discarding surplus device: LGE-LG-H815

2016-01-27T13:59:57.880Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-27T13:59:57.928Z - debug: Device presented: LGE-LG-D802 (android) unittest socket:6

2016-01-27T13:59:57.929Z - info: Discarding surplus device: LGE-LG-D802

2016-01-27T13:59:58.128Z - debug: Socket disconnected: transport close 3 (samsung-SM-G900F)

2016-01-27T13:59:58.152Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-27T13:59:58.222Z - info: Running on android test: failed to get mobile documents path

2016-01-27T13:59:58.272Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-27T13:59:58.336Z - info: Running on android test: #init should register the networkChanged event

2016-01-27T13:59:58.379Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-27T13:59:58.448Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-27T13:59:58.513Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-27T13:59:58.548Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:7

2016-01-27T13:59:58.552Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-27T13:59:58.568Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-27T13:59:58.632Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-27T13:59:58.695Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-27T13:59:58.719Z - debug: Socket disconnected: transport close 6 (LGE-LG-D802)

2016-01-27T13:59:58.756Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-27T13:59:58.781Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:8

2016-01-27T13:59:58.782Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-27T13:59:58.836Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-27T13:59:58.864Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-01-27T13:59:58.922Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-27T13:59:59.011Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-27T13:59:59.093Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-27T13:59:59.147Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-27T13:59:59.194Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-27T13:59:59.213Z - debug: Socket disconnected: transport close 7 (samsung-SM-N910C)

2016-01-27T13:59:59.238Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-27T13:59:59.299Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-27T13:59:59.555Z - info: Running on ios test: multiplex can send data

2016-01-27T13:59:59.650Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F)

2016-01-27T14:00:00.237Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:9

2016-01-27T14:00:00.238Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-01-27T14:00:00.382Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-27T14:00:00.619Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:10

2016-01-27T14:00:00.620Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-27T14:00:00.721Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-27T14:00:01.035Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-27T14:00:01.067Z - debug: Socket disconnected: transport close 10 (LGE-Nexus 5)

2016-01-27T14:00:01.446Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-27T14:00:01.622Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-27T14:00:02.237Z - info: Running on android test: messages with invalid location or USN should be ignored

2016-01-27T14:00:02.299Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-27T14:00:02.351Z - info: Running on android test: #start should fail if called twice in a row

2016-01-27T14:00:02.408Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-27T14:00:02.468Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-01-27T14:00:02.590Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-27T14:00:02.702Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-27T14:00:02.732Z - debug: Socket disconnected: transport close 9 (Apple-Iphone5s-1)

2016-01-27T14:00:02.757Z - info: Running on android test: #startListeningForAdvertisements can be called multiple times in a row

2016-01-27T14:00:02.845Z - info: Running on android test: #stopListeningForAdvertisements can be called multiple times in a row

2016-01-27T14:00:02.891Z - info: Running on android test: #stopAdvertisingAndListening can be called multiple times in a row

2016-01-27T14:00:02.959Z - info: Running on android test: functions are run from a queue in the right order

2016-01-27T14:00:03.029Z - info: Test run on android complete

2016-01-27T14:00:03.033Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-27T14:00:03.034Z - info: PLATFORM: android

2016-01-27T14:00:03.036Z - info: RESULT: PASS

2016-01-27T14:00:03.037Z - info: 41 of 41 tests completed

2016-01-27T14:00:03.038Z - info: 41/41 passed (0 failures)

2016-01-27T14:00:03.039Z - info: --- Test Details ---



2016-01-27T14:00:03.040Z - info: multiplex can send data - pass

2016-01-27T14:00:03.041Z - info: enqueue and run in order - pass

2016-01-27T14:00:03.042Z - info: basic - pass

2016-01-27T14:00:03.043Z - info: another - pass

2016-01-27T14:00:03.044Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-27T14:00:03.045Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-27T14:00:03.046Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-27T14:00:03.047Z - info: failed to get mobile documents path - pass

2016-01-27T14:00:03.048Z - info: #init should register the peerAvailabilityChanged event - pass
2016-01-27T14:00:03.049Z - info: #init should register the networkChanged event - pass

2016-01-27T14:00:03.050Z - info: #startBroadcasting should throw on null device name - pass

2016-01-27T14:00:03.051Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-27T14:00:03.052Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-27T14:00:03.054Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-27T14:00:03.055Z - info: #startBroadcasting should throw on negative port - pass

2016-01-27T14:00:03.056Z - info: #startBroadcasting should throw on too large port - pass

2016-01-27T14:00:03.057Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-27T14:00:03.062Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-27T14:00:03.063Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-27T14:00:03.063Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-27T14:00:03.064Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-27T14:00:03.066Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-27T14:00:03.067Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-27T14:00:03.076Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-27T14:00:03.077Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-27T14:00:03.078Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-27T14:00:03.079Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-27T14:00:03.080Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-27T14:00:03.081Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass
2016-01-27T14:00:03.082Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-27T14:00:03.083Z - info: messages with invalid location or USN should be ignored - pass

2016-01-27T14:00:03.084Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-27T14:00:03.085Z - info: #start should fail if called twice in a row - pass
2016-01-27T14:00:03.086Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-01-27T14:00:03.087Z - info: #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-01-27T14:00:03.088Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-01-27T14:00:03.089Z - info: #stop can be called multiple times in a row - pass
2016-01-27T14:00:03.090Z - info: #startListeningForAdvertisements can be called multiple times in a row - pass

2016-01-27T14:00:03.094Z - info: #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-01-27T14:00:03.095Z - info: #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-01-27T14:00:03.096Z - info: functions are run from a queue in the right order - pass

2016-01-27T14:00:03.097Z - info: 

-== END ==-

2016-01-27T14:00:05.804Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:11

2016-01-27T14:00:05.805Z - info: Discarding surplus device: LGE-LG-D855

2016-01-27T14:00:06.417Z - debug: Socket disconnected: transport close 11 (LGE-LG-D855)

2016-01-27T14:01:24.744Z - debug: Socket disconnected: ping timeout 4 (Apple-Iphone5-1)

2016-01-27T14:01:28.043Z - debug: Socket disconnected: ping timeout 1 (LGE-LG-D722)

2016-01-27T14:01:28.047Z - debug: Socket disconnected: ping timeout 0 (motorola-Nexus 6)

2016-01-27T14:12:07.064Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57348078846ce9d_More_Wifi_infrastructure_features_vjrantal/thali09_LGE-Nexus 5.md)





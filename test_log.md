#### Test 564496600f5d794 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-21T10:05:44.672Z - info: listening on *:3000

2016-01-21T10:05:45.178Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:0

2016-01-21T10:05:45.551Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-01-21T10:05:45.601Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:3

2016-01-21T10:05:45.603Z - info: Required number of android devices presented (2)

2016-01-21T10:05:45.607Z - info: Starting unit test run for platform: android

2016-01-21T10:05:45.669Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:2

2016-01-21T10:05:45.670Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-21T10:05:46.015Z - info: Running on android test: multiplex can send data

2016-01-21T10:05:46.084Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-01-21T10:05:46.085Z - info: Required number of ios devices presented (2)

2016-01-21T10:05:46.087Z - info: Starting unit test run for platform: ios

2016-01-21T10:05:46.399Z - info: Running on ios test: multiplex can send data

2016-01-21T10:05:46.728Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-01-21T10:05:46.729Z - info: Discarding surplus device: LGE-LG-H815

2016-01-21T10:05:46.744Z - info: Running on android test: basic

2016-01-21T10:05:46.858Z - debug: Socket disconnected: transport close 2 (samsung-SM-G900F)

2016-01-21T10:05:46.875Z - info: Running on android test: another

2016-01-21T10:05:46.963Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:6

2016-01-21T10:05:46.964Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-21T10:05:46.974Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-21T10:05:47.202Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-21T10:05:47.309Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-21T10:05:47.361Z - info: Running on android test: failed to get mobile documents path

2016-01-21T10:05:47.416Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-21T10:05:47.495Z - info: Running on android test: #init should register the networkChanged event

2016-01-21T10:05:47.530Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:7

2016-01-21T10:05:47.531Z - info: Discarding surplus device: HTC-HTC One M8s

2016-01-21T10:05:47.554Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-21T10:05:47.610Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-21T10:05:47.707Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-01-21T10:05:47.720Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-21T10:05:47.789Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-21T10:05:47.843Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-21T10:05:47.882Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-21T10:05:47.920Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-21T10:05:47.979Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F)

2016-01-21T10:05:47.986Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-21T10:05:48.042Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-21T10:05:48.127Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-21T10:05:48.191Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-21T10:05:48.269Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-21T10:05:48.310Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-21T10:05:48.346Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-21T10:05:48.380Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-21T10:05:48.591Z - debug: Socket disconnected: transport close 7 (HTC-HTC One M8s)

2016-01-21T10:05:49.308Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:8

2016-01-21T10:05:49.309Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-21T10:05:49.370Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:9

2016-01-21T10:05:49.371Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-21T10:05:49.805Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:10

2016-01-21T10:05:49.806Z - info: Discarding surplus device: LGE-LG-D722

2016-01-21T10:05:50.341Z - debug: Socket disconnected: transport close 8 (HTC-HTC Desire 820)

2016-01-21T10:05:50.907Z - debug: Socket disconnected: transport close 10 (LGE-LG-D722)

2016-01-21T10:05:51.056Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-21T10:05:51.582Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-21T10:05:51.787Z - debug: Socket disconnected: transport close 9 (Apple-Iphone6-1)

2016-01-21T10:05:52.051Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-21T10:05:52.543Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-21T10:05:52.966Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-21T10:05:53.052Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:11

2016-01-21T10:05:53.054Z - info: Discarding surplus device: LGE-LG-D855

2016-01-21T10:05:53.259Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-21T10:05:53.336Z - info: Running on android test: #start should fail if called twice in a row

2016-01-21T10:05:53.381Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-21T10:05:53.440Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-21T10:05:53.545Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-21T10:05:53.585Z - info: Test run on android complete

2016-01-21T10:05:53.587Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-21T10:05:53.588Z - info: PLATFORM: android

2016-01-21T10:05:53.590Z - info: RESULT: PASS

2016-01-21T10:05:53.593Z - info: 34 of 34 tests completed

2016-01-21T10:05:53.594Z - info: 34/34 passed (0 failures)

2016-01-21T10:05:53.596Z - info: --- Test Details ---



2016-01-21T10:05:53.597Z - info: multiplex can send data - pass

2016-01-21T10:05:53.598Z - info: basic - pass

2016-01-21T10:05:53.599Z - info: another - pass

2016-01-21T10:05:53.600Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-21T10:05:53.601Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-21T10:05:53.602Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-21T10:05:53.603Z - info: failed to get mobile documents path - pass

2016-01-21T10:05:53.604Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-21T10:05:53.605Z - info: #init should register the networkChanged event - pass

2016-01-21T10:05:53.606Z - info: #startBroadcasting should throw on null device name - pass

2016-01-21T10:05:53.607Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-21T10:05:53.608Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-21T10:05:53.609Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-21T10:05:53.611Z - info: #startBroadcasting should throw on negative port - pass

2016-01-21T10:05:53.612Z - info: #startBroadcasting should throw on too large port - pass

2016-01-21T10:05:53.613Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-21T10:05:53.614Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-21T10:05:53.615Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-21T10:05:53.616Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-21T10:05:53.617Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-21T10:05:53.618Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-21T10:05:53.619Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-21T10:05:53.623Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-21T10:05:53.624Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-21T10:05:53.625Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-21T10:05:53.626Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-21T10:05:53.627Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-21T10:05:53.628Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-21T10:05:53.629Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-21T10:05:53.631Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-21T10:05:53.631Z - info: #start should fail if called twice in a row - pass

2016-01-21T10:05:53.633Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-01-21T10:05:53.633Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-01-21T10:05:53.635Z - info: #stop can be called multiple times in a row - pass

2016-01-21T10:05:53.636Z - info: 

-== END ==-

2016-01-21T10:05:53.777Z - debug: Socket disconnected: transport close 11 (LGE-LG-D855)

2016-01-21T10:07:18.599Z - debug: Socket disconnected: ping timeout 0 (samsung-SM-N910C)

2016-01-21T10:07:18.605Z - debug: Socket disconnected: ping timeout 3 (LGE-Nexus 5)

2016-01-21T10:18:14.166Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-01-21T10:18:14.198Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/564496600f5d794_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali09_LGE-Nexus 5.md)





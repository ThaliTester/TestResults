#### Test 5644966031ce140 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-19T12:06:30.040Z - info: listening on *:3000

2016-01-19T12:06:31.001Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:0

2016-01-19T12:06:31.106Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-01-19T12:06:31.159Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-01-19T12:06:31.162Z - info: Required number of ios devices presented (2)

2016-01-19T12:06:31.166Z - info: Starting unit test run for platform: ios

2016-01-19T12:06:31.405Z - info: Running on ios test: multiplex can send data

2016-01-19T12:06:31.599Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:3

2016-01-19T12:06:31.600Z - info: Required number of android devices presented (2)

2016-01-19T12:06:31.602Z - info: Starting unit test run for platform: android

2016-01-19T12:06:31.621Z - info: Running on ios test: basic

2016-01-19T12:06:31.635Z - debug: Device presented: motorola-XT1072 (android) unittest socket:4

2016-01-19T12:06:31.636Z - info: Discarding surplus device: motorola-XT1072

2016-01-19T12:06:31.677Z - info: Running on ios test: another

2016-01-19T12:06:31.723Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-19T12:06:31.983Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-19T12:06:32.067Z - info: Running on android test: multiplex can send data

2016-01-19T12:06:32.202Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-19T12:06:32.494Z - debug: Socket disconnected: transport close 4 (motorola-XT1072)

2016-01-19T12:06:32.652Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-01-19T12:06:32.655Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-01-19T12:06:32.887Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:6

2016-01-19T12:06:32.888Z - info: Discarding surplus device: LGE-LG-H815

2016-01-19T12:06:33.012Z - info: Running on android test: basic

2016-01-19T12:06:33.100Z - info: Running on android test: another

2016-01-19T12:06:33.126Z - info: Running on ios test: failed to get mobile documents path

2016-01-19T12:06:33.223Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-19T12:06:33.375Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-19T12:06:33.429Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-19T12:06:33.441Z - info: Running on ios test: #init should register the networkChanged event

2016-01-19T12:06:33.516Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-19T12:06:33.574Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-19T12:06:33.606Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-19T12:06:33.633Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:7

2016-01-19T12:06:33.634Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-19T12:06:33.645Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-19T12:06:33.749Z - info: Running on android test: failed to get mobile documents path

2016-01-19T12:06:33.764Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-19T12:06:33.808Z - debug: Socket disconnected: transport close 6 (LGE-LG-H815)

2016-01-19T12:06:33.844Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-19T12:06:33.899Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-19T12:06:33.946Z - info: Running on android test: #init should register the networkChanged event

2016-01-19T12:06:33.978Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-19T12:06:34.005Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-19T12:06:34.038Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-19T12:06:34.070Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-19T12:06:34.091Z - debug: Socket disconnected: transport close 7 (LGE-Nexus 5)

2016-01-19T12:06:34.097Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-19T12:06:34.126Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-19T12:06:34.157Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-19T12:06:34.215Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-19T12:06:34.225Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-19T12:06:34.271Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-19T12:06:34.304Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-19T12:06:34.335Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-19T12:06:34.359Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-19T12:06:34.388Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-19T12:06:34.427Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-19T12:06:34.440Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-19T12:06:34.507Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-19T12:06:34.554Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-19T12:06:34.562Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-19T12:06:34.595Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:8

2016-01-19T12:06:34.596Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-19T12:06:34.627Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-19T12:06:34.695Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-19T12:06:34.806Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-19T12:06:34.871Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-19T12:06:34.912Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-19T12:06:34.942Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-19T12:06:34.993Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-01-19T12:06:34.994Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-19T12:06:35.062Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-19T12:06:35.226Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:10

2016-01-19T12:06:35.227Z - info: Discarding surplus device: LGE-LG-D722

2016-01-19T12:06:35.233Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:11

2016-01-19T12:06:35.234Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-01-19T12:06:35.405Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-19T12:06:35.462Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5s-1)

2016-01-19T12:06:35.557Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-19T12:06:35.629Z - debug: Socket disconnected: transport close 8 (HTC-HTC Desire 820)

2016-01-19T12:06:36.006Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-01-19T12:06:36.216Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:12

2016-01-19T12:06:36.216Z - info: Discarding surplus device: LGE-LG-D855

2016-01-19T12:06:36.395Z - debug: Socket disconnected: transport close 10 (LGE-LG-D722)

2016-01-19T12:06:36.566Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-19T12:06:37.044Z - debug: Socket disconnected: transport close 12 (LGE-LG-D855)

2016-01-19T12:06:37.743Z - debug: Socket disconnected: transport close 11 (Apple-IpadAir2-1)

2016-01-19T12:06:40.865Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-19T12:06:41.942Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-19T12:06:42.530Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-19T12:06:43.010Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-19T12:06:43.602Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-19T12:06:44.651Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-19T12:06:45.018Z - info: Running on android test: #start should fail if called twice in a row

2016-01-19T12:06:45.179Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-19T12:06:45.415Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-19T12:06:45.605Z - info: Test run on android complete

2016-01-19T12:06:45.608Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-19T12:06:45.609Z - info: PLATFORM: android

2016-01-19T12:06:45.610Z - info: RESULT: PASS

2016-01-19T12:06:45.611Z - info: 33 of 33 tests completed

2016-01-19T12:06:45.613Z - info: 33/33 passed (0 failures)

2016-01-19T12:06:45.614Z - info: --- Test Details ---



2016-01-19T12:06:45.615Z - info: multiplex can send data - pass

2016-01-19T12:06:45.616Z - info: basic - pass

2016-01-19T12:06:45.617Z - info: another - pass

2016-01-19T12:06:45.618Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-19T12:06:45.619Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-19T12:06:45.620Z - info: failed to extract public key because of corrupt pkcs12 file - pass
2016-01-19T12:06:45.621Z - info: failed to get mobile documents path - pass

2016-01-19T12:06:45.622Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-19T12:06:45.622Z - info: #init should register the networkChanged event - pass
2016-01-19T12:06:45.623Z - info: #startBroadcasting should throw on null device name - pass
2016-01-19T12:06:45.624Z - info: #startBroadcasting should throw on empty string device name - pass
2016-01-19T12:06:45.625Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-19T12:06:45.626Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-19T12:06:45.630Z - info: #startBroadcasting should throw on negative port - pass
2016-01-19T12:06:45.631Z - info: #startBroadcasting should throw on too large port - pass
2016-01-19T12:06:45.632Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-19T12:06:45.633Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-19T12:06:45.634Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-19T12:06:45.634Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-19T12:06:45.635Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-19T12:06:45.636Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-19T12:06:45.637Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-19T12:06:45.638Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-19T12:06:45.639Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
2016-01-19T12:06:45.640Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-19T12:06:45.641Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-19T12:06:45.642Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-19T12:06:45.645Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass
2016-01-19T12:06:45.649Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-01-19T12:06:45.649Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-19T12:06:45.651Z - info: #start should fail if called twice in a row - pass
2016-01-19T12:06:45.651Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-01-19T12:06:45.652Z - info: #stop can be called multiple times in a row - pass
2016-01-19T12:06:45.653Z - info: 

-== END ==-

2016-01-19T12:06:50.149Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-19T12:07:36.335Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-19T12:07:43.084Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-19T12:08:10.536Z - debug: Socket disconnected: ping timeout 0 (samsung-SM-G900F)

2016-01-19T12:08:10.616Z - debug: Socket disconnected: ping timeout 3 (samsung-SM-N910C)

2016-01-19T12:08:18.123Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-19T12:08:27.271Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-19T12:08:31.513Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-19T12:08:57.284Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-19T12:09:33.785Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-19T12:09:36.230Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-01-19T12:09:36.798Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)


 
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
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/iOS_Iphone5s-1.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5644966031ce140_Wifi_infrastructure_work_vjrantal/thali09_LGE-Nexus 5.md)





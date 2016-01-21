#### Test 56672827039a409 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-21T17:19:05.723Z - info: listening on *:3000

2016-01-21T17:19:06.354Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:0

2016-01-21T17:19:06.366Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:1

2016-01-21T17:19:06.368Z - info: Required number of android devices presented (2)

2016-01-21T17:19:06.372Z - info: Starting unit test run for platform: android

2016-01-21T17:19:06.484Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-01-21T17:19:06.696Z - info: Running on android test: multiplex can send data

2016-01-21T17:19:06.940Z - info: Running on android test: enqueue and run in order

2016-01-21T17:19:07.282Z - info: Running on android test: basic

2016-01-21T17:19:07.366Z - info: Running on android test: another

2016-01-21T17:19:07.406Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-21T17:19:07.773Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-01-21T17:19:07.774Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-21T17:19:07.781Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-21T17:19:08.007Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-01-21T17:19:08.008Z - info: Required number of ios devices presented (2)

2016-01-21T17:19:08.010Z - info: Starting unit test run for platform: ios

2016-01-21T17:19:08.058Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-21T17:19:08.115Z - info: Running on android test: failed to get mobile documents path

2016-01-21T17:19:08.157Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-21T17:19:08.169Z - info: Running on ios test: multiplex can send data

2016-01-21T17:19:08.221Z - info: Running on android test: #init should register the networkChanged event

2016-01-21T17:19:08.285Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-21T17:19:08.355Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-21T17:19:08.407Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-21T17:19:08.464Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-21T17:19:08.507Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-21T17:19:08.565Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-21T17:19:08.615Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-21T17:19:08.665Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-21T17:19:08.717Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-21T17:19:08.803Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-21T17:19:08.890Z - debug: Socket disconnected: transport close 3 (samsung-SM-G900F)

2016-01-21T17:19:08.911Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-21T17:19:08.984Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-21T17:19:09.070Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-21T17:19:09.120Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-21T17:19:09.191Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-21T17:19:09.282Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:5

2016-01-21T17:19:09.283Z - info: Discarding surplus device: LGE-LG-D855

2016-01-21T17:19:09.522Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:6

2016-01-21T17:19:09.523Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-21T17:19:09.807Z - debug: Socket disconnected: transport close 5 (LGE-LG-D855)

2016-01-21T17:19:10.019Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:7

2016-01-21T17:19:10.020Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-21T17:19:10.192Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-01-21T17:19:10.193Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-21T17:19:10.238Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-21T17:19:10.573Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:9

2016-01-21T17:19:10.574Z - info: Discarding surplus device: LGE-LG-H815

2016-01-21T17:19:10.604Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:10

2016-01-21T17:19:10.605Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-21T17:19:10.779Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-21T17:19:10.894Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-01-21T17:19:11.034Z - debug: Socket disconnected: transport close 10 (LGE-Nexus 5)

2016-01-21T17:19:11.141Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-21T17:19:11.593Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-21T17:19:11.680Z - debug: Socket disconnected: transport close 9 (LGE-LG-H815)

2016-01-21T17:19:11.907Z - info: Running on android test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-21T17:19:11.918Z - debug: Socket disconnected: transport close 6 (Apple-Iphone6-1)

2016-01-21T17:19:12.076Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-21T17:19:12.292Z - info: Test run on android complete

2016-01-21T17:19:12.294Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-21T17:19:12.296Z - info: PLATFORM: android

2016-01-21T17:19:12.297Z - info: RESULT: PASS

2016-01-21T17:19:12.298Z - info: 31 of 31 tests completed

2016-01-21T17:19:12.300Z - info: 31/31 passed (0 failures)
2016-01-21T17:19:12.301Z - info: --- Test Details ---



2016-01-21T17:19:12.302Z - info: multiplex can send data - pass

2016-01-21T17:19:12.303Z - info: enqueue and run in order - pass

2016-01-21T17:19:12.305Z - info: basic - pass

2016-01-21T17:19:12.306Z - info: another - pass

2016-01-21T17:19:12.307Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-21T17:19:12.308Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-21T17:19:12.309Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-21T17:19:12.310Z - info: failed to get mobile documents path - pass

2016-01-21T17:19:12.311Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-21T17:19:12.312Z - info: #init should register the networkChanged event - pass

2016-01-21T17:19:12.314Z - info: #startBroadcasting should throw on null device name - pass

2016-01-21T17:19:12.315Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-21T17:19:12.315Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-21T17:19:12.317Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-21T17:19:12.318Z - info: #startBroadcasting should throw on negative port - pass

2016-01-21T17:19:12.319Z - info: #startBroadcasting should throw on too large port - pass

2016-01-21T17:19:12.320Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-21T17:19:12.321Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-21T17:19:12.326Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-21T17:19:12.328Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-21T17:19:12.329Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-21T17:19:12.331Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-21T17:19:12.332Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-21T17:19:12.333Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-21T17:19:12.334Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-21T17:19:12.335Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-21T17:19:12.336Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-21T17:19:12.336Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-21T17:19:12.337Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-21T17:19:12.339Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass

2016-01-21T17:19:12.340Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-21T17:19:12.340Z - info: 

-== END ==-

2016-01-21T17:19:12.948Z - debug: Socket disconnected: transport close 7 (Apple-Iphone5-1)

2016-01-21T17:20:37.286Z - debug: Socket disconnected: ping timeout 1 (LGE-LG-D722)

2016-01-21T17:20:37.305Z - debug: Socket disconnected: ping timeout 0 (samsung-SM-G900F)

2016-01-21T17:31:07.249Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-01-21T17:31:07.305Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Android task is completed. [FAILED]
```
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali03_LGE-LG-D855.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56672827039a409__472_Promise_Queue_yaronyg/thali09_LGE-Nexus 5.md)





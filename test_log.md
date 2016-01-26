#### Test 5667282762e056f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-26T17:59:38.003Z - info: listening on *:3000

2016-01-26T17:59:38.431Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:0

2016-01-26T17:59:38.472Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-01-26T17:59:38.475Z - info: Required number of android devices presented (2)

2016-01-26T17:59:38.478Z - info: Starting unit test run for platform: android

2016-01-26T17:59:38.687Z - info: Running on android test: multiplex can send data

2016-01-26T17:59:39.230Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:2

2016-01-26T17:59:39.232Z - info: Discarding surplus device: motorola-Nexus 6

2016-01-26T17:59:39.325Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-01-26T17:59:39.327Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-26T17:59:39.699Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:4

2016-01-26T17:59:39.700Z - info: Discarding surplus device: LGE-LG-D722

2016-01-26T17:59:39.739Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-01-26T17:59:39.740Z - info: Discarding surplus device: LGE-LG-H815

2016-01-26T17:59:39.867Z - debug: Socket disconnected: transport close 2 (motorola-Nexus 6)

2016-01-26T17:59:40.123Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:6

2016-01-26T17:59:40.124Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-26T17:59:40.704Z - debug: Socket disconnected: transport close 3 (samsung-SM-G900F)

2016-01-26T17:59:40.786Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-01-26T17:59:40.839Z - debug: Socket disconnected: transport close 4 (LGE-LG-D722)

2016-01-26T17:59:40.954Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:7

2016-01-26T17:59:41.216Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F)

2016-01-26T17:59:41.719Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:8

2016-01-26T17:59:41.720Z - info: Required number of ios devices presented (2)

2016-01-26T17:59:41.721Z - info: Starting unit test run for platform: ios

2016-01-26T17:59:41.976Z - info: Running on ios test: multiplex can send data

2016-01-26T17:59:42.170Z - info: Running on ios test: enqueue and run in order

2016-01-26T17:59:42.231Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:9

2016-01-26T17:59:42.232Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-26T17:59:42.353Z - info: Running on android test: enqueue and run in order

2016-01-26T17:59:42.705Z - info: Running on android test: basic

2016-01-26T17:59:42.811Z - info: Running on android test: another

2016-01-26T17:59:42.853Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-26T17:59:43.028Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:10

2016-01-26T17:59:43.029Z - info: Discarding surplus device: LGE-LG-D855

2016-01-26T17:59:43.129Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-26T17:59:43.298Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-26T17:59:43.365Z - info: Running on android test: failed to get mobile documents path

2016-01-26T17:59:43.406Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-26T17:59:43.451Z - info: Running on android test: #init should register the networkChanged event

2016-01-26T17:59:43.498Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-26T17:59:43.570Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-26T17:59:43.630Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-26T17:59:43.673Z - debug: Socket disconnected: transport close 10 (LGE-LG-D855)

2016-01-26T17:59:43.701Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-26T17:59:43.767Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-26T17:59:43.828Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-26T17:59:43.879Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-26T17:59:43.946Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-26T17:59:44.024Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-26T17:59:44.086Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-26T17:59:44.144Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-26T17:59:44.190Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-26T17:59:44.228Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-26T17:59:44.269Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-26T17:59:44.326Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-26T17:59:45.388Z - debug: Socket disconnected: transport close 9 (Apple-Iphone5-1)

2016-01-26T17:59:45.455Z - info: Running on ios test: basic

2016-01-26T17:59:47.132Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-26T17:59:50.389Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-26T17:59:50.603Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:11

2016-01-26T17:59:50.604Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-26T17:59:50.830Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-26T17:59:51.305Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-26T17:59:51.613Z - info: Running on android test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-26T17:59:51.684Z - debug: Socket disconnected: transport close 11 (samsung-SM-G800F)

2016-01-26T17:59:51.981Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-26T17:59:52.191Z - info: Test run on android complete

2016-01-26T17:59:52.193Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-26T17:59:52.195Z - info: PLATFORM: android

2016-01-26T17:59:52.196Z - info: RESULT: PASS

2016-01-26T17:59:52.198Z - info: 31 of 31 tests completed

2016-01-26T17:59:52.199Z - info: 31/31 passed (0 failures)

2016-01-26T17:59:52.206Z - info: --- Test Details ---



2016-01-26T17:59:52.207Z - info: multiplex can send data - pass

2016-01-26T17:59:52.208Z - info: enqueue and run in order - pass

2016-01-26T17:59:52.209Z - info: basic - pass

2016-01-26T17:59:52.210Z - info: another - pass

2016-01-26T17:59:52.211Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-26T17:59:52.212Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-26T17:59:52.213Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-26T17:59:52.214Z - info: failed to get mobile documents path - pass

2016-01-26T17:59:52.215Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-26T17:59:52.216Z - info: #init should register the networkChanged event - pass

2016-01-26T17:59:52.217Z - info: #startBroadcasting should throw on null device name - pass

2016-01-26T17:59:52.218Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-26T17:59:52.219Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-26T17:59:52.220Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-26T17:59:52.221Z - info: #startBroadcasting should throw on negative port - pass

2016-01-26T17:59:52.222Z - info: #startBroadcasting should throw on too large port - pass

2016-01-26T17:59:52.223Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-26T17:59:52.224Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-26T17:59:52.227Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-26T17:59:52.227Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-26T17:59:52.228Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-26T17:59:52.229Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-26T17:59:52.231Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-26T17:59:52.232Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-26T17:59:52.233Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-26T17:59:52.234Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-26T17:59:52.256Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-26T17:59:52.266Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-26T17:59:52.268Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-26T17:59:52.269Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass

2016-01-26T17:59:52.270Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-26T17:59:52.271Z - info: 

-== END ==-

2016-01-26T17:59:54.717Z - info: Running on ios test: another

2016-01-26T17:59:59.132Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-26T18:00:03.608Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-26T18:00:04.048Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-26T18:00:04.262Z - info: Running on ios test: failed to get mobile documents path

2016-01-26T18:00:04.611Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-26T18:00:04.959Z - info: Running on ios test: #init should register the networkChanged event

2016-01-26T18:00:05.314Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-26T18:00:05.661Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-26T18:00:06.008Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-26T18:00:06.366Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-26T18:00:06.718Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-26T18:00:07.050Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-26T18:00:07.241Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-26T18:00:07.449Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-26T18:00:07.518Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-26T18:00:07.572Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-26T18:00:07.636Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-26T18:00:07.686Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-26T18:00:07.754Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-26T18:00:07.801Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-26T18:00:07.850Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-26T18:00:08.376Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-26T18:00:08.796Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-26T18:00:09.217Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-26T18:00:11.451Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-26T18:00:15.629Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-26T18:00:20.354Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-26T18:00:25.055Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-26T18:00:31.862Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-26T18:00:38.714Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-26T18:00:39.061Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-26T18:00:39.322Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-26T18:01:17.072Z - debug: Socket disconnected: ping timeout 1 (samsung-SM-N910C)

2016-01-26T18:01:17.205Z - debug: Socket disconnected: ping timeout 0 (LGE-Nexus 5)

2016-01-26T18:02:04.564Z - debug: Socket disconnected: ping timeout 8 (Apple-Iphone5s-1)

2016-01-26T18:12:14.069Z - debug: Socket disconnected: transport close 7 (Apple-IpadAir2-1)


 
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
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5667282762e056f__472_Promise_Queue_yaronyg/thali09_LGE-Nexus 5.md)





#### Test 565307121a686b7 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-19T22:10:38.394Z - info: listening on *:3000

2016-01-19T22:10:39.048Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-01-19T22:10:39.620Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-01-19T22:10:39.623Z - info: Required number of ios devices presented (2)

2016-01-19T22:10:39.627Z - info: Starting unit test run for platform: ios

2016-01-19T22:10:39.787Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-01-19T22:10:39.843Z - info: Running on ios test: multiplex can send data

2016-01-19T22:10:39.981Z - info: Running on ios test: basic

2016-01-19T22:10:40.066Z - info: Running on ios test: another

2016-01-19T22:10:40.169Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-19T22:10:40.308Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:3

2016-01-19T22:10:40.310Z - info: Required number of android devices presented (2)

2016-01-19T22:10:40.312Z - info: Starting unit test run for platform: android

2016-01-19T22:10:40.420Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-19T22:10:40.445Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-01-19T22:10:40.448Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-19T22:10:40.584Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-19T22:10:40.618Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:5

2016-01-19T22:10:40.619Z - info: Discarding surplus device: LGE-LG-D722

2016-01-19T22:10:40.651Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-01-19T22:10:40.652Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-19T22:10:40.694Z - info: Running on ios test: failed to get mobile documents path

2016-01-19T22:10:40.745Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-19T22:10:40.793Z - info: Running on ios test: #init should register the networkChanged event

2016-01-19T22:10:40.857Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-19T22:10:40.911Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-19T22:10:40.973Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-19T22:10:41.047Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-19T22:10:41.110Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-19T22:10:41.172Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-19T22:10:41.237Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-19T22:10:41.305Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-19T22:10:41.375Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-19T22:10:41.464Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-19T22:10:41.484Z - debug: Socket disconnected: transport close 6 (samsung-SM-N910C)

2016-01-19T22:10:41.560Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-19T22:10:41.631Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-19T22:10:41.717Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-19T22:10:41.752Z - debug: Socket disconnected: transport close 5 (LGE-LG-D722)

2016-01-19T22:10:41.760Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-01-19T22:10:41.761Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-19T22:10:41.787Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-19T22:10:41.820Z - info: Running on android test: multiplex can send data

2016-01-19T22:10:41.903Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-19T22:10:41.944Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:8

2016-01-19T22:10:41.945Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-19T22:10:41.974Z - info: Running on android test: basic

2016-01-19T22:10:42.018Z - info: Running on android test: another

2016-01-19T22:10:42.085Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-19T22:10:42.242Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-19T22:10:42.314Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-19T22:10:42.343Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-19T22:10:42.413Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-19T22:10:42.469Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-19T22:10:42.536Z - info: Running on android test: failed to get mobile documents path

2016-01-19T22:10:42.601Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-19T22:10:42.653Z - info: Running on android test: #init should register the networkChanged event

2016-01-19T22:10:42.701Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-19T22:10:42.747Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-19T22:10:42.761Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-01-19T22:10:42.801Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-19T22:10:42.813Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-19T22:10:42.855Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-19T22:10:42.868Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F)

2016-01-19T22:10:42.931Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-19T22:10:42.978Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-19T22:10:43.027Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-19T22:10:43.088Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-19T22:10:43.145Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-19T22:10:43.199Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-19T22:10:43.256Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-19T22:10:43.332Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-19T22:10:43.500Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-19T22:10:43.575Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-19T22:10:43.737Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)

2016-01-19T22:10:43.762Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:9

2016-01-19T22:10:43.763Z - info: Discarding surplus device: LGE-LG-D855

2016-01-19T22:10:43.779Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-19T22:10:44.643Z - debug: Socket disconnected: transport close 9 (LGE-LG-D855)

2016-01-19T22:10:44.802Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-19T22:10:45.352Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-19T22:10:45.800Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-19T22:10:46.037Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-19T22:10:46.455Z - info: Running on android test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-19T22:10:46.749Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-19T22:10:46.945Z - info: Test run on android complete

2016-01-19T22:10:46.948Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-19T22:10:46.949Z - info: PLATFORM: android

2016-01-19T22:10:46.950Z - info: RESULT: PASS

2016-01-19T22:10:46.951Z - info: 30 of 30 tests completed

2016-01-19T22:10:46.952Z - info: 30/30 passed (0 failures)

2016-01-19T22:10:46.953Z - info: --- Test Details ---



2016-01-19T22:10:46.954Z - info: multiplex can send data - pass

2016-01-19T22:10:46.955Z - info: basic - pass

2016-01-19T22:10:46.956Z - info: another - pass

2016-01-19T22:10:46.957Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-19T22:10:46.958Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-19T22:10:46.959Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-19T22:10:46.960Z - info: failed to get mobile documents path - pass

2016-01-19T22:10:46.961Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-19T22:10:46.962Z - info: #init should register the networkChanged event - pass

2016-01-19T22:10:46.963Z - info: #startBroadcasting should throw on null device name - pass

2016-01-19T22:10:46.964Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-19T22:10:46.965Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-19T22:10:46.966Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-19T22:10:46.967Z - info: #startBroadcasting should throw on negative port - pass

2016-01-19T22:10:46.968Z - info: #startBroadcasting should throw on too large port - pass

2016-01-19T22:10:46.969Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-19T22:10:46.970Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-19T22:10:46.971Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-19T22:10:46.972Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-19T22:10:46.973Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-01-19T22:10:46.974Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-19T22:10:46.975Z - info: should call Mobile("Disconnect") without an error - pass
2016-01-19T22:10:46.975Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-19T22:10:46.976Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
2016-01-19T22:10:46.977Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-19T22:10:46.981Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-19T22:10:46.981Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-19T22:10:46.982Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass
2016-01-19T22:10:46.983Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass
2016-01-19T22:10:46.984Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-19T22:10:46.984Z - info: 

-== END ==-

2016-01-19T22:10:54.975Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-19T22:11:10.618Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-19T22:11:35.250Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-19T22:11:43.104Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-19T22:11:54.154Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-19T22:11:54.478Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-19T22:11:54.717Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-19T22:12:11.830Z - debug: Socket disconnected: ping timeout 2 (LGE-LG-H815)

2016-01-19T22:12:11.960Z - debug: Socket disconnected: ping timeout 3 (LGE-Nexus 5)

2016-01-19T22:13:19.743Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone6-1)

2016-01-19T22:22:58.987Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)


 
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
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/565307121a686b7_Fix_messed_up_SSDP_binding_language_yaronyg/thali09_LGE-Nexus 5.md)





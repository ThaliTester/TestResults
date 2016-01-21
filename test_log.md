#### Test 56672827b6f75d5 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-21T16:47:56.512Z - info: listening on *:3000

2016-01-21T16:47:57.171Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:0

2016-01-21T16:47:57.464Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-01-21T16:47:57.467Z - info: Required number of android devices presented (2)

2016-01-21T16:47:57.470Z - info: Starting unit test run for platform: android

2016-01-21T16:47:57.764Z - info: Running on android test: multiplex can send data

2016-01-21T16:47:57.942Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:2

2016-01-21T16:47:57.943Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-21T16:47:57.996Z - info: Running on android test: enqueue and run in order

2016-01-21T16:47:58.351Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-01-21T16:47:58.354Z - info: Discarding surplus device: LGE-LG-H815

2016-01-21T16:47:58.360Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-01-21T16:47:58.369Z - info: Running on android test: basic

2016-01-21T16:47:58.504Z - info: Running on android test: another

2016-01-21T16:47:58.570Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-21T16:47:58.625Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:5

2016-01-21T16:47:58.627Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-21T16:47:58.920Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-21T16:47:58.949Z - debug: Socket disconnected: transport close 2 (samsung-SM-G900F)

2016-01-21T16:47:59.236Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-21T16:47:59.301Z - info: Running on android test: failed to get mobile documents path

2016-01-21T16:47:59.343Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-21T16:47:59.394Z - info: Running on android test: #init should register the networkChanged event

2016-01-21T16:47:59.444Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-21T16:47:59.494Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-21T16:47:59.509Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-01-21T16:47:59.543Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-21T16:47:59.593Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-21T16:47:59.648Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-21T16:47:59.694Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-21T16:47:59.740Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-21T16:47:59.785Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-21T16:47:59.808Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F)

2016-01-21T16:47:59.850Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-21T16:47:59.924Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-21T16:47:59.992Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-21T16:48:00.075Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-21T16:48:00.129Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-21T16:48:00.173Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-21T16:48:00.238Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-21T16:48:00.286Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:6

2016-01-21T16:48:00.287Z - info: Discarding surplus device: LGE-LG-D855

2016-01-21T16:48:00.601Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:7

2016-01-21T16:48:00.603Z - info: Required number of ios devices presented (2)

2016-01-21T16:48:00.605Z - info: Starting unit test run for platform: ios

2016-01-21T16:48:00.959Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:8

2016-01-21T16:48:00.960Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-21T16:48:01.295Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:9

2016-01-21T16:48:01.296Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-01-21T16:48:01.566Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:10

2016-01-21T16:48:01.567Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-21T16:48:01.702Z - debug: Socket disconnected: transport close 6 (LGE-LG-D855)

2016-01-21T16:48:01.978Z - debug: Socket disconnected: transport close 10 (LGE-Nexus 5)

2016-01-21T16:48:02.026Z - info: Running on ios test: multiplex can send data

2016-01-21T16:48:03.339Z - debug: Socket disconnected: transport close 8 (Apple-Iphone6-1)

2016-01-21T16:48:03.458Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-21T16:48:03.804Z - debug: Socket disconnected: transport close 9 (Apple-IpadAir2-1)

2016-01-21T16:48:03.988Z - info: Running on ios test: enqueue and run in order

2016-01-21T16:48:04.440Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-21T16:48:04.524Z - info: Running on ios test: basic

2016-01-21T16:48:05.063Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-21T16:48:05.425Z - info: Running on ios test: another

2016-01-21T16:48:05.490Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-21T16:48:05.829Z - info: Running on android test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-21T16:48:06.018Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-21T16:48:06.177Z - info: Test run on android complete

2016-01-21T16:48:06.179Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-21T16:48:06.180Z - info: PLATFORM: android

2016-01-21T16:48:06.181Z - info: RESULT: PASS

2016-01-21T16:48:06.183Z - info: 31 of 31 tests completed

2016-01-21T16:48:06.184Z - info: 31/31 passed (0 failures)

2016-01-21T16:48:06.185Z - info: --- Test Details ---



2016-01-21T16:48:06.186Z - info: multiplex can send data - pass

2016-01-21T16:48:06.187Z - info: enqueue and run in order - pass

2016-01-21T16:48:06.188Z - info: basic - pass

2016-01-21T16:48:06.189Z - info: another - pass

2016-01-21T16:48:06.190Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-21T16:48:06.191Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-21T16:48:06.192Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-21T16:48:06.194Z - info: failed to get mobile documents path - pass

2016-01-21T16:48:06.195Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-21T16:48:06.196Z - info: #init should register the networkChanged event - pass

2016-01-21T16:48:06.197Z - info: #startBroadcasting should throw on null device name - pass

2016-01-21T16:48:06.198Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-21T16:48:06.199Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-21T16:48:06.200Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-21T16:48:06.201Z - info: #startBroadcasting should throw on negative port - pass

2016-01-21T16:48:06.202Z - info: #startBroadcasting should throw on too large port - pass

2016-01-21T16:48:06.203Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-21T16:48:06.204Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-21T16:48:06.205Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-21T16:48:06.206Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-21T16:48:06.207Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-21T16:48:06.208Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-21T16:48:06.209Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-21T16:48:06.210Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-21T16:48:06.211Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-21T16:48:06.212Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-21T16:48:06.217Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-21T16:48:06.217Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-21T16:48:06.219Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-21T16:48:06.222Z - info: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation - pass

2016-01-21T16:48:06.223Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-21T16:48:06.225Z - info: 

-== END ==-

2016-01-21T16:48:07.300Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-21T16:48:11.372Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-21T16:48:11.671Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-21T16:48:11.835Z - info: Running on ios test: failed to get mobile documents path

2016-01-21T16:48:12.154Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-21T16:48:13.201Z - info: Running on ios test: #init should register the networkChanged event

2016-01-21T16:48:15.446Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-21T16:48:16.900Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-21T16:48:17.166Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-21T16:48:18.173Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-21T16:48:18.310Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-21T16:48:18.570Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-21T16:48:18.641Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-21T16:48:19.470Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-21T16:48:20.422Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-21T16:48:20.497Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-21T16:48:20.550Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-21T16:48:20.602Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-21T16:48:20.655Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-21T16:48:20.706Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-21T16:48:20.782Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-21T16:48:21.183Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-21T16:48:21.627Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-21T16:48:22.339Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-21T16:48:26.278Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-21T16:48:32.469Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-21T16:48:37.823Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-21T16:48:43.094Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-21T16:48:49.971Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-21T16:48:58.292Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-21T16:48:59.194Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-21T16:48:59.712Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-21T16:49:31.186Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-D722)

2016-01-21T16:49:31.193Z - debug: Socket disconnected: ping timeout 1 (samsung-SM-N910C)

2016-01-21T16:49:41.247Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-21T16:49:41.770Z - info: Running on ios test: #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation

2016-01-21T16:49:44.268Z - debug: Socket disconnected: transport close 7 (Apple-Iphone5-1)

2016-01-21T17:00:32.508Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)


 
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
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56672827b6f75d5__472_Promise_Queue_yaronyg/thali09_LGE-Nexus 5.md)





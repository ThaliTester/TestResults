#### Test 56818254e6f5c3b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-29T16:44:21.858Z - info: listening on *:3000

2016-01-29T16:44:23.530Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:1

2016-01-29T16:44:23.554Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-01-29T16:44:23.556Z - info: Required number of android devices presented (2)

2016-01-29T16:44:23.560Z - info: Starting unit test run for platform: android

2016-01-29T16:44:23.790Z - info: Running on android test: multiplex can send data

2016-01-29T16:44:23.874Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-01-29T16:44:23.988Z - info: Running on android test: enqueue and run in order

2016-01-29T16:44:24.065Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:4

2016-01-29T16:44:24.066Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-29T16:44:24.141Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:5

2016-01-29T16:44:24.142Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-29T16:44:24.312Z - info: Running on android test: basic

2016-01-29T16:44:24.358Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-01-29T16:44:24.359Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-29T16:44:24.416Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:7

2016-01-29T16:44:24.416Z - info: Discarding surplus device: LGE-LG-D722

2016-01-29T16:44:24.433Z - info: Running on android test: another

2016-01-29T16:44:24.558Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-29T16:44:24.832Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-29T16:44:24.915Z - debug: Socket disconnected: transport close 5 (samsung-SM-A300FU)

2016-01-29T16:44:24.962Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:8

2016-01-29T16:44:24.963Z - info: Required number of ios devices presented (2)

2016-01-29T16:44:24.965Z - info: Starting unit test run for platform: ios

2016-01-29T16:44:24.984Z - debug: Socket disconnected: transport close 6 (samsung-SM-N910C)

2016-01-29T16:44:25.043Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-29T16:44:25.055Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:9

2016-01-29T16:44:25.056Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-29T16:44:25.105Z - info: Running on android test: failed to get mobile documents path

2016-01-29T16:44:25.154Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-29T16:44:25.201Z - info: Running on android test: #init should register the networkChanged event

2016-01-29T16:44:25.229Z - debug: Socket disconnected: transport close 4 (samsung-SM-G900F)

2016-01-29T16:44:25.258Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-29T16:44:25.308Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-29T16:44:25.379Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-29T16:44:25.435Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-29T16:44:25.476Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:10

2016-01-29T16:44:25.477Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-29T16:44:25.506Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-29T16:44:25.568Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-29T16:44:25.591Z - debug: Socket disconnected: transport close 9 (LGE-Nexus 5)

2016-01-29T16:44:25.612Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:11

2016-01-29T16:44:25.613Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-01-29T16:44:25.644Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-29T16:44:25.658Z - debug: Socket disconnected: transport close 7 (LGE-LG-D722)

2016-01-29T16:44:25.731Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-29T16:44:25.796Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-29T16:44:25.864Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-29T16:44:25.955Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-29T16:44:26.023Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-29T16:44:26.077Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-29T16:44:26.129Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-29T16:44:26.176Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:12

2016-01-29T16:44:26.177Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-29T16:44:26.188Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-29T16:44:26.430Z - debug: Socket disconnected: transport close 10 (HTC-HTC Desire 820)

2016-01-29T16:44:26.891Z - info: Running on ios test: multiplex can send data

2016-01-29T16:44:27.138Z - info: Running on ios test: enqueue and run in order

2016-01-29T16:44:27.431Z - info: Running on ios test: basic

2016-01-29T16:44:27.443Z - debug: Socket disconnected: transport close 12 (samsung-SM-G900F)

2016-01-29T16:44:27.481Z - info: Running on ios test: another

2016-01-29T16:44:27.510Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-29T16:44:27.565Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-29T16:44:27.816Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-29T16:44:27.973Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-29T16:44:28.009Z - debug: Socket disconnected: transport close 11 (Apple-IpadAir2-1)

2016-01-29T16:44:28.062Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-29T16:44:28.193Z - info: Running on ios test: failed to get mobile documents path

2016-01-29T16:44:28.254Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-29T16:44:28.306Z - info: Running on ios test: #init should register the networkChanged event

2016-01-29T16:44:28.368Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-29T16:44:28.379Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-29T16:44:28.475Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-29T16:44:28.530Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-29T16:44:28.596Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-29T16:44:28.666Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-29T16:44:28.853Z - info: Running on android test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-01-29T16:44:29.199Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-29T16:44:29.353Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-29T16:44:29.627Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-01-29T16:44:29.628Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-29T16:44:29.649Z - info: Running on android test: messages with invalid location or USN should be ignored

2016-01-29T16:44:29.869Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-29T16:44:30.105Z - info: Running on android test: #start should fail if called twice in a row

2016-01-29T16:44:30.449Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-29T16:44:30.544Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-01-29T16:44:30.641Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-29T16:44:30.767Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-29T16:44:30.817Z - info: Running on android test: #startListeningForAdvertisements can be called multiple times in a row

2016-01-29T16:44:30.869Z - info: Running on android test: #stopListeningForAdvertisements can be called multiple times in a row

2016-01-29T16:44:30.919Z - info: Running on android test: #stopAdvertisingAndListening can be called multiple times in a row

2016-01-29T16:44:30.965Z - info: Running on android test: functions are run from a queue in the right order

2016-01-29T16:44:31.067Z - info: Test run on android complete

2016-01-29T16:44:31.070Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-29T16:44:31.071Z - info: PLATFORM: android

2016-01-29T16:44:31.072Z - info: RESULT: PASS

2016-01-29T16:44:31.073Z - info: 41 of 41 tests completed

2016-01-29T16:44:31.074Z - info: 41/41 passed (0 failures)

2016-01-29T16:44:31.075Z - info: --- Test Details ---



2016-01-29T16:44:31.077Z - info: multiplex can send data - pass

2016-01-29T16:44:31.078Z - info: enqueue and run in order - pass

2016-01-29T16:44:31.079Z - info: basic - pass

2016-01-29T16:44:31.080Z - info: another - pass

2016-01-29T16:44:31.081Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-29T16:44:31.082Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-29T16:44:31.083Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-29T16:44:31.084Z - info: failed to get mobile documents path - pass
2016-01-29T16:44:31.085Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-29T16:44:31.086Z - info: #init should register the networkChanged event - pass

2016-01-29T16:44:31.086Z - info: #startBroadcasting should throw on null device name - pass

2016-01-29T16:44:31.090Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-29T16:44:31.091Z - info: #startBroadcasting should throw on non-number port - pass
2016-01-29T16:44:31.092Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-29T16:44:31.093Z - info: #startBroadcasting should throw on negative port - pass
2016-01-29T16:44:31.094Z - info: #startBroadcasting should throw on too large port - pass
2016-01-29T16:44:31.094Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-29T16:44:31.095Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-29T16:44:31.101Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-29T16:44:31.102Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-29T16:44:31.103Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-01-29T16:44:31.104Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-29T16:44:31.104Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-29T16:44:31.105Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-29T16:44:31.106Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-29T16:44:31.107Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-29T16:44:31.108Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-29T16:44:31.109Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-29T16:44:31.109Z - info: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-01-29T16:44:31.110Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-29T16:44:31.111Z - info: messages with invalid location or USN should be ignored - pass
2016-01-29T16:44:31.112Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-29T16:44:31.114Z - info: #start should fail if called twice in a row - pass
2016-01-29T16:44:31.118Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-01-29T16:44:31.119Z - info: #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-01-29T16:44:31.120Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-01-29T16:44:31.120Z - info: #stop can be called multiple times in a row - pass
2016-01-29T16:44:31.121Z - info: #startListeningForAdvertisements can be called multiple times in a row - pass
2016-01-29T16:44:31.122Z - info: #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-01-29T16:44:31.123Z - info: #stopAdvertisingAndListening can be called multiple times in a row - pass
2016-01-29T16:44:31.125Z - info: functions are run from a queue in the right order - pass

2016-01-29T16:44:31.126Z - info: 

-== END ==-

2016-01-29T16:44:31.643Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:13

2016-01-29T16:44:31.644Z - info: Discarding surplus device: LGE-LG-D855

2016-01-29T16:44:31.959Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-29T16:44:32.025Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-29T16:44:32.104Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-29T16:44:32.196Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-29T16:44:32.257Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-01-29T16:44:32.272Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-29T16:44:32.284Z - debug: Socket disconnected: transport close 13 (LGE-LG-D855)

2016-01-29T16:44:32.376Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-29T16:44:32.478Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-29T16:44:32.531Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-29T16:44:32.608Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-29T16:44:32.966Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-29T16:44:34.881Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-29T16:44:39.733Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-29T16:44:41.093Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-29T16:44:47.510Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-29T16:44:53.279Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-29T16:44:58.718Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-29T16:45:06.016Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-29T16:45:14.413Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-29T16:45:15.788Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-29T16:45:16.022Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-29T16:45:56.082Z - debug: Socket disconnected: ping timeout 1 (motorola-Nexus 6)

2016-01-29T16:45:56.087Z - debug: Socket disconnected: ping timeout 2 (LGE-LG-H815)

2016-01-29T16:46:41.066Z - debug: Socket disconnected: ping timeout 8 (Apple-Iphone5-1)

2016-01-29T16:54:31.737Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone5s-1)


 
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
ios: child process exited with code 254 on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56818254e6f5c3b__317__378_Replication_and_life_cycle_yaronyg/thali09_LGE-Nexus 5.md)





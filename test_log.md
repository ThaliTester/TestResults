#### Test 573480789efee08 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-28T11:49:53.371Z - info: listening on *:3000

2016-01-28T11:49:53.942Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:0

2016-01-28T11:49:53.985Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:1

2016-01-28T11:49:54.189Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-01-28T11:49:54.191Z - info: Required number of ios devices presented (2)

2016-01-28T11:49:54.196Z - info: Starting unit test run for platform: ios

2016-01-28T11:49:54.335Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-01-28T11:49:54.337Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-01-28T11:49:54.560Z - info: Running on ios test: multiplex can send data

2016-01-28T11:49:54.847Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-01-28T11:49:54.850Z - info: Required number of android devices presented (2)

2016-01-28T11:49:54.851Z - info: Starting unit test run for platform: android

2016-01-28T11:49:55.104Z - info: Running on ios test: enqueue and run in order

2016-01-28T11:49:55.192Z - info: Running on android test: multiplex can send data

2016-01-28T11:49:55.377Z - info: Running on android test: enqueue and run in order

2016-01-28T11:49:55.599Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:5

2016-01-28T11:49:55.600Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-28T11:49:55.876Z - info: Running on android test: basic

2016-01-28T11:49:55.889Z - info: Running on ios test: basic

2016-01-28T11:49:56.021Z - info: Running on android test: another

2016-01-28T11:49:56.066Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-28T11:49:56.203Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:6

2016-01-28T11:49:56.207Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-01-28T11:49:56.326Z - info: Running on ios test: another

2016-01-28T11:49:56.361Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:7

2016-01-28T11:49:56.362Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-28T11:49:56.373Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-28T11:49:56.589Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F)

2016-01-28T11:49:56.611Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-28T11:49:56.643Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:8

2016-01-28T11:49:56.647Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-28T11:49:56.675Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-28T11:49:56.701Z - info: Running on android test: failed to get mobile documents path

2016-01-28T11:49:56.722Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-01-28T11:49:56.780Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-28T11:49:56.846Z - info: Running on android test: #init should register the networkChanged event

2016-01-28T11:49:56.896Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-28T11:49:56.974Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-28T11:49:57.047Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-28T11:49:57.137Z - debug: Socket disconnected: transport close 7 (samsung-SM-N910C)

2016-01-28T11:49:57.144Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-28T11:49:57.206Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-28T11:49:57.293Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-28T11:49:57.354Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-28T11:49:57.371Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-28T11:49:57.442Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-28T11:49:57.516Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-28T11:49:57.581Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-28T11:49:57.642Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-28T11:49:57.658Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F)

2016-01-28T11:49:57.786Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-28T11:49:57.863Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-28T11:49:57.873Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:9

2016-01-28T11:49:57.878Z - info: Discarding surplus device: motorola-Nexus 6

2016-01-28T11:49:57.902Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-28T11:49:57.931Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-28T11:49:58.015Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-28T11:49:58.143Z - info: Running on ios test: failed to get mobile documents path

2016-01-28T11:49:58.361Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-28T11:49:58.439Z - info: Running on ios test: #init should register the networkChanged event

2016-01-28T11:49:58.449Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:10

2016-01-28T11:49:58.450Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-28T11:49:58.509Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-28T11:49:58.570Z - debug: Socket disconnected: transport close 9 (motorola-Nexus 6)

2016-01-28T11:49:58.575Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-28T11:49:58.637Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-28T11:49:58.754Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-28T11:49:58.840Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-28T11:49:58.880Z - debug: Socket disconnected: transport close 10 (LGE-Nexus 5)

2016-01-28T11:49:58.908Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-28T11:49:59.009Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-28T11:49:59.072Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-28T11:49:59.082Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-28T11:49:59.163Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-28T11:49:59.277Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-28T11:49:59.354Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-28T11:49:59.492Z - debug: Socket disconnected: transport close 6 (Apple-Iphone5s-1)

2016-01-28T11:49:59.496Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-28T11:49:59.539Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-28T11:49:59.575Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-28T11:49:59.651Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-28T11:49:59.727Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-28T11:49:59.964Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-28T11:50:00.261Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-28T11:50:01.063Z - info: Running on android test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-01-28T11:50:01.143Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-28T11:50:01.449Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-28T11:50:02.358Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-28T11:50:02.434Z - info: Running on android test: messages with invalid location or USN should be ignored

2016-01-28T11:50:02.754Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-28T11:50:02.909Z - info: Running on android test: #start should fail if called twice in a row

2016-01-28T11:50:03.022Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-28T11:50:03.061Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:11

2016-01-28T11:50:03.063Z - info: Discarding surplus device: LGE-LG-D855

2016-01-28T11:50:03.173Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-01-28T11:50:03.270Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-28T11:50:03.488Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-28T11:50:03.530Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-28T11:50:03.574Z - info: Running on android test: #startListeningForAdvertisements can be called multiple times in a row

2016-01-28T11:50:03.730Z - info: Running on android test: #stopListeningForAdvertisements can be called multiple times in a row

2016-01-28T11:50:03.766Z - debug: Socket disconnected: transport close 11 (LGE-LG-D855)

2016-01-28T11:50:03.883Z - info: Running on android test: #stopAdvertisingAndListening can be called multiple times in a row

2016-01-28T11:50:03.982Z - info: Running on android test: functions are run from a queue in the right order

2016-01-28T11:50:04.113Z - info: Test run on android complete

2016-01-28T11:50:04.116Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-28T11:50:04.117Z - info: PLATFORM: android

2016-01-28T11:50:04.118Z - info: RESULT: PASS

2016-01-28T11:50:04.119Z - info: 41 of 41 tests completed

2016-01-28T11:50:04.120Z - info: 41/41 passed (0 failures)

2016-01-28T11:50:04.121Z - info: --- Test Details ---


2016-01-28T11:50:04.122Z - info: multiplex can send data - pass
2016-01-28T11:50:04.123Z - info: enqueue and run in order - pass
2016-01-28T11:50:04.124Z - info: basic - pass

2016-01-28T11:50:04.125Z - info: another - pass
2016-01-28T11:50:04.126Z - info: successfully create a new pkcs12 file and return hash value - pass
2016-01-28T11:50:04.126Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-28T11:50:04.127Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-28T11:50:04.132Z - info: failed to get mobile documents path - pass

2016-01-28T11:50:04.133Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-28T11:50:04.136Z - info: #init should register the networkChanged event - pass

2016-01-28T11:50:04.137Z - info: #startBroadcasting should throw on null device name - pass

2016-01-28T11:50:04.138Z - info: #startBroadcasting should throw on empty string device name - pass
2016-01-28T11:50:04.139Z - info: #startBroadcasting should throw on non-number port - pass
2016-01-28T11:50:04.140Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-28T11:50:04.141Z - info: #startBroadcasting should throw on negative port - pass
2016-01-28T11:50:04.142Z - info: #startBroadcasting should throw on too large port - pass

2016-01-28T11:50:04.143Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-28T11:50:04.143Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-28T11:50:04.144Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-28T11:50:04.145Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-28T11:50:04.146Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-01-28T11:50:04.148Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-28T11:50:04.152Z - info: should call Mobile("Disconnect") without an error - pass
2016-01-28T11:50:04.153Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-28T11:50:04.154Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
2016-01-28T11:50:04.155Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-28T11:50:04.155Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-28T11:50:04.156Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-28T11:50:04.157Z - info: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass

2016-01-28T11:50:04.159Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-28T11:50:04.160Z - info: messages with invalid location or USN should be ignored - pass

2016-01-28T11:50:04.161Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-28T11:50:04.162Z - info: #start should fail if called twice in a row - pass
2016-01-28T11:50:04.163Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass
2016-01-28T11:50:04.164Z - info: #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-01-28T11:50:04.165Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-01-28T11:50:04.165Z - info: #stop can be called multiple times in a row - pass

2016-01-28T11:50:04.166Z - info: #startListeningForAdvertisements can be called multiple times in a row - pass
2016-01-28T11:50:04.167Z - info: #stopListeningForAdvertisements can be called multiple times in a row - pass

2016-01-28T11:50:04.168Z - info: #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-01-28T11:50:04.169Z - info: functions are run from a queue in the right order - pass

2016-01-28T11:50:04.170Z - info: 

-== END ==-

2016-01-28T11:50:08.618Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-28T11:50:13.862Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-28T11:50:16.163Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:12

2016-01-28T11:50:16.164Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-28T11:50:17.237Z - debug: Socket disconnected: transport close 12 (samsung-SM-G800F)

2016-01-28T11:50:19.034Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-28T11:50:25.913Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-28T11:50:36.105Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-28T11:51:02.102Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-28T11:51:03.393Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-28T11:51:29.128Z - debug: Socket disconnected: ping timeout 4 (LGE-LG-H815)

2016-01-28T11:51:29.136Z - debug: Socket disconnected: ping timeout 1 (LGE-LG-D722)

2016-01-28T11:52:28.663Z - debug: Socket disconnected: ping timeout 2 (Apple-Iphone6-1)

2016-01-28T11:53:35.865Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone5-1)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/573480789efee08_More_Wifi_infrastructure_features_vjrantal/thali09_LGE-Nexus 5.md)





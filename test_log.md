#### Test 58135655e9e7eb8 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-09T12:40:59.374Z - info: listening on *:3000

2016-02-09T12:41:01.016Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-02-09T12:41:01.046Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:2

2016-02-09T12:41:01.067Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:1

2016-02-09T12:41:01.070Z - info: Required number of android devices presented (2)

2016-02-09T12:41:01.074Z - info: Starting unit test run for platform: android

2016-02-09T12:41:01.425Z - info: Running on android test: multiplex can send data

2016-02-09T12:41:01.572Z - info: Running on android test: enqueue and run in order

2016-02-09T12:41:01.981Z - info: Running on android test: basic

2016-02-09T12:41:02.032Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:3

2016-02-09T12:41:02.034Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-09T12:41:02.120Z - info: Running on android test: another

2016-02-09T12:41:02.201Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-09T12:41:02.507Z - debug: Socket disconnected: transport close 3 (LGE-Nexus 5)

2016-02-09T12:41:02.540Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-02-09T12:41:02.542Z - info: Discarding surplus device: LGE-LG-H815

2016-02-09T12:41:02.629Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-09T12:41:02.800Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T12:41:02.910Z - info: Running on android test: failed to get mobile documents path

2016-02-09T12:41:03.039Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-09T12:41:03.146Z - info: Running on android test: #init should register the networkChanged event

2016-02-09T12:41:03.270Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-09T12:41:03.377Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-09T12:41:03.489Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-09T12:41:03.526Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-02-09T12:41:03.604Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-09T12:41:03.618Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:5

2016-02-09T12:41:03.619Z - info: Discarding surplus device: LGE-LG-D855

2016-02-09T12:41:03.698Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-09T12:41:03.804Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-09T12:41:03.901Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T12:41:03.939Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:6

2016-02-09T12:41:03.942Z - info: Discarding surplus device: LGE-LG-D722

2016-02-09T12:41:04.008Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T12:41:04.085Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T12:41:04.108Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:7

2016-02-09T12:41:04.109Z - info: Required number of ios devices presented (2)

2016-02-09T12:41:04.111Z - info: Starting unit test run for platform: ios

2016-02-09T12:41:04.225Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T12:41:04.239Z - debug: Socket disconnected: transport close 5 (LGE-LG-D855)

2016-02-09T12:41:04.330Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T12:41:04.421Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-09T12:41:04.551Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-09T12:41:04.630Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-09T12:41:04.690Z - info: Running on ios test: multiplex can send data

2016-02-09T12:41:04.756Z - info: Running on android test: #start should fail if called twice in a row

2016-02-09T12:41:04.878Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-09T12:41:04.974Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-09T12:41:04.976Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-09T12:41:04.981Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T12:41:05.125Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-09T12:41:05.173Z - debug: Socket disconnected: transport close 6 (LGE-LG-D722)

2016-02-09T12:41:05.256Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T12:41:05.457Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-09T12:41:05.469Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T12:41:05.554Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T12:41:10.136Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-09T12:41:10.137Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T12:41:11.160Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-09T12:41:13.906Z - info: Running on ios test: enqueue and run in order

2016-02-09T12:41:18.210Z - info: Running on ios test: basic

2016-02-09T12:41:19.325Z - info: Running on ios test: another

2016-02-09T12:41:19.666Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-09T12:41:20.213Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-09T12:41:20.559Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T12:41:20.886Z - info: Running on ios test: failed to get mobile documents path

2016-02-09T12:41:21.226Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-09T12:41:21.871Z - info: Running on ios test: #init should register the networkChanged event

2016-02-09T12:41:24.863Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-09T12:41:34.791Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-09T12:41:38.691Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-09T12:41:38.971Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-09T12:41:39.340Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-09T12:41:39.813Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-09T12:41:40.186Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T12:41:40.540Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T12:41:40.874Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T12:41:41.216Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T12:41:41.549Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T12:41:41.887Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-09T12:41:42.228Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-09T12:41:42.609Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-09T12:41:42.735Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-09T12:41:42.890Z - info: Running on ios test: #startListeningForAdvertisements should fail if start not called

2016-02-09T12:41:43.135Z - info: Running on ios test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T12:41:43.266Z - info: Running on ios test: should be able to call #startListeningForAdvertisements many times

2016-02-09T12:41:43.427Z - info: Running on ios test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T12:41:43.608Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T12:41:43.736Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T12:41:44.117Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-09T12:41:44.302Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-09T12:41:44.779Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-09T12:41:45.839Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-09T12:41:51.339Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-09T12:41:56.328Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-09T12:42:01.489Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-09T12:42:08.826Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-09T12:42:16.498Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-09T12:42:16.798Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-09T12:42:17.269Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-09T12:42:30.606Z - debug: Socket disconnected: ping timeout 2 (motorola-Nexus 6)

2016-02-09T12:42:30.611Z - debug: Socket disconnected: ping timeout 1 (samsung-SM-G900F)

2016-02-09T12:42:47.965Z - debug: Socket disconnected: transport close 7 (Apple-Iphone6-1)

2016-02-09T12:54:33.706Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali03_samsung-SM-G800F.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali04_samsung-SM-N910C.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58135655e9e7eb8_Remove_race_in_tests_tobybrad/thali09_LGE-Nexus 5.md)





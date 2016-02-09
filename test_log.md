#### Test 584164489c56086 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-09T09:23:33.195Z - info: listening on *:3000

2016-02-09T09:23:33.548Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-02-09T09:23:34.130Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:1

2016-02-09T09:23:34.133Z - info: Required number of android devices presented (2)

2016-02-09T09:23:34.136Z - info: Starting unit test run for platform: android

2016-02-09T09:23:34.172Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-02-09T09:23:34.224Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:3

2016-02-09T09:23:34.225Z - info: Discarding surplus device: LGE-LG-D722

2016-02-09T09:23:34.965Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-02-09T09:23:34.966Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-09T09:23:35.421Z - debug: Socket disconnected: transport close 3 (LGE-LG-D722)

2016-02-09T09:23:35.651Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)

2016-02-09T09:23:35.797Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:5

2016-02-09T09:23:35.798Z - info: Discarding surplus device: HTC-HTC One M8s

2016-02-09T09:23:35.861Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:6

2016-02-09T09:23:35.863Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T09:23:36.180Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:7

2016-02-09T09:23:36.181Z - info: Discarding surplus device: LGE-LG-D855

2016-02-09T09:23:36.475Z - info: Running on android test: multiplex can send data

2016-02-09T09:23:36.606Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F)

2016-02-09T09:23:36.773Z - debug: Socket disconnected: transport close 7 (LGE-LG-D855)

2016-02-09T09:23:36.967Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:8

2016-02-09T09:23:36.968Z - info: Required number of ios devices presented (2)

2016-02-09T09:23:36.970Z - info: Starting unit test run for platform: ios

2016-02-09T09:23:37.067Z - info: Running on android test: enqueue and run in order

2016-02-09T09:23:37.108Z - debug: Socket disconnected: transport close 5 (HTC-HTC One M8s)

2016-02-09T09:23:37.391Z - info: Running on android test: basic

2016-02-09T09:23:37.508Z - info: Running on android test: another

2016-02-09T09:23:37.556Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-09T09:23:37.622Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:9

2016-02-09T09:23:37.624Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-09T09:23:37.629Z - info: Running on ios test: multiplex can send data

2016-02-09T09:23:37.820Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-09T09:23:37.861Z - info: Running on ios test: enqueue and run in order

2016-02-09T09:23:37.959Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T09:23:38.019Z - info: Running on android test: failed to get mobile documents path

2016-02-09T09:23:38.059Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-09T09:23:38.111Z - info: Running on android test: #init should register the networkChanged event

2016-02-09T09:23:38.148Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-09T09:23:38.196Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-09T09:23:38.262Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-09T09:23:38.311Z - debug: Socket disconnected: transport close 9 (motorola-Nexus 6)

2016-02-09T09:23:38.317Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-09T09:23:38.362Z - info: Running on ios test: basic

2016-02-09T09:23:38.374Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-09T09:23:38.453Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-09T09:23:38.525Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T09:23:38.631Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T09:23:38.685Z - info: Running on ios test: another

2016-02-09T09:23:38.732Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T09:23:38.808Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T09:23:38.873Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-09T09:23:38.881Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T09:23:38.934Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-09T09:23:38.982Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-09T09:23:39.028Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-09T09:23:39.091Z - info: Running on android test: #start should fail if called twice in a row

2016-02-09T09:23:39.158Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-09T09:23:39.208Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T09:23:39.260Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-09T09:23:39.322Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T09:23:39.373Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-09T09:23:39.424Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T09:23:39.462Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T09:23:43.088Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T09:23:43.232Z - info: Running on ios test: failed to get mobile documents path

2016-02-09T09:23:43.302Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-09T09:23:43.374Z - info: Running on ios test: #init should register the networkChanged event

2016-02-09T09:23:43.436Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-09T09:23:43.526Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-09T09:23:43.603Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-09T09:23:43.663Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-09T09:23:43.727Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-09T09:23:43.838Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-09T09:23:43.913Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T09:23:44.000Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T09:23:44.092Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T09:23:44.197Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T09:23:44.264Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T09:23:44.331Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-09T09:23:44.394Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-09T09:23:44.465Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-09T09:23:44.547Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-09T09:23:44.616Z - info: Running on ios test: #startListeningForAdvertisements should fail if start not called

2016-02-09T09:23:44.683Z - info: Running on ios test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T09:23:44.761Z - info: Running on ios test: should be able to call #startListeningForAdvertisements many times

2016-02-09T09:23:44.869Z - info: Running on ios test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T09:23:45.002Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T09:23:45.092Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T09:23:45.479Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-09T09:23:45.966Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-09T09:23:46.196Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-09T09:23:46.641Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-09T09:23:51.303Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-09T09:23:55.512Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-09T09:24:04.761Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-09T09:25:04.489Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-H815)

2016-02-09T09:36:49.004Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-02-09T09:36:49.152Z - debug: Socket disconnected: transport close 8 (Apple-Iphone6-1)

2016-02-09T09:40:02.540Z - debug: Socket disconnected: transport close 1 (LGE-Nexus 5)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali07_samsung-SM-A500FU.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali07_samsung-SM-G900F.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/584164489c56086_Request_and_Check_Permissions_in_Android__412_juhanak/thali09_LGE-Nexus 5.md)





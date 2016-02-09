#### Test 5841644866d9c0e Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-09T12:12:40.870Z - info: listening on *:3000

2016-02-09T12:12:41.322Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:0

2016-02-09T12:12:41.988Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:1

2016-02-09T12:12:41.991Z - info: Required number of android devices presented (2)

2016-02-09T12:12:41.994Z - info: Starting unit test run for platform: android

2016-02-09T12:12:42.617Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:2

2016-02-09T12:12:42.618Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-09T12:12:42.819Z - info: Running on android test: multiplex can send data

2016-02-09T12:12:43.123Z - debug: Socket disconnected: transport close 2 (LGE-Nexus 5)

2016-02-09T12:12:43.656Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-02-09T12:12:44.453Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:4

2016-02-09T12:12:44.454Z - info: Discarding surplus device: LGE-LG-D855

2016-02-09T12:12:44.588Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:5

2016-02-09T12:12:44.589Z - info: Discarding surplus device: LGE-LG-D722

2016-02-09T12:12:45.740Z - debug: Socket disconnected: transport close 5 (LGE-LG-D722)

2016-02-09T12:12:45.877Z - info: Running on android test: enqueue and run in order

2016-02-09T12:12:45.985Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:7

2016-02-09T12:12:45.986Z - info: Discarding surplus device: LGE-LG-H815

2016-02-09T12:12:46.220Z - info: Running on android test: basic

2016-02-09T12:12:46.339Z - info: Running on android test: another

2016-02-09T12:12:46.442Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-09T12:12:46.800Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-09T12:12:46.959Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T12:12:46.982Z - debug: Socket disconnected: transport close 7 (LGE-LG-H815)

2016-02-09T12:12:47.026Z - info: Running on android test: failed to get mobile documents path

2016-02-09T12:12:47.081Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-09T12:12:47.153Z - info: Running on android test: #init should register the networkChanged event

2016-02-09T12:12:47.209Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-09T12:12:47.264Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-09T12:12:47.327Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-09T12:12:47.395Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-09T12:12:47.456Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-09T12:12:47.532Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-09T12:12:47.607Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T12:12:47.674Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T12:12:47.699Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-09T12:12:47.700Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-09T12:12:47.747Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T12:12:47.817Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T12:12:47.880Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T12:12:47.958Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-09T12:12:48.014Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-09T12:12:48.093Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-09T12:12:48.182Z - info: Running on android test: #start should fail if called twice in a row

2016-02-09T12:12:48.273Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:6

2016-02-09T12:12:48.274Z - info: Required number of ios devices presented (2)
2016-02-09T12:12:48.276Z - info: Starting unit test run for platform: ios

2016-02-09T12:12:48.297Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-09T12:12:48.330Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-09T12:12:48.371Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T12:12:48.450Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-09T12:12:48.526Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T12:12:48.651Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T12:12:48.694Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T12:12:49.388Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-09T12:12:49.391Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T12:12:50.081Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-09T12:12:50.221Z - debug: Socket disconnected: transport close 4 (LGE-LG-D855)

2016-02-09T12:13:04.219Z - info: Running on ios test: multiplex can send data

2016-02-09T12:13:12.610Z - info: Running on ios test: enqueue and run in order

2016-02-09T12:13:22.230Z - info: Running on ios test: basic

2016-02-09T12:13:30.132Z - info: Running on ios test: another

2016-02-09T12:13:44.875Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-09T12:13:49.658Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-09T12:13:56.204Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T12:13:57.029Z - info: Running on ios test: failed to get mobile documents path

2016-02-09T12:14:06.235Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-09T12:14:13.715Z - debug: Socket disconnected: ping timeout 0 (motorola-Nexus 6)

2016-02-09T12:14:13.722Z - debug: Socket disconnected: ping timeout 1 (samsung-SM-G900F)

2016-02-09T12:14:13.732Z - info: Running on ios test: #init should register the networkChanged event

2016-02-09T12:14:20.158Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-09T12:14:30.998Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-09T12:14:39.801Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-09T12:14:45.333Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-09T12:14:54.125Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-09T12:15:01.833Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-09T12:15:13.979Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T12:15:18.480Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T12:15:23.199Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T12:15:47.748Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T12:15:57.367Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T12:16:00.866Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-09T12:16:06.798Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-09T12:16:17.433Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-09T12:16:31.359Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-09T12:16:38.429Z - info: Running on ios test: #startListeningForAdvertisements should fail if start not called

2016-02-09T12:16:48.125Z - info: Running on ios test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T12:16:54.065Z - info: Running on ios test: should be able to call #startListeningForAdvertisements many times

2016-02-09T12:16:56.733Z - info: Running on ios test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T12:17:02.247Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T12:17:02.867Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T12:17:12.080Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-09T12:17:22.440Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-09T12:17:43.753Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-09T12:17:53.150Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-09T12:18:11.505Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-09T12:18:16.204Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-09T12:18:22.477Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-09T12:18:32.466Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-09T12:18:45.045Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-09T12:18:55.308Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-02-09T12:20:23.585Z - debug: Socket disconnected: ping timeout 6 (Apple-Iphone5-1)


 
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
ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5841644866d9c0e_Request_and_Check_Permissions_in_Android__412_juhanak/thali09_LGE-Nexus 5.md)





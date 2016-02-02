#### Test 579720943a29850 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-02T12:10:05.740Z - info: listening on *:3000

2016-02-02T12:10:06.632Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:0

2016-02-02T12:10:07.511Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:1

2016-02-02T12:10:07.514Z - info: Required number of android devices presented (2)

2016-02-02T12:10:07.518Z - info: Starting unit test run for platform: android

2016-02-02T12:10:08.011Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-02-02T12:10:08.234Z - info: Running on android test: multiplex can send data

2016-02-02T12:10:08.640Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-02-02T12:10:08.642Z - info: Required number of ios devices presented (2)

2016-02-02T12:10:08.643Z - info: Starting unit test run for platform: ios

2016-02-02T12:10:08.659Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-02-02T12:10:08.661Z - info: Discarding surplus device: LGE-LG-H815

2016-02-02T12:10:09.312Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-02-02T12:10:09.313Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-02T12:10:09.447Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-02-02T12:10:09.448Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-02T12:10:09.570Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:7

2016-02-02T12:10:09.571Z - info: Discarding surplus device: LGE-LG-D855

2016-02-02T12:10:09.646Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-02-02T12:10:09.973Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-02-02T12:10:10.002Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-02-02T12:10:10.162Z - debug: Socket disconnected: transport close 7 (LGE-LG-D855)

2016-02-02T12:10:10.177Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:8

2016-02-02T12:10:10.178Z - info: Discarding surplus device: HTC-HTC One M8s

2016-02-02T12:10:10.805Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:9

2016-02-02T12:10:10.806Z - info: Discarding surplus device: Apple-Iphone6-1

2016-02-02T12:10:10.830Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:10

2016-02-02T12:10:10.831Z - info: Discarding surplus device: LGE-LG-D722

2016-02-02T12:10:11.065Z - debug: Socket disconnected: transport close 8 (HTC-HTC One M8s)

2016-02-02T12:10:11.075Z - info: Running on ios test: multiplex can send data

2016-02-02T12:10:11.528Z - info: Running on android test: enqueue and run in order

2016-02-02T12:10:11.604Z - info: Running on ios test: enqueue and run in order

2016-02-02T12:10:11.916Z - info: Running on ios test: basic

2016-02-02T12:10:11.992Z - info: Running on android test: basic

2016-02-02T12:10:12.001Z - debug: Socket disconnected: transport close 10 (LGE-LG-D722)

2016-02-02T12:10:12.013Z - info: Running on ios test: another

2016-02-02T12:10:12.108Z - info: Running on android test: another

2016-02-02T12:10:12.119Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-02T12:10:12.171Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-02T12:10:12.365Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-02T12:10:12.493Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-02T12:10:12.563Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-02T12:10:12.711Z - info: Running on ios test: failed to get mobile documents path

2016-02-02T12:10:12.730Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-02T12:10:12.783Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-02T12:10:12.827Z - info: Running on android test: failed to get mobile documents path

2016-02-02T12:10:12.871Z - info: Running on ios test: #init should register the networkChanged event

2016-02-02T12:10:12.924Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-02T12:10:12.944Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-02T12:10:13.050Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-02T12:10:13.066Z - info: Running on android test: #init should register the networkChanged event

2016-02-02T12:10:13.140Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-02T12:10:13.155Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-02T12:10:13.204Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-02T12:10:13.227Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-02T12:10:13.287Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-02T12:10:13.315Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-02T12:10:13.350Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-02T12:10:13.414Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-02T12:10:13.462Z - debug: Socket disconnected: transport close 9 (Apple-Iphone6-1)

2016-02-02T12:10:13.477Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-02T12:10:13.487Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-02T12:10:13.550Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-02T12:10:13.561Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-02T12:10:13.614Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-02T12:10:13.621Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-02T12:10:13.680Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-02T12:10:13.693Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-02T12:10:13.747Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-02T12:10:13.758Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-02T12:10:13.805Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-02T12:10:13.901Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-02T12:10:13.974Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-02T12:10:14.026Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-02T12:10:14.071Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-02T12:10:14.113Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-02T12:10:14.184Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-02T12:10:14.251Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-02T12:10:15.056Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:11

2016-02-02T12:10:15.059Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-02T12:10:15.764Z - debug: Socket disconnected: transport close 11 (samsung-SM-G900F)

2016-02-02T12:10:17.493Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-02T12:10:17.556Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-02T12:10:17.912Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-02T12:10:18.061Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-02T12:10:19.083Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-02T12:10:20.423Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-02T12:10:25.866Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-02T12:10:32.482Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-02T12:10:37.516Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-02T12:10:47.980Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-02T12:10:59.906Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-02T12:11:00.914Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-02T12:11:01.352Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-02T12:11:39.051Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-02-02T12:11:39.218Z - debug: Socket disconnected: ping timeout 1 (samsung-SM-G900F)

2016-02-02T12:13:15.285Z - debug: Socket disconnected: ping timeout 2 (Apple-Iphone5-1)

2016-02-02T12:26:51.693Z - debug: Socket disconnected: transport close 0 (LGE-Nexus 5)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali05_samsung-SM-G800H.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali05_motorola-Nexus 6.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/579720943a29850_Address_test_setup_issue_vjrantal/thali09_LGE-Nexus 5.md)





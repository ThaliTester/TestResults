#### Test 583805003a0697c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-09T22:18:51.188Z - info: listening on *:3000

2016-02-09T22:18:53.604Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:0

2016-02-09T22:18:53.656Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:1

2016-02-09T22:18:53.659Z - info: Required number of android devices presented (2)

2016-02-09T22:18:53.663Z - info: Starting unit test run for platform: android

2016-02-09T22:18:53.982Z - info: Running on android test: multiplex can send data

2016-02-09T22:18:54.167Z - info: Running on android test: enqueue and run in order

2016-02-09T22:18:54.353Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:2

2016-02-09T22:18:54.354Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-09T22:18:54.568Z - info: Running on android test: basic

2016-02-09T22:18:54.684Z - info: Running on android test: another

2016-02-09T22:18:54.779Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-09T22:18:55.060Z - debug: Socket disconnected: transport close 2 (motorola-Nexus 6)

2016-02-09T22:18:55.087Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-02-09T22:18:55.204Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-09T22:18:55.500Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:4

2016-02-09T22:18:55.501Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-09T22:18:55.514Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-09T22:18:55.611Z - info: Running on android test: failed to get mobile documents path

2016-02-09T22:18:55.618Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:5

2016-02-09T22:18:55.619Z - info: Discarding surplus device: LGE-LG-D855

2016-02-09T22:18:55.727Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-09T22:18:55.834Z - info: Running on android test: #init should register the networkChanged event

2016-02-09T22:18:55.944Z - debug: Socket disconnected: transport close 4 (LGE-Nexus 5)

2016-02-09T22:18:55.967Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-09T22:18:56.129Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-09T22:18:56.191Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:6

2016-02-09T22:18:56.201Z - info: Discarding surplus device: LGE-LG-H815

2016-02-09T22:18:56.242Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-09T22:18:56.267Z - debug: Socket disconnected: transport close 5 (LGE-LG-D855)

2016-02-09T22:18:56.333Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-09T22:18:56.423Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-09T22:18:56.515Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-09T22:18:56.644Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-09T22:18:56.743Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-09T22:18:56.941Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-09T22:18:57.089Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-09T22:18:57.162Z - debug: Socket disconnected: transport close 6 (LGE-LG-H815)

2016-02-09T22:18:57.203Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-09T22:18:57.295Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-09T22:18:57.400Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-09T22:18:57.483Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-09T22:18:57.587Z - info: Running on android test: #start should fail if called twice in a row

2016-02-09T22:18:57.686Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-09T22:18:57.802Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-09T22:18:57.839Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:7

2016-02-09T22:18:57.840Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-09T22:18:57.957Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-09T22:18:58.056Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-09T22:18:58.229Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-09T22:18:58.302Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-09T22:18:58.347Z - debug: Socket disconnected: transport close 7 (samsung-SM-N910C)

2016-02-09T22:19:01.710Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:8

2016-02-09T22:19:01.711Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-09T22:19:02.337Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F)

2016-02-09T22:20:23.392Z - debug: Socket disconnected: ping timeout 1 (samsung-SM-G900F)

2016-02-09T22:32:17.905Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-02-09T22:35:40.668Z - debug: Socket disconnected: transport close 0 (LGE-LG-D722)


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/583805003a0697c_Completes_Issue_209_-_Implement_Thali_Notification_Beacons_mpodwysocki/thali09_LGE-Nexus 5.md)





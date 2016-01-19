#### Test 564317025f150b2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-19T08:09:19.937Z - info: listening on *:3000

2016-01-19T08:09:20.508Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:0

2016-01-19T08:09:20.586Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-01-19T08:09:20.589Z - info: Required number of android devices presented (2)

2016-01-19T08:09:20.593Z - info: Starting unit test run for platform: android

2016-01-19T08:09:20.633Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-01-19T08:09:20.641Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-01-19T08:09:20.643Z - info: Required number of ios devices presented (2)

2016-01-19T08:09:20.644Z - info: Starting unit test run for platform: ios

2016-01-19T08:09:20.678Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-01-19T08:09:20.679Z - info: Discarding surplus device: LGE-LG-H815

2016-01-19T08:09:20.838Z - info: Running on android test: multiplex can send data

2016-01-19T08:09:20.890Z - info: Running on ios test: multiplex can send data

2016-01-19T08:09:21.004Z - info: Running on android test: basic

2016-01-19T08:09:21.074Z - info: Running on ios test: basic

2016-01-19T08:09:21.103Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:5

2016-01-19T08:09:21.105Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-19T08:09:21.116Z - info: Running on android test: another

2016-01-19T08:09:21.155Z - info: Running on ios test: another

2016-01-19T08:09:21.201Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-19T08:09:21.254Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-19T08:09:21.359Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-19T08:09:21.405Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:6

2016-01-19T08:09:21.406Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-19T08:09:21.417Z - debug: Device presented: motorola-XT1072 (android) unittest socket:7

2016-01-19T08:09:21.417Z - info: Discarding surplus device: motorola-XT1072

2016-01-19T08:09:21.450Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:8

2016-01-19T08:09:21.453Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-19T08:09:21.517Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-01-19T08:09:21.537Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-19T08:09:21.545Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-19T08:09:21.583Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:9

2016-01-19T08:09:21.584Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-19T08:09:21.642Z - info: Running on android test: failed to get mobile documents path

2016-01-19T08:09:21.659Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:11

2016-01-19T08:09:21.660Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-19T08:09:21.675Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:10

2016-01-19T08:09:21.676Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-19T08:09:21.699Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-19T08:09:21.752Z - info: Running on android test: #init should register the networkChanged event

2016-01-19T08:09:21.798Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-19T08:09:21.826Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-19T08:09:21.888Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-19T08:09:21.908Z - debug: Socket disconnected: transport close 5 (HTC-HTC Desire 820)

2016-01-19T08:09:22.000Z - debug: Socket disconnected: transport close 9 (LGE-Nexus 5)

2016-01-19T08:09:22.012Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-19T08:09:22.067Z - debug: Socket disconnected: transport close 6 (samsung-SM-A500FU)

2016-01-19T08:09:22.106Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-19T08:09:22.124Z - debug: Socket disconnected: transport close 8 (samsung-SM-A300FU)

2016-01-19T08:09:22.130Z - debug: Socket disconnected: transport close 7 (motorola-XT1072)

2016-01-19T08:09:22.164Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-19T08:09:22.253Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-19T08:09:22.371Z - info: Running on ios test: failed to get mobile documents path

2016-01-19T08:09:22.417Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-19T08:09:22.429Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-19T08:09:22.450Z - debug: Socket disconnected: transport close 10 (samsung-SM-G900F)

2016-01-19T08:09:22.499Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-19T08:09:22.545Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-19T08:09:22.588Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-19T08:09:22.635Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-19T08:09:22.716Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-19T08:09:22.771Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-19T08:09:22.786Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:12

2016-01-19T08:09:22.787Z - info: Discarding surplus device: HTC-HTC Desire 820

2016-01-19T08:09:22.844Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-19T08:09:22.987Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:13

2016-01-19T08:09:22.989Z - info: Discarding surplus device: samsung-SM-A300FU

2016-01-19T08:09:23.027Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-19T08:09:23.089Z - info: Running on ios test: #init should register the networkChanged event

2016-01-19T08:09:23.114Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:14

2016-01-19T08:09:23.115Z - info: Discarding surplus device: LGE-LG-D722

2016-01-19T08:09:23.153Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-19T08:09:23.274Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-19T08:09:23.350Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-19T08:09:23.402Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-19T08:09:23.457Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:15

2016-01-19T08:09:23.458Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-19T08:09:23.484Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-19T08:09:23.651Z - debug: Socket disconnected: transport close 13 (samsung-SM-A300FU)

2016-01-19T08:09:23.743Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:16

2016-01-19T08:09:23.744Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-19T08:09:23.796Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:17

2016-01-19T08:09:23.797Z - info: Discarding surplus device: HTC-HTC One M8s

2016-01-19T08:09:23.837Z - debug: Socket disconnected: transport close 12 (HTC-HTC Desire 820)

2016-01-19T08:09:24.042Z - debug: Socket disconnected: transport close 11 (Apple-Iphone6-1)

2016-01-19T08:09:24.366Z - debug: Socket disconnected: transport close 14 (LGE-LG-D722)

2016-01-19T08:09:24.399Z - debug: Socket disconnected: transport close 16 (samsung-SM-A500FU)

2016-01-19T08:09:24.454Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-19T08:09:24.541Z - debug: Socket disconnected: transport close 15 (samsung-SM-G900F)

2016-01-19T08:09:24.571Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-19T08:09:24.674Z - debug: Socket disconnected: transport close 17 (HTC-HTC One M8s)

2016-01-19T08:09:24.691Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-19T08:09:24.799Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-19T08:09:24.948Z - debug: Device presented: LGE-LG-D802 (android) unittest socket:18

2016-01-19T08:09:24.949Z - info: Discarding surplus device: LGE-LG-D802

2016-01-19T08:09:24.954Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-19T08:09:25.003Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-19T08:09:25.053Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-19T08:09:25.108Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-19T08:09:25.173Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-19T08:09:25.229Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-19T08:09:25.540Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:19

2016-01-19T08:09:25.541Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-01-19T08:09:25.570Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-19T08:09:25.701Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-19T08:09:25.722Z - debug: Socket disconnected: transport close 18 (LGE-LG-D802)

2016-01-19T08:09:26.702Z - debug: Device presented: motorola-XT1039 (android) unittest socket:20

2016-01-19T08:09:26.703Z - info: Discarding surplus device: motorola-XT1039

2016-01-19T08:09:26.815Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-19T08:09:27.197Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-19T08:09:27.581Z - debug: Socket disconnected: transport close 20 (motorola-XT1039)

2016-01-19T08:09:28.306Z - debug: Socket disconnected: transport close 19 (Apple-Iphone5s-1)

2016-01-19T08:09:31.106Z - debug: Device presented: samsung-SM-G800F (android) unittest socket:21

2016-01-19T08:09:31.107Z - info: Discarding surplus device: samsung-SM-G800F

2016-01-19T08:09:32.200Z - debug: Socket disconnected: transport close 21 (samsung-SM-G800F)

2016-01-19T08:09:34.604Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-19T08:09:41.420Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-19T08:09:47.703Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-19T08:09:55.903Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-19T08:10:09.693Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-19T08:10:11.324Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-19T08:10:12.133Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-19T08:10:48.095Z - debug: Socket disconnected: ping timeout 0 (LGE-Nexus 5)

2016-01-19T08:11:02.954Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:22

2016-01-19T08:11:02.957Z - info: Discarding surplus device: LGE-LG-D855

2016-01-19T08:11:03.400Z - debug: Socket disconnected: transport close 22 (LGE-LG-D855)

2016-01-19T08:12:05.149Z - debug: Socket disconnected: ping timeout 2 (Apple-Iphone5-1)

2016-01-19T08:21:45.884Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-01-19T08:27:17.584Z - debug: Socket disconnected: transport close 1 (samsung-SM-N910C)


 
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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
Android task is completed. [SUCCESS]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on FA55PYS00566 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on HT574YC04723 
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/564317025f150b2_Temp_commit_to_check_OS_versions_in_CI__vjrantal/thali09_LGE-Nexus 5.md)





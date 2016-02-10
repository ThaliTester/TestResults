#### Test 58752353dc32d9f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-10T14:14:52.215Z - info: listening on *:3000

2016-02-10T14:14:52.660Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:1

2016-02-10T14:14:52.670Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:2

2016-02-10T14:14:52.674Z - info: Required number of android devices presented (2)

2016-02-10T14:14:52.677Z - info: Starting unit test run for platform: android

2016-02-10T14:14:52.715Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:3

2016-02-10T14:14:52.717Z - info: Discarding surplus device: LGE-LG-D855

2016-02-10T14:14:52.728Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:4

2016-02-10T14:14:52.729Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-10T14:14:53.104Z - info: Running on android test: multiplex can send data

2016-02-10T14:14:53.260Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-02-10T14:14:53.261Z - info: Discarding surplus device: LGE-LG-H815

2016-02-10T14:14:53.350Z - info: Running on android test: enqueue and run in order

2016-02-10T14:14:53.579Z - debug: Socket disconnected: transport close 3 (LGE-LG-D855)

2016-02-10T14:14:53.685Z - info: Running on android test: basic

2016-02-10T14:14:53.692Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:6

2016-02-10T14:14:53.809Z - debug: Socket disconnected: transport close 4 (samsung-SM-G900F)

2016-02-10T14:14:53.822Z - info: Running on android test: another

2016-02-10T14:14:53.916Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-10T14:14:54.260Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-10T14:14:54.288Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-02-10T14:14:54.749Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:7

2016-02-10T14:14:54.753Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-10T14:14:54.765Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-10T14:14:54.912Z - info: Running on android test: failed to get mobile documents path

2016-02-10T14:14:55.025Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-10T14:14:55.134Z - info: Running on android test: #init should register the networkChanged event

2016-02-10T14:14:55.198Z - debug: Socket disconnected: transport close 7 (LGE-Nexus 5)

2016-02-10T14:14:55.272Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-10T14:14:55.392Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-10T14:14:55.449Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-02-10T14:14:55.451Z - info: Required number of ios devices presented (2)

2016-02-10T14:14:55.452Z - info: Starting unit test run for platform: ios

2016-02-10T14:14:55.497Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-10T14:14:55.613Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-10T14:14:55.694Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-10T14:14:55.795Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-10T14:14:55.841Z - info: Running on ios test: multiplex can send data

2016-02-10T14:14:55.879Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-10T14:14:55.998Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-10T14:14:56.131Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-10T14:14:56.242Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-10T14:14:56.345Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-10T14:14:56.387Z - info: Running on ios test: enqueue and run in order

2016-02-10T14:14:56.436Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-10T14:14:56.555Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-10T14:14:56.718Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-10T14:14:56.836Z - info: Running on android test: #start should fail if called twice in a row

2016-02-10T14:14:56.949Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-10T14:14:57.039Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-10T14:14:57.071Z - info: Running on ios test: basic

2016-02-10T14:14:57.101Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-10T14:14:57.102Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-10T14:14:57.152Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-10T14:14:57.279Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-10T14:14:57.321Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:9

2016-02-10T14:14:57.322Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-10T14:14:57.561Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-10T14:14:57.566Z - info: Running on ios test: another

2016-02-10T14:14:57.573Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-10T14:14:57.675Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-10T14:14:57.918Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-10T14:14:57.962Z - debug: Socket disconnected: transport close 9 (motorola-Nexus 6)

2016-02-10T14:14:58.765Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-10T14:15:01.654Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:10

2016-02-10T14:15:01.655Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-10T14:15:02.350Z - debug: Socket disconnected: transport close 10 (samsung-SM-G900F)

2016-02-10T14:15:10.623Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-10T14:15:14.313Z - info: Running on ios test: failed to get mobile documents path

2016-02-10T14:15:16.868Z - debug: Device presented: motorola-XT1072 (android) unittest socket:11

2016-02-10T14:15:16.871Z - info: Discarding surplus device: motorola-XT1072

2016-02-10T14:15:17.650Z - debug: Socket disconnected: transport close 11 (motorola-XT1072)

2016-02-10T14:15:19.170Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-10T14:15:23.717Z - info: Running on ios test: #init should register the networkChanged event

2016-02-10T14:15:27.535Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-10T14:15:28.048Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-10T14:15:28.495Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-10T14:15:28.847Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-10T14:15:29.531Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-10T14:15:29.878Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-10T14:15:30.219Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-10T14:15:30.731Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-10T14:15:38.452Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-10T14:15:38.792Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-10T14:15:39.128Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-10T14:15:39.394Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-10T14:15:39.871Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-10T14:15:40.209Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-10T14:15:40.715Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-10T14:15:41.056Z - info: Running on ios test: #startListeningForAdvertisements should fail if start not called

2016-02-10T14:15:43.457Z - info: Running on ios test: should be able to call #stopListeningForAdvertisements many times

2016-02-10T14:15:43.807Z - info: Running on ios test: should be able to call #startListeningForAdvertisements many times

2016-02-10T14:15:43.933Z - info: Running on ios test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-10T14:15:44.110Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-10T14:15:44.237Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-10T14:15:44.676Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-10T14:15:45.779Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-10T14:15:47.694Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-10T14:15:48.230Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-10T14:15:54.167Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-10T14:15:59.958Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-10T14:16:07.339Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-10T14:16:22.737Z - debug: Socket disconnected: ping timeout 2 (HTC-HTC One M8s)

2016-02-10T14:19:32.037Z - debug: Socket disconnected: transport close 12 (NOT YET SET)

2016-02-10T14:19:32.043Z - debug: Socket disconnected: transport close 13 (NOT YET SET)

2016-02-10T14:19:32.240Z - debug: Socket disconnected: transport close 14 (NOT YET SET)

2016-02-10T14:19:47.393Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:15

2016-02-10T14:19:47.394Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-10T14:19:52.499Z - debug: Socket disconnected: transport close 15 (Apple-Iphone5-1)

2016-02-10T14:28:21.091Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-02-10T14:28:21.208Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-02-10T14:31:36.688Z - debug: Socket disconnected: transport close 1 (LGE-LG-D722)


 
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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58752353dc32d9f_Run_coordinated_desktop_tests_in_CI_vjrantal/thali09_LGE-Nexus 5.md)





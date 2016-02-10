#### Test 58918757c0fcaf3 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-10T17:10:04.164Z - info: listening on *:3000

2016-02-10T17:10:04.562Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-02-10T17:10:05.800Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:1

2016-02-10T17:10:06.105Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:2

2016-02-10T17:10:06.109Z - info: Required number of android devices presented (2)

2016-02-10T17:10:06.113Z - info: Starting unit test run for platform: android

2016-02-10T17:10:06.345Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-02-10T17:10:06.348Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-10T17:10:07.128Z - info: Running on android test: multiplex can send data

2016-02-10T17:10:07.361Z - info: Running on android test: enqueue and run in order

2016-02-10T17:10:07.491Z - debug: Socket disconnected: transport close 3 (samsung-SM-G900F)

2016-02-10T17:10:07.662Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:4

2016-02-10T17:10:07.665Z - info: Discarding surplus device: LGE-LG-H815

2016-02-10T17:10:07.681Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:5

2016-02-10T17:10:07.684Z - info: Discarding surplus device: HTC-HTC One M8s

2016-02-10T17:10:07.712Z - info: Running on android test: basic

2016-02-10T17:10:07.807Z - info: Running on android test: another

2016-02-10T17:10:07.867Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-10T17:10:08.255Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-10T17:10:08.479Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:6

2016-02-10T17:10:08.481Z - info: Required number of ios devices presented (2)

2016-02-10T17:10:08.482Z - info: Starting unit test run for platform: ios

2016-02-10T17:10:08.530Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-10T17:10:08.613Z - debug: Socket disconnected: transport close 4 (LGE-LG-H815)

2016-02-10T17:10:08.623Z - info: Running on android test: failed to get mobile documents path

2016-02-10T17:10:08.690Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-10T17:10:08.761Z - debug: Socket disconnected: transport close 5 (HTC-HTC One M8s)

2016-02-10T17:10:08.778Z - info: Running on android test: #init should register the networkChanged event

2016-02-10T17:10:08.877Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-10T17:10:08.993Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-10T17:10:09.091Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-10T17:10:09.162Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:7

2016-02-10T17:10:09.165Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-10T17:10:09.197Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-10T17:10:09.277Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-10T17:10:09.386Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-10T17:10:09.474Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-10T17:10:09.566Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-10T17:10:09.648Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-10T17:10:09.718Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-10T17:10:09.789Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-10T17:10:09.796Z - debug: Socket disconnected: transport close 7 (motorola-Nexus 6)

2016-02-10T17:10:09.866Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-10T17:10:09.973Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-10T17:10:10.066Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-10T17:10:10.176Z - info: Running on android test: #start should fail if called twice in a row

2016-02-10T17:10:10.620Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-10T17:10:10.624Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-10T17:10:11.001Z - info: Running on ios test: multiplex can send data

2016-02-10T17:10:11.298Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-10T17:10:12.989Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-10T17:10:12.991Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-10T17:10:13.697Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-10T17:10:18.950Z - info: Running on ios test: enqueue and run in order

2016-02-10T17:10:19.564Z - info: Running on ios test: basic

2016-02-10T17:10:23.163Z - info: Running on ios test: another

2016-02-10T17:10:23.303Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-10T17:10:24.097Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-10T17:10:30.021Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-10T17:10:31.938Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:10

2016-02-10T17:10:31.940Z - info: Discarding surplus device: LGE-LG-D855

2016-02-10T17:10:32.808Z - debug: Socket disconnected: transport close 10 (LGE-LG-D855)

2016-02-10T17:10:35.732Z - info: Running on ios test: failed to get mobile documents path

2016-02-10T17:10:40.038Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-10T17:10:40.508Z - info: Running on ios test: #init should register the networkChanged event

2016-02-10T17:10:40.862Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-10T17:10:41.282Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-10T17:10:41.722Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-10T17:10:42.144Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-10T17:10:42.492Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-10T17:10:42.843Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-10T17:10:43.181Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-10T17:10:43.524Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-10T17:10:43.871Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-10T17:10:44.213Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-10T17:10:44.564Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-10T17:10:44.809Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-10T17:10:44.927Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-10T17:10:45.062Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-10T17:10:45.183Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-10T17:23:36.347Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-02-10T17:23:36.392Z - debug: Socket disconnected: transport close 6 (Apple-Iphone6-1)

2016-02-10T17:26:52.553Z - debug: Socket disconnected: transport close 1 (LGE-LG-D722)

2016-02-10T17:26:54.524Z - debug: Socket disconnected: transport close 2 (LGE-Nexus 5)


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58918757c0fcaf3_Network_change_behavior_for_thaliWifiInfrastructure_vjrantal/thali09_LGE-Nexus 5.md)





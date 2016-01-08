#### Test 54970261ac9928f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-08T16:15:57.451Z - info: listening on *:3000

2016-01-08T16:15:57.971Z - debug: Device presented: UNITTEST-0.4721144140772535 (android) unittest socket:0

2016-01-08T16:15:57.995Z - debug: Device presented: UNITTEST-0.7559135123425266 (android) unittest socket:1

2016-01-08T16:15:58.029Z - debug: Device presented: UNITTEST-0.6311396994210046 (ios) unittest socket:2

2016-01-08T16:15:58.649Z - debug: Device presented: UNITTEST-0.7031760696572316 (android) unittest socket:3

2016-01-08T16:15:58.700Z - debug: Device presented: UNITTEST-0.17601670462422503 (android) unittest socket:4

2016-01-08T16:15:58.776Z - debug: Device presented: UNITTEST-0.3146765186222562 (android) unittest socket:5

2016-01-08T16:15:58.928Z - debug: Device presented: UNITTEST-0.8700999262505068 (ios) unittest socket:6

2016-01-08T16:15:58.929Z - info: Required number of devices presented

2016-01-08T16:15:58.933Z - info: Starting unit test run for platform: ios

2016-01-08T16:15:59.201Z - info: Running test: multiplex can send data

2016-01-08T16:15:59.861Z - debug: Device presented: UNITTEST-0.3412887943016627 (ios) unittest socket:7

2016-01-08T16:15:59.862Z - info: Discarding surplus device: UNITTEST-0.3412887943016627

2016-01-08T16:15:59.914Z - debug: Device presented: UNITTEST-0.7466432181757434 (android) unittest socket:8

2016-01-08T16:15:59.947Z - debug: Device presented: UNITTEST-0.3991367780489544 (android) unittest socket:10

2016-01-08T16:15:59.967Z - debug: Device presented: UNITTEST-0.9165489127426778 (android) unittest socket:9

2016-01-08T16:16:00.193Z - debug: Device presented: UNITTEST-0.8342475367162469 (android) unittest socket:11

2016-01-08T16:16:00.401Z - debug: Device presented: UNITTEST-0.0809922599325057 (android) unittest socket:12

2016-01-08T16:16:00.622Z - debug: Device presented: UNITTEST-0.342439566122516 (android) unittest socket:13

2016-01-08T16:16:01.115Z - debug: Device presented: UNITTEST-0.6414976193204325 (android) unittest socket:14

2016-01-08T16:16:01.273Z - debug: Device presented: UNITTEST-0.22089058353014013 (android) unittest socket:15

2016-01-08T16:16:01.499Z - debug: Device presented: UNITTEST-0.5885385039895511 (android) unittest socket:16

2016-01-08T16:16:02.059Z - debug: Device presented: UNITTEST-0.2861338733719405 (android) unittest socket:17

2016-01-08T16:16:02.382Z - debug: Device presented: UNITTEST-0.3438487404424525 (android) unittest socket:18

2016-01-08T16:16:02.543Z - debug: Device presented: UNITTEST-0.4560743679837269 (android) unittest socket:19

2016-01-08T16:16:02.571Z - debug: Device presented: UNITTEST-0.7619919244172022 (ios) unittest socket:20

2016-01-08T16:16:02.575Z - info: Discarding surplus device: UNITTEST-0.7619919244172022

2016-01-08T16:16:03.042Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.3412887943016627)

2016-01-08T16:16:05.247Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.7619919244172022)

2016-01-08T16:16:13.982Z - debug: Device presented: UNITTEST-0.69837526399277 (android) unittest socket:21

2016-01-08T16:16:16.870Z - debug: Device presented: UNITTEST-0.7167672609558433 (android) unittest socket:22

2016-01-08T16:16:16.871Z - info: Required number of devices presented

2016-01-08T16:16:16.875Z - info: Starting unit test run for platform: android

2016-01-08T16:16:21.085Z - info: Running test: multiplex can send data

2016-01-08T16:16:46.400Z - info: Running test: basic

2016-01-08T16:16:50.901Z - info: Running test: another

2016-01-08T16:16:58.682Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-08T16:17:05.869Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-08T16:17:10.962Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-08T16:17:17.089Z - info: Running test: failed to get mobile documents path

2016-01-08T16:17:27.136Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-08T16:17:30.198Z - info: Running test: #init should register the networkChanged event

2016-01-08T16:17:31.929Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-08T16:17:32.094Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-08T16:17:32.278Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-08T16:17:32.452Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-08T16:17:32.643Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-08T16:17:33.480Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-08T16:17:40.435Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-08T16:17:47.795Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-08T16:18:00.697Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-08T16:18:12.354Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-08T16:18:28.317Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-08T16:18:36.926Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-08T16:18:46.735Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-08T16:18:57.786Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-08T16:19:20.926Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-08T16:19:23.126Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.9165489127426778)

2016-01-08T16:19:23.308Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.7167672609558433)

2016-01-08T16:19:23.351Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.69837526399277)

2016-01-08T16:19:23.688Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.7031760696572316)

2016-01-08T16:19:23.696Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.2861338733719405)

2016-01-08T16:19:25.005Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.5885385039895511)

2016-01-08T16:38:34.190Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.6311396994210046)

2016-01-08T16:38:34.264Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.8700999262505068)

2016-01-08T16:42:24.091Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.3146765186222562)

2016-01-08T16:42:25.851Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.3438487404424525)

2016-01-08T16:42:26.527Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.8342475367162469)

2016-01-08T16:42:26.582Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.7466432181757434)

2016-01-08T16:42:28.026Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.17601670462422503)

2016-01-08T16:42:28.579Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.7559135123425266)

2016-01-08T16:42:50.912Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.4721144140772535)

2016-01-08T16:43:27.602Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.22089058353014013)

2016-01-08T16:43:29.440Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.6414976193204325)

2016-01-08T16:43:59.299Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.3991367780489544)

2016-01-08T16:44:01.416Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.342439566122516)

2016-01-08T16:44:03.644Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.0809922599325057)

2016-01-08T16:46:19.071Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.4560743679837269)


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Android task is completed. [FAILED]
```
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali03_LGE-LG-D855.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/54970261ac9928f_Switch_to_Unit_Tests_tobybrad/thali09_LGE-Nexus 5.md)





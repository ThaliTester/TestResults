#### Test 549702610263d9b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-05T17:36:29.657Z - info: listening on *:3000

2016-01-05T17:36:30.324Z - debug: Device presented: UNITTEST-0.5623402532010092 (android) unittest socket:0

2016-01-05T17:36:30.334Z - debug: Device presented: UNITTEST-0.705627245928782 (android) unittest socket:1

2016-01-05T17:36:30.476Z - debug: Device presented: UNITTEST-0.7249752750806948 (android) unittest socket:2

2016-01-05T17:36:31.605Z - debug: Device presented: UNITTEST-0.7002718641575749 (android) unittest socket:3

2016-01-05T17:36:31.674Z - debug: Device presented: UNITTEST-0.2555441347534224 (android) unittest socket:4

2016-01-05T17:36:31.955Z - debug: Device presented: UNITTEST-0.49733606874958314 (android) unittest socket:6

2016-01-05T17:36:32.023Z - debug: Device presented: UNITTEST-0.31142566859207654 (ios) unittest socket:5

2016-01-05T17:36:32.153Z - debug: Device presented: UNITTEST-0.2193250153804981 (android) unittest socket:7

2016-01-05T17:36:32.955Z - debug: Device presented: UNITTEST-0.6217446382418562 (ios) unittest socket:8

2016-01-05T17:36:32.956Z - info: Required number of devices presented

2016-01-05T17:36:32.960Z - info: Starting unit test run for platform: ios

2016-01-05T17:36:33.019Z - debug: Device presented: UNITTEST-0.1613085135240474 (android) unittest socket:9

2016-01-05T17:36:33.079Z - debug: Device presented: UNITTEST-0.554533708549163 (android) unittest socket:10

2016-01-05T17:36:33.162Z - debug: Device presented: UNITTEST-0.6257643228965077 (android) unittest socket:11

2016-01-05T17:36:33.314Z - debug: Device presented: UNITTEST-0.4681877322172031 (android) unittest socket:12

2016-01-05T17:36:33.389Z - info: Running test: multiplex can send data

2016-01-05T17:36:33.511Z - debug: Device presented: UNITTEST-0.10390162445562678 (ios) unittest socket:13

2016-01-05T17:36:33.633Z - debug: Device presented: UNITTEST-0.07344997624019245 (android) unittest socket:14

2016-01-05T17:36:34.014Z - debug: Device presented: UNITTEST-0.5584914974044489 (android) unittest socket:15

2016-01-05T17:36:34.148Z - debug: Device presented: UNITTEST-0.09715619194222236 (android) unittest socket:16

2016-01-05T17:36:34.510Z - debug: Device presented: UNITTEST-0.8762860475605704 (android) unittest socket:17

2016-01-05T17:36:34.690Z - debug: Device presented: UNITTEST-0.610799458472619 (ios) unittest socket:18

2016-01-05T17:36:34.750Z - debug: Device presented: UNITTEST-0.1921676971887074 (android) unittest socket:19

2016-01-05T17:36:34.756Z - debug: Device presented: UNITTEST-0.5939982695698172 (android) unittest socket:20

2016-01-05T17:36:35.892Z - info: Running test: basic

2016-01-05T17:36:36.188Z - info: Running test: another

2016-01-05T17:36:36.480Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-05T17:36:36.987Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-05T17:36:37.427Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-05T17:36:37.798Z - info: Running test: failed to get mobile documents path

2016-01-05T17:36:38.082Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-05T17:36:38.402Z - info: Running test: #init should register the networkChanged event

2016-01-05T17:36:38.715Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-05T17:36:39.013Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-05T17:36:39.369Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-05T17:36:39.710Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-05T17:36:40.006Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-05T17:36:40.379Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-05T17:36:40.716Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-05T17:36:41.004Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-05T17:36:41.291Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-05T17:36:41.601Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-05T17:36:41.927Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-05T17:36:42.223Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-05T17:36:42.526Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-05T17:36:42.816Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-05T17:36:43.116Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-05T17:36:43.725Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-05T17:36:44.584Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-05T17:36:45.304Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-05T17:36:45.406Z - debug: Device presented: UNITTEST-0.12054984434691252 (android) unittest socket:21

2016-01-05T17:36:46.092Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-05T17:36:53.324Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-05T17:36:58.685Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-05T17:37:03.578Z - info: Running test: ThaliEmitter handles socket disconnect correctly

2016-01-05T17:37:13.020Z - info: Running test: ThaliReplicationManager can call start without error

2016-01-05T17:37:17.055Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.6217446382418562)

2016-01-05T17:37:25.600Z - debug: Device presented: UNITTEST-0.934922949435458 (android) unittest socket:22

2016-01-05T17:37:25.614Z - info: Required number of devices presented

2016-01-05T17:37:25.616Z - info: Starting unit test run for platform: android

2016-01-05T17:37:28.403Z - info: Running test: multiplex can send data

2016-01-05T17:37:37.014Z - info: Running test: basic

2016-01-05T17:37:44.763Z - info: Running test: another

2016-01-05T17:37:47.663Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-05T17:37:54.865Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-05T17:38:00.745Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-05T17:38:08.126Z - info: Running test: failed to get mobile documents path

2016-01-05T17:38:15.302Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-05T17:38:20.397Z - info: Running test: #init should register the networkChanged event

2016-01-05T17:38:26.926Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-05T17:38:32.667Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-05T17:38:36.932Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-05T17:38:39.428Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-05T17:38:47.373Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-05T17:38:54.772Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-05T17:39:06.016Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-05T17:39:13.169Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-05T17:39:24.232Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-05T17:39:30.980Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-05T17:39:38.348Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-05T17:39:41.833Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-05T17:39:48.583Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-05T17:39:57.371Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-05T17:40:04.323Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-05T17:40:06.896Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.934922949435458)

2016-01-05T17:40:06.910Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.09715619194222236)

2016-01-05T17:40:06.952Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.12054984434691252)

2016-01-05T17:40:08.290Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.2555441347534224)

2016-01-05T17:40:09.757Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.07344997624019245)

2016-01-05T17:40:09.876Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.554533708549163)

2016-01-05T17:58:38.431Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.610799458472619)

2016-01-05T17:58:38.535Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.10390162445562678)

2016-01-05T17:58:38.562Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.31142566859207654)

2016-01-05T18:02:37.153Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.7002718641575749)

2016-01-05T18:02:38.020Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.2193250153804981)

2016-01-05T18:02:39.101Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.5584914974044489)

2016-01-05T18:02:39.505Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.705627245928782)

2016-01-05T18:02:41.272Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.1613085135240474)

2016-01-05T18:02:43.687Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.4681877322172031)

2016-01-05T18:03:02.713Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.7249752750806948)

2016-01-05T18:03:40.629Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.5623402532010092)

2016-01-05T18:03:42.179Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.6257643228965077)

2016-01-05T18:04:20.150Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.5939982695698172)

2016-01-05T18:04:22.847Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.49733606874958314)

2016-01-05T18:04:25.385Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.8762860475605704)

2016-01-05T18:07:13.445Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.1921676971887074)


 
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
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702610263d9b_Switch_to_Unit_Tests_tobybrad/thali09_LGE-Nexus 5.md)





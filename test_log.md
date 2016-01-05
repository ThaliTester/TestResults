#### Test 54970261fc259e9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-05T16:29:57.833Z - info: listening on *:3000

2016-01-05T16:29:58.334Z - debug: Device presented: UNITTEST-0.5092622174850912 (android) unittest socket:1

2016-01-05T16:29:58.343Z - info: 1

2016-01-05T16:29:58.344Z - info: 2

2016-01-05T16:29:58.365Z - debug: Device presented: UNITTEST-0.1499003483618807 (ios) unittest socket:0

2016-01-05T16:29:58.366Z - info: 1

2016-01-05T16:29:58.369Z - info: 2

2016-01-05T16:29:58.396Z - debug: Device presented: UNITTEST-0.7463179156952353 (android) unittest socket:2

2016-01-05T16:29:58.398Z - info: 2

2016-01-05T16:29:58.399Z - info: 2

2016-01-05T16:29:58.400Z - info: Required number of devices presented

2016-01-05T16:29:58.404Z - info: Starting unit test run for platform: android

2016-01-05T16:29:58.543Z - debug: Device presented: UNITTEST-0.7544489532164939 (ios) unittest socket:3

2016-01-05T16:29:58.545Z - info: 2

2016-01-05T16:29:58.545Z - info: 2

2016-01-05T16:29:58.546Z - info: Required number of devices presented

2016-01-05T16:29:58.548Z - info: Starting unit test run for platform: ios

2016-01-05T16:29:58.647Z - info: Running test: multiplex can send data

2016-01-05T16:29:58.742Z - debug: Device presented: UNITTEST-0.2820520252948763 (ios) unittest socket:4

2016-01-05T16:29:58.744Z - info: 3
2016-01-05T16:29:58.744Z - info: 2

2016-01-05T16:29:58.876Z - info: Running test: basic

2016-01-05T16:29:59.048Z - info: Running test: another

2016-01-05T16:29:59.169Z - debug: Device presented: UNITTEST-0.4470162237269726 (android) unittest socket:5

2016-01-05T16:29:59.171Z - info: 3

2016-01-05T16:29:59.172Z - info: 2

2016-01-05T16:29:59.228Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-05T16:29:59.486Z - debug: Device presented: UNITTEST-0.24052093630144145 (android) unittest socket:6

2016-01-05T16:29:59.487Z - info: 4

2016-01-05T16:29:59.488Z - info: 2

2016-01-05T16:29:59.496Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-05T16:29:59.757Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-05T16:29:59.870Z - debug: Device presented: UNITTEST-0.06851606847758174 (android) unittest socket:7

2016-01-05T16:29:59.871Z - info: 5

2016-01-05T16:29:59.872Z - info: 2

2016-01-05T16:29:59.918Z - info: Running test: failed to get mobile documents path

2016-01-05T16:29:59.985Z - debug: Device presented: UNITTEST-0.21103295442367576 (ios) unittest socket:8

2016-01-05T16:29:59.986Z - info: 4

2016-01-05T16:29:59.987Z - info: 2

2016-01-05T16:30:00.087Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-05T16:30:00.107Z - debug: Device presented: UNITTEST-0.9984751373305255 (android) unittest socket:9

2016-01-05T16:30:00.108Z - info: 6

2016-01-05T16:30:00.108Z - info: 2

2016-01-05T16:30:00.204Z - info: Running test: #init should register the networkChanged event

2016-01-05T16:30:00.338Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-05T16:30:00.481Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-05T16:30:00.575Z - debug: Device presented: UNITTEST-0.11327442039167845 (android) unittest socket:10

2016-01-05T16:30:00.576Z - info: 7

2016-01-05T16:30:00.577Z - info: 2

2016-01-05T16:30:00.631Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-05T16:30:00.763Z - debug: Device presented: UNITTEST-0.20433735660271057 (android) unittest socket:11

2016-01-05T16:30:00.767Z - info: 8

2016-01-05T16:30:00.768Z - info: 2

2016-01-05T16:30:00.781Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-05T16:30:00.811Z - debug: Device presented: UNITTEST-0.38887226203891934 (android) unittest socket:12

2016-01-05T16:30:00.812Z - info: 9

2016-01-05T16:30:00.813Z - info: 2

2016-01-05T16:30:00.947Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-05T16:30:01.007Z - info: Running test: multiplex can send data

2016-01-05T16:30:01.108Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-05T16:30:01.304Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-05T16:30:01.477Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-05T16:30:01.516Z - debug: Device presented: UNITTEST-0.059038729479631846 (android) unittest socket:13

2016-01-05T16:30:01.517Z - info: 10
2016-01-05T16:30:01.518Z - info: 2

2016-01-05T16:30:01.634Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-05T16:30:01.783Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-05T16:30:01.857Z - debug: Device presented: UNITTEST-0.7250815156325529 (android) unittest socket:14

2016-01-05T16:30:01.858Z - info: 11

2016-01-05T16:30:01.861Z - info: 2

2016-01-05T16:30:02.040Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-05T16:30:02.075Z - debug: Device presented: UNITTEST-0.6187848472053704 (android) unittest socket:15

2016-01-05T16:30:02.076Z - info: 12

2016-01-05T16:30:02.077Z - info: 2

2016-01-05T16:30:02.086Z - debug: Device presented: UNITTEST-0.2538178717799716 (android) unittest socket:17

2016-01-05T16:30:02.087Z - info: 13

2016-01-05T16:30:02.088Z - info: 2

2016-01-05T16:30:02.103Z - debug: Device presented: UNITTEST-0.5410239195160005 (android) unittest socket:16

2016-01-05T16:30:02.104Z - info: 14

2016-01-05T16:30:02.105Z - info: 2

2016-01-05T16:30:02.202Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-05T16:30:02.334Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-05T16:30:02.459Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-05T16:30:02.613Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-05T16:30:02.765Z - debug: Device presented: UNITTEST-0.7163978343236889 (android) unittest socket:18

2016-01-05T16:30:02.766Z - info: 15

2016-01-05T16:30:02.767Z - info: 2

2016-01-05T16:30:02.838Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.7463179156952353)

2016-01-05T16:30:02.863Z - debug: Device presented: UNITTEST-0.7814287219177957 (android) unittest socket:19

2016-01-05T16:30:02.864Z - info: 16

2016-01-05T16:30:02.880Z - info: 2

2016-01-05T16:30:03.226Z - debug: Device presented: UNITTEST-0.5248022805795235 (android) unittest socket:20

2016-01-05T16:30:03.227Z - info: 17

2016-01-05T16:30:03.228Z - info: 2

2016-01-05T16:30:04.328Z - info: Running test: basic

2016-01-05T16:30:04.617Z - info: Running test: another

2016-01-05T16:30:04.979Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-05T16:30:05.453Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-05T16:30:05.876Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-05T16:30:06.234Z - info: Running test: failed to get mobile documents path

2016-01-05T16:30:06.540Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-05T16:30:06.846Z - info: Running test: #init should register the networkChanged event

2016-01-05T16:30:07.157Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-05T16:30:07.463Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-05T16:30:07.746Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-05T16:30:08.030Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-05T16:30:08.335Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-05T16:30:08.635Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-05T16:30:08.972Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-05T16:30:09.289Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-05T16:30:09.574Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-05T16:30:09.852Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-05T16:30:10.134Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-05T16:30:10.424Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-05T16:30:10.723Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-05T16:30:11.015Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-05T16:30:11.299Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-05T16:30:11.942Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-05T16:30:12.798Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-05T16:30:14.449Z - debug: Device presented: UNITTEST-0.6183317454580324 (android) unittest socket:21

2016-01-05T16:30:14.450Z - info: 18
2016-01-05T16:30:14.451Z - info: 2

2016-01-05T16:30:14.970Z - debug: Device presented: UNITTEST-0.8376665101202412 (android) unittest socket:22

2016-01-05T16:30:14.972Z - info: 19

2016-01-05T16:30:14.973Z - info: 2

2016-01-05T16:30:16.559Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.1499003483618807)

2016-01-05T16:52:00.676Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.2820520252948763)

2016-01-05T16:52:00.708Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.7544489532164939)

2016-01-05T16:52:00.737Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.21103295442367576)

2016-01-05T16:55:59.976Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.5092622174850912)

2016-01-05T16:56:00.261Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.9984751373305255)

2016-01-05T16:56:01.393Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.2538178717799716)

2016-01-05T16:56:02.128Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.38887226203891934)

2016-01-05T16:56:04.060Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.6187848472053704)

2016-01-05T16:56:06.317Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.11327442039167845)

2016-01-05T16:56:17.808Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.059038729479631846)

2016-01-05T16:56:34.382Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.20433735660271057)

2016-01-05T16:56:36.646Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.24052093630144145)

2016-01-05T16:57:02.688Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.4470162237269726)

2016-01-05T16:57:04.325Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.5410239195160005)

2016-01-05T16:57:08.078Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.7163978343236889)

2016-01-05T16:57:41.712Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.7250815156325529)

2016-01-05T16:57:43.996Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.7814287219177957)

2016-01-05T16:57:46.545Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.06851606847758174)

2016-01-05T17:00:09.604Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.8376665101202412)

2016-01-05T17:00:15.380Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.6183317454580324)

2016-01-05T17:00:16.837Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.5248022805795235)


 
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
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali02_LGE-Nexus 5.md)

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
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali03_LGE-LG-D855.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/54970261fc259e9_Switch_to_Unit_Tests_tobybrad/thali09_LGE-Nexus 5.md)





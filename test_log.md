#### Test 549702610b97681 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-08T23:08:28.198Z - info: listening on *:3000

2016-01-08T23:08:28.747Z - debug: Device presented: UNITTEST-0.2715739324625521 (android) unittest socket:0

2016-01-08T23:08:28.752Z - info: Discarding surplus device: UNITTEST-0.2715739324625521

2016-01-08T23:08:28.765Z - debug: Device presented: UNITTEST-0.2799245278062581 (android) unittest socket:1

2016-01-08T23:08:28.769Z - info: Discarding surplus device: UNITTEST-0.2799245278062581

2016-01-08T23:08:28.923Z - debug: Device presented: UNITTEST-0.2017276160161542 (android) unittest socket:2

2016-01-08T23:08:28.924Z - info: Discarding surplus device: UNITTEST-0.2017276160161542

2016-01-08T23:08:29.027Z - debug: Device presented: UNITTEST-0.6638361663600717 (android) unittest socket:3

2016-01-08T23:08:29.028Z - info: Discarding surplus device: UNITTEST-0.6638361663600717

2016-01-08T23:08:29.072Z - debug: Device presented: UNITTEST-0.9892544438329871 (ios) unittest socket:4

2016-01-08T23:08:29.389Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.2799245278062581)

2016-01-08T23:08:29.541Z - debug: Device presented: UNITTEST-0.4124366263870328 (ios) unittest socket:5

2016-01-08T23:08:29.542Z - info: Required number of ios devices presented (2)

2016-01-08T23:08:29.545Z - info: Starting unit test run for platform: ios

2016-01-08T23:08:29.580Z - debug: Device presented: UNITTEST-0.15468022930809378 (android) unittest socket:7

2016-01-08T23:08:29.581Z - info: Discarding surplus device: UNITTEST-0.15468022930809378

2016-01-08T23:08:29.586Z - debug: Device presented: UNITTEST-0.32800017686769534 (android) unittest socket:6

2016-01-08T23:08:29.587Z - info: Discarding surplus device: UNITTEST-0.32800017686769534

2016-01-08T23:08:29.828Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.6638361663600717)

2016-01-08T23:08:29.839Z - info: Running test: multiplex can send data

2016-01-08T23:08:29.934Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.2715739324625521)

2016-01-08T23:08:29.967Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.2017276160161542)

2016-01-08T23:08:29.985Z - debug: Device presented: UNITTEST-0.08189454649847083 (android) unittest socket:8

2016-01-08T23:08:29.986Z - info: Discarding surplus device: UNITTEST-0.08189454649847083

2016-01-08T23:08:30.102Z - debug: Device presented: UNITTEST-0.3730590315697929 (android) unittest socket:9

2016-01-08T23:08:30.103Z - info: Discarding surplus device: UNITTEST-0.3730590315697929

2016-01-08T23:08:30.117Z - info: Running test: basic

2016-01-08T23:08:30.172Z - info: Running test: another

2016-01-08T23:08:30.243Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.15468022930809378)

2016-01-08T23:08:30.249Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-08T23:08:30.445Z - debug: Device presented: UNITTEST-0.02884695841625473 (android) unittest socket:10

2016-01-08T23:08:30.447Z - info: Discarding surplus device: UNITTEST-0.02884695841625473

2016-01-08T23:08:30.514Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-08T23:08:30.520Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.32800017686769534)

2016-01-08T23:08:30.561Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.3730590315697929)

2016-01-08T23:08:30.602Z - debug: Device presented: UNITTEST-0.6683899913171256 (android) unittest socket:11

2016-01-08T23:08:30.603Z - info: Discarding surplus device: UNITTEST-0.6683899913171256

2016-01-08T23:08:30.721Z - debug: Device presented: UNITTEST-0.6293227240293489 (android) unittest socket:12

2016-01-08T23:08:30.722Z - info: Discarding surplus device: UNITTEST-0.6293227240293489

2016-01-08T23:08:30.758Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.08189454649847083)

2016-01-08T23:08:30.763Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-08T23:08:30.887Z - info: Running test: failed to get mobile documents path

2016-01-08T23:08:30.960Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-08T23:08:31.017Z - debug: Device presented: UNITTEST-0.7194915500167948 (android) unittest socket:13

2016-01-08T23:08:31.018Z - info: Discarding surplus device: UNITTEST-0.7194915500167948

2016-01-08T23:08:31.028Z - info: Running test: #init should register the networkChanged event

2016-01-08T23:08:31.130Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-08T23:08:31.198Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-08T23:08:31.260Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-08T23:08:31.298Z - debug: Device presented: UNITTEST-0.852576748732482 (ios) unittest socket:14

2016-01-08T23:08:31.300Z - info: Discarding surplus device: UNITTEST-0.852576748732482

2016-01-08T23:08:31.329Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-08T23:08:31.372Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.6293227240293489)

2016-01-08T23:08:31.410Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.6683899913171256)

2016-01-08T23:08:31.459Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-08T23:08:31.479Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.02884695841625473)

2016-01-08T23:08:31.520Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-08T23:08:31.621Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-08T23:08:31.657Z - debug: Device presented: UNITTEST-0.1538471638892852 (android) unittest socket:15

2016-01-08T23:08:31.658Z - info: Discarding surplus device: UNITTEST-0.1538471638892852

2016-01-08T23:08:31.704Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-08T23:08:31.767Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-08T23:08:31.834Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-08T23:08:31.953Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-08T23:08:31.958Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.7194915500167948)

2016-01-08T23:08:32.092Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-08T23:08:32.155Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-08T23:08:32.237Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-08T23:08:32.299Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-08T23:08:32.455Z - debug: Device presented: UNITTEST-0.30484022565022606 (android) unittest socket:16

2016-01-08T23:08:32.456Z - info: Discarding surplus device: UNITTEST-0.30484022565022606

2016-01-08T23:08:32.671Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.1538471638892852)

2016-01-08T23:08:32.690Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-08T23:08:32.696Z - debug: Device presented: UNITTEST-0.6854748972126012 (ios) unittest socket:17

2016-01-08T23:08:32.697Z - info: Discarding surplus device: UNITTEST-0.6854748972126012

2016-01-08T23:08:33.035Z - debug: Device presented: UNITTEST-0.8888255788762048 (android) unittest socket:18

2016-01-08T23:08:33.036Z - info: Discarding surplus device: UNITTEST-0.8888255788762048

2016-01-08T23:08:33.118Z - debug: Device presented: UNITTEST-0.9537344284439536 (android) unittest socket:19

2016-01-08T23:08:33.119Z - info: Discarding surplus device: UNITTEST-0.9537344284439536

2016-01-08T23:08:33.134Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.30484022565022606)

2016-01-08T23:08:33.152Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-08T23:08:33.290Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-08T23:08:33.680Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.9537344284439536)

2016-01-08T23:08:33.721Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-08T23:08:34.037Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.8888255788762048)

2016-01-08T23:08:34.124Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.852576748732482)

2016-01-08T23:08:34.379Z - debug: Device presented: UNITTEST-0.6086735466491733 (android) unittest socket:20

2016-01-08T23:08:34.380Z - info: Discarding surplus device: UNITTEST-0.6086735466491733

2016-01-08T23:08:34.901Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.6086735466491733)

2016-01-08T23:08:35.307Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.6854748972126012)

2016-01-08T23:08:43.604Z - debug: Device presented: UNITTEST-0.43791220888833926 (android) unittest socket:21

2016-01-08T23:08:43.605Z - info: Discarding surplus device: UNITTEST-0.43791220888833926

2016-01-08T23:08:45.308Z - debug: Device presented: UNITTEST-0.5031474336709516 (android) unittest socket:22

2016-01-08T23:08:45.309Z - info: Discarding surplus device: UNITTEST-0.5031474336709516

2016-01-08T23:08:46.825Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.43791220888833926)

2016-01-08T23:08:48.252Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.5031474336709516)

2016-01-08T23:08:49.585Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-08T23:09:08.917Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-08T23:09:14.997Z - info: Running test: ThaliEmitter handles socket disconnect correctly

2016-01-08T23:09:23.170Z - info: Running test: ThaliReplicationManager can call start without error

2016-01-08T23:09:25.217Z - info: Running test: ThaliReplicationManager receives identity

2016-01-08T23:09:27.595Z - info: Test run complete

2016-01-08T23:09:27.598Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-08T23:09:27.600Z - info: PLATFORM: ios

2016-01-08T23:09:27.601Z - info: RESULT: PASS
2016-01-08T23:09:27.602Z - info: 33 of 33 tests completed

2016-01-08T23:09:27.603Z - info: 33/33 passed (0 failures)

2016-01-08T23:09:27.604Z - info: --- Test Details ---


2016-01-08T23:09:27.604Z - info: multiplex can send data - pass

2016-01-08T23:09:27.605Z - info: basic - pass
2016-01-08T23:09:27.606Z - info: another - pass

2016-01-08T23:09:27.607Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-08T23:09:27.609Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-08T23:09:27.610Z - info: failed to extract public key because of corrupt pkcs12 file - pass
2016-01-08T23:09:27.611Z - info: failed to get mobile documents path - pass

2016-01-08T23:09:27.612Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-08T23:09:27.613Z - info: #init should register the networkChanged event - pass
2016-01-08T23:09:27.617Z - info: #startBroadcasting should throw on null device name - pass
2016-01-08T23:09:27.618Z - info: #startBroadcasting should throw on empty string device name - pass
2016-01-08T23:09:27.619Z - info: #startBroadcasting should throw on non-number port - pass
2016-01-08T23:09:27.619Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-08T23:09:27.620Z - info: #startBroadcasting should throw on negative port - pass
2016-01-08T23:09:27.621Z - info: #startBroadcasting should throw on too large port - pass
2016-01-08T23:09:27.622Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-08T23:09:27.623Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-08T23:09:27.623Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-08T23:09:27.624Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-08T23:09:27.625Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-01-08T23:09:27.625Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-08T23:09:27.626Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-08T23:09:27.627Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-08T23:09:27.630Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-08T23:09:27.634Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-08T23:09:27.635Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-08T23:09:27.635Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-08T23:09:27.636Z - info: ThaliEmitter can discover and connect to peers - pass

2016-01-08T23:09:27.637Z - info: ThaliEmitter can discover and connect to peers and then fail on double connect - pass
2016-01-08T23:09:27.638Z - info: ThaliEmitter can discover and connect to peers and then fail on double disconnect - pass
2016-01-08T23:09:27.639Z - info: ThaliEmitter handles socket disconnect correctly - pass
2016-01-08T23:09:27.639Z - info: ThaliReplicationManager can call start without error - pass
2016-01-08T23:09:27.640Z - info: ThaliReplicationManager receives identity - pass
2016-01-08T23:09:27.641Z - info: 

-== END ==-


```


Logs for system : 
```

android : No Error

ios : false
```


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Device test finished on 320414cd475f91e3 
Android task is completed. [SUCCESS]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Device test finished on 022678fb504e29b0 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Device test finished on 0c6a0f3c0bdb4e77 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/thali09_LGE-Nexus 5.md)


###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/549702610b97681_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5s-1.md)



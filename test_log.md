#### Test 5497026179923a9 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-11T10:54:16.273Z - info: listening on *:3000

2016-01-11T10:54:16.749Z - debug: Device presented: UNITTEST-0.05499246745314934 (android) unittest socket:1

2016-01-11T10:54:16.927Z - debug: Device presented: UNITTEST-0.10920010110875689 (ios) unittest socket:2

2016-01-11T10:54:17.027Z - debug: Device presented: UNITTEST-0.8671429465056992 (android) unittest socket:3

2016-01-11T10:54:17.029Z - info: Required number of android devices presented (2)

2016-01-11T10:54:17.032Z - info: Starting unit test run for platform: android

2016-01-11T10:54:17.081Z - debug: Device presented: UNITTEST-0.026858993033879508 (ios) unittest socket:0

2016-01-11T10:54:17.082Z - info: Required number of ios devices presented (2)

2016-01-11T10:54:17.083Z - info: Starting unit test run for platform: ios

2016-01-11T10:54:17.262Z - debug: Device presented: UNITTEST-0.006009945249277782 (android) unittest socket:4

2016-01-11T10:54:17.263Z - info: Discarding surplus device: UNITTEST-0.006009945249277782

2016-01-11T10:54:17.324Z - info: Running test: multiplex can send data

2016-01-11T10:54:17.444Z - debug: Device presented: UNITTEST-0.9471115627568092 (android) unittest socket:6

2016-01-11T10:54:17.446Z - info: Discarding surplus device: UNITTEST-0.9471115627568092

2016-01-11T10:54:17.471Z - debug: Device presented: UNITTEST-0.9031482433813235 (android) unittest socket:5

2016-01-11T10:54:17.472Z - info: Discarding surplus device: UNITTEST-0.9031482433813235

2016-01-11T10:54:17.563Z - info: Running test: basic

2016-01-11T10:54:17.631Z - info: Running test: another

2016-01-11T10:54:17.698Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-11T10:54:17.761Z - info: Running test: multiplex can send data

2016-01-11T10:54:17.794Z - debug: Device presented: UNITTEST-0.5395020787753072 (android) unittest socket:7

2016-01-11T10:54:17.795Z - info: Discarding surplus device: UNITTEST-0.5395020787753072

2016-01-11T10:54:17.943Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.006009945249277782)

2016-01-11T10:54:17.962Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-11T10:54:18.012Z - debug: Device presented: UNITTEST-0.9692783161137092 (android) unittest socket:8

2016-01-11T10:54:18.013Z - info: Discarding surplus device: UNITTEST-0.9692783161137092

2016-01-11T10:54:18.137Z - info: Running test: basic

2016-01-11T10:54:18.200Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-11T10:54:18.218Z - info: Running test: another

2016-01-11T10:54:18.305Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-11T10:54:18.334Z - info: Running test: failed to get mobile documents path

2016-01-11T10:54:18.343Z - debug: Device presented: UNITTEST-0.9761101811935033 (android) unittest socket:9

2016-01-11T10:54:18.344Z - info: Discarding surplus device: UNITTEST-0.9761101811935033

2016-01-11T10:54:18.371Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.9471115627568092)

2016-01-11T10:54:18.402Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-11T10:54:18.459Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.9031482433813235)

2016-01-11T10:54:18.480Z - info: Running test: #init should register the networkChanged event

2016-01-11T10:54:18.517Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-11T10:54:18.562Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-11T10:54:18.569Z - debug: Device presented: UNITTEST-0.44237635887393834 (ios) unittest socket:10

2016-01-11T10:54:18.570Z - info: Discarding surplus device: UNITTEST-0.44237635887393834

2016-01-11T10:54:18.623Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.5395020787753072)

2016-01-11T10:54:18.649Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-11T10:54:18.664Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.9692783161137092)

2016-01-11T10:54:18.724Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-11T10:54:18.779Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-11T10:54:18.790Z - debug: Device presented: UNITTEST-0.8022228789122615 (ios) unittest socket:11

2016-01-11T10:54:18.791Z - info: Discarding surplus device: UNITTEST-0.8022228789122615

2016-01-11T10:54:18.817Z - debug: Device presented: UNITTEST-0.18268665213688717 (android) unittest socket:12

2016-01-11T10:54:18.818Z - info: Discarding surplus device: UNITTEST-0.18268665213688717

2016-01-11T10:54:18.830Z - info: Running test: failed to get mobile documents path

2016-01-11T10:54:18.877Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-11T10:54:18.887Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-11T10:54:18.961Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-11T10:54:18.967Z - info: Running test: #init should register the networkChanged event

2016-01-11T10:54:19.022Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-11T10:54:19.028Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-11T10:54:19.100Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-11T10:54:19.107Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-11T10:54:19.128Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.9761101811935033)

2016-01-11T10:54:19.144Z - debug: Device presented: UNITTEST-0.6073317590189735 (android) unittest socket:13

2016-01-11T10:54:19.145Z - info: Discarding surplus device: UNITTEST-0.6073317590189735

2016-01-11T10:54:19.154Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-11T10:54:19.180Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-11T10:54:19.209Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-11T10:54:19.264Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-11T10:54:19.273Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-11T10:54:19.333Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-11T10:54:19.342Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.18268665213688717)

2016-01-11T10:54:19.350Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-11T10:54:19.442Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-11T10:54:19.447Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-11T10:54:19.524Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-11T10:54:19.532Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-11T10:54:19.540Z - debug: Device presented: UNITTEST-0.021024983925862384 (android) unittest socket:14

2016-01-11T10:54:19.541Z - info: Discarding surplus device: UNITTEST-0.021024983925862384

2016-01-11T10:54:19.593Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-11T10:54:19.598Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-11T10:54:19.604Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.6073317590189735)

2016-01-11T10:54:19.663Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-11T10:54:19.671Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-11T10:54:19.714Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-11T10:54:19.752Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-11T10:54:19.775Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-11T10:54:19.822Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-11T10:54:19.863Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-11T10:54:19.907Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-11T10:54:20.055Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.05499246745314934)

2016-01-11T10:54:20.235Z - debug: Device presented: UNITTEST-0.7088974799995883 (android) unittest socket:15

2016-01-11T10:54:20.236Z - info: Discarding surplus device: UNITTEST-0.7088974799995883

2016-01-11T10:54:20.380Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-11T10:54:20.419Z - debug: Device presented: UNITTEST-0.21759934485405263 (android) unittest socket:16

2016-01-11T10:54:20.420Z - info: Discarding surplus device: UNITTEST-0.21759934485405263

2016-01-11T10:54:20.752Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-11T10:54:20.827Z - debug: Device presented: UNITTEST-0.8422972994651655 (android) unittest socket:17

2016-01-11T10:54:20.828Z - info: Discarding surplus device: UNITTEST-0.8422972994651655

2016-01-11T10:54:20.851Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.021024983925862384)

2016-01-11T10:54:20.887Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.7088974799995883)

2016-01-11T10:54:20.900Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-11T10:54:21.044Z - debug: Device presented: UNITTEST-0.42271141657255507 (android) unittest socket:18

2016-01-11T10:54:21.045Z - info: Discarding surplus device: UNITTEST-0.42271141657255507

2016-01-11T10:54:21.211Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.44237635887393834)

2016-01-11T10:54:21.338Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-11T10:54:21.368Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.8022228789122615)

2016-01-11T10:54:21.474Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.21759934485405263)

2016-01-11T10:54:21.520Z - debug: Device presented: UNITTEST-0.9621705321707456 (android) unittest socket:19

2016-01-11T10:54:21.521Z - info: Discarding surplus device: UNITTEST-0.9621705321707456

2016-01-11T10:54:21.611Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.8422972994651655)

2016-01-11T10:54:21.699Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.42271141657255507)

2016-01-11T10:54:22.549Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.9621705321707456)

2016-01-11T10:54:26.455Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-11T10:54:31.375Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-11T10:54:35.204Z - debug: Device presented: UNITTEST-0.956445612176902 (android) unittest socket:20

2016-01-11T10:54:35.208Z - info: Discarding surplus device: UNITTEST-0.956445612176902

2016-01-11T10:54:36.418Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.956445612176902)

2016-01-11T10:54:36.649Z - info: Running test: ThaliEmitter handles socket disconnect correctly

2016-01-11T10:54:44.766Z - info: Running test: ThaliReplicationManager can call start without error

2016-01-11T10:54:46.321Z - info: Running test: ThaliReplicationManager receives identity

2016-01-11T10:54:46.521Z - info: Test run complete

2016-01-11T10:54:46.524Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-11T10:54:46.525Z - info: PLATFORM: ios

2016-01-11T10:54:46.526Z - info: RESULT: PASS

2016-01-11T10:54:46.527Z - info: 33 of 33 tests completed
2016-01-11T10:54:46.528Z - info: 33/33 passed (0 failures)
2016-01-11T10:54:46.529Z - info: --- Test Details ---


2016-01-11T10:54:46.530Z - info: multiplex can send data - pass

2016-01-11T10:54:46.531Z - info: basic - pass
2016-01-11T10:54:46.532Z - info: another - pass

2016-01-11T10:54:46.533Z - info: successfully create a new pkcs12 file and return hash value - pass
2016-01-11T10:54:46.534Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-11T10:54:46.535Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-11T10:54:46.539Z - info: failed to get mobile documents path - pass

2016-01-11T10:54:46.543Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-11T10:54:46.544Z - info: #init should register the networkChanged event - pass
2016-01-11T10:54:46.545Z - info: #startBroadcasting should throw on null device name - pass
2016-01-11T10:54:46.546Z - info: #startBroadcasting should throw on empty string device name - pass
2016-01-11T10:54:46.547Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-11T10:54:46.548Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-11T10:54:46.548Z - info: #startBroadcasting should throw on negative port - pass

2016-01-11T10:54:46.549Z - info: #startBroadcasting should throw on too large port - pass

2016-01-11T10:54:46.550Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-11T10:54:46.551Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-11T10:54:46.552Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-11T10:54:46.553Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-11T10:54:46.554Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-01-11T10:54:46.554Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-11T10:54:46.555Z - info: should call Mobile("Disconnect") without an error - pass
2016-01-11T10:54:46.556Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-11T10:54:46.557Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
2016-01-11T10:54:46.557Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-11T10:54:46.558Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-11T10:54:46.561Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-11T10:54:46.562Z - info: ThaliEmitter can discover and connect to peers - pass

2016-01-11T10:54:46.563Z - info: ThaliEmitter can discover and connect to peers and then fail on double connect - pass

2016-01-11T10:54:46.564Z - info: ThaliEmitter can discover and connect to peers and then fail on double disconnect - pass
2016-01-11T10:54:46.565Z - info: ThaliEmitter handles socket disconnect correctly - pass

2016-01-11T10:54:46.565Z - info: ThaliReplicationManager can call start without error - pass

2016-01-11T10:54:46.566Z - info: ThaliReplicationManager receives identity - pass

2016-01-11T10:54:46.567Z - info: 

-== END ==-

2016-01-11T10:54:48.974Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.026858993033879508)

2016-01-11T10:54:49.733Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.10920010110875689)

2016-01-11T10:55:16.876Z - debug: Device presented: UNITTEST-0.8060326039569327 (android) unittest socket:21

2016-01-11T10:55:16.877Z - info: Discarding surplus device: UNITTEST-0.8060326039569327

2016-01-11T10:55:17.660Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.8060326039569327)

2016-01-11T11:21:58.148Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.8671429465056992)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed. [SUCCESS]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on 022678fb504e29b0 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5497026179923a9_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5s-1.md)



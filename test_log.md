#### Test 564496607226f84 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-19T11:16:49.937Z - info: listening on *:3000

2016-01-19T11:16:50.907Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-01-19T11:16:50.936Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-01-19T11:16:50.939Z - info: Required number of ios devices presented (2)

2016-01-19T11:16:50.943Z - info: Starting unit test run for platform: ios

2016-01-19T11:16:50.981Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:2

2016-01-19T11:16:51.146Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-01-19T11:16:51.148Z - info: Required number of android devices presented (2)

2016-01-19T11:16:51.149Z - info: Starting unit test run for platform: android

2016-01-19T11:16:51.405Z - info: Running on ios test: multiplex can send data

2016-01-19T11:16:51.460Z - info: Running on android test: multiplex can send data

2016-01-19T11:16:51.640Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:4

2016-01-19T11:16:51.641Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-19T11:16:51.647Z - info: Running on android test: basic

2016-01-19T11:16:51.701Z - info: Running on android test: another

2016-01-19T11:16:51.808Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-19T11:16:52.082Z - debug: Socket disconnected: transport close 4 (LGE-Nexus 5)

2016-01-19T11:16:52.102Z - info: Running on ios test: basic

2016-01-19T11:16:52.132Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-19T11:16:52.188Z - info: Running on ios test: another

2016-01-19T11:16:52.267Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-19T11:16:52.393Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-19T11:16:52.498Z - info: Running on android test: failed to get mobile documents path

2016-01-19T11:16:52.510Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-19T11:16:52.596Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-19T11:16:52.659Z - info: Running on android test: #init should register the networkChanged event

2016-01-19T11:16:52.706Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-19T11:16:52.738Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-19T11:16:52.763Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-19T11:16:52.827Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-19T11:16:52.859Z - info: Running on ios test: failed to get mobile documents path

2016-01-19T11:16:52.895Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-19T11:16:52.961Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:5

2016-01-19T11:16:52.963Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-19T11:16:52.968Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:6

2016-01-19T11:16:52.969Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-19T11:16:53.012Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-19T11:16:53.022Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-19T11:16:53.107Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-19T11:16:53.146Z - info: Running on ios test: #init should register the networkChanged event

2016-01-19T11:16:53.156Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-19T11:16:53.206Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-19T11:16:53.231Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-19T11:16:53.249Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-01-19T11:16:53.251Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-19T11:16:53.287Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-19T11:16:53.298Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-19T11:16:53.370Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-19T11:16:53.425Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-19T11:16:53.477Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-19T11:16:53.534Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-19T11:16:53.681Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-19T11:16:53.727Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-19T11:16:53.969Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-19T11:16:54.115Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F)

2016-01-19T11:16:54.251Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-01-19T11:16:54.260Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-19T11:16:54.287Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:8

2016-01-19T11:16:54.288Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-01-19T11:16:54.312Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-19T11:16:54.333Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:9

2016-01-19T11:16:54.334Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-19T11:16:54.364Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-19T11:16:54.428Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-19T11:16:54.481Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-19T11:16:54.534Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-19T11:16:54.597Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-19T11:16:54.650Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-19T11:16:54.702Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-19T11:16:54.755Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-19T11:16:54.770Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-19T11:16:54.815Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-19T11:16:54.880Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-19T11:16:54.923Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-19T11:16:55.079Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-19T11:16:55.235Z - debug: Socket disconnected: transport close 9 (samsung-SM-N910C)

2016-01-19T11:16:55.255Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-19T11:16:55.357Z - debug: Socket disconnected: transport close 6 (Apple-Iphone6-1)

2016-01-19T11:16:55.503Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-19T11:16:55.757Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-19T11:16:56.291Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-19T11:16:56.643Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-19T11:16:56.707Z - info: Running on android test: #start should fail if called twice in a row

2016-01-19T11:16:56.725Z - debug: Socket disconnected: transport close 8 (Apple-Iphone5s-1)

2016-01-19T11:16:56.795Z - info: Running on android test: #start should start hosting given router object

2016-01-19T11:16:56.812Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-19T11:16:56.897Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-19T11:16:56.967Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-19T11:16:57.040Z - info: Test run on android complete

2016-01-19T11:16:57.042Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-19T11:16:57.043Z - info: PLATFORM: android

2016-01-19T11:16:57.044Z - info: RESULT: PASS

2016-01-19T11:16:57.045Z - info: 33 of 33 tests completed

2016-01-19T11:16:57.047Z - info: 33/33 passed (0 failures)

2016-01-19T11:16:57.048Z - info: --- Test Details ---



2016-01-19T11:16:57.049Z - info: multiplex can send data - pass

2016-01-19T11:16:57.050Z - info: basic - pass

2016-01-19T11:16:57.050Z - info: another - pass

2016-01-19T11:16:57.051Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-19T11:16:57.052Z - info: successfully read a previous pkcs12 file and return hash value - pass
2016-01-19T11:16:57.053Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-19T11:16:57.054Z - info: failed to get mobile documents path - pass

2016-01-19T11:16:57.055Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-19T11:16:57.056Z - info: #init should register the networkChanged event - pass

2016-01-19T11:16:57.057Z - info: #startBroadcasting should throw on null device name - pass
2016-01-19T11:16:57.057Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-19T11:16:57.058Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-19T11:16:57.059Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-19T11:16:57.060Z - info: #startBroadcasting should throw on negative port - pass

2016-01-19T11:16:57.061Z - info: #startBroadcasting should throw on too large port - pass
2016-01-19T11:16:57.062Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-19T11:16:57.063Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-19T11:16:57.064Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-19T11:16:57.064Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-19T11:16:57.065Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-19T11:16:57.066Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-19T11:16:57.067Z - info: should call Mobile("Disconnect") without an error - pass
2016-01-19T11:16:57.072Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-19T11:16:57.072Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
2016-01-19T11:16:57.073Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-19T11:16:57.074Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-19T11:16:57.075Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-19T11:16:57.076Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass
2016-01-19T11:16:57.076Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-19T11:16:57.077Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-19T11:16:57.077Z - info: #start should fail if called twice in a row - pass

2016-01-19T11:16:57.078Z - info: #start should start hosting given router object - pass
2016-01-19T11:16:57.079Z - info: #stop can be called multiple times in a row - pass

2016-01-19T11:16:57.080Z - info: 

-== END ==-

2016-01-19T11:16:57.215Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:10

2016-01-19T11:16:57.216Z - info: Discarding surplus device: LGE-LG-D855

2016-01-19T11:16:57.956Z - debug: Socket disconnected: transport close 10 (LGE-LG-D855)

2016-01-19T11:17:05.065Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-19T11:17:11.547Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-19T11:17:18.396Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-19T11:17:26.098Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-19T11:17:38.377Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-19T11:17:38.847Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-19T11:17:39.161Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-19T11:18:16.447Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-19T11:18:17.547Z - info: Running on ios test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-19T11:18:18.510Z - info: Running on ios test: verify that Thali-specific messages are filtered correctly

2016-01-19T11:18:18.648Z - info: Running on ios test: #start should fail if called twice in a row

2016-01-19T11:18:18.707Z - info: Running on ios test: #start should start hosting given router object

2016-01-19T11:18:18.991Z - info: Running on ios test: #stop can be called multiple times in a row

2016-01-19T11:18:19.057Z - info: Test run on ios complete

2016-01-19T11:18:19.059Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-19T11:18:19.060Z - info: PLATFORM: ios
2016-01-19T11:18:19.061Z - info: RESULT: PASS

2016-01-19T11:18:19.062Z - info: 41 of 41 tests completed

2016-01-19T11:18:19.063Z - info: 41/41 passed (0 failures)

2016-01-19T11:18:19.064Z - info: --- Test Details ---


2016-01-19T11:18:19.065Z - info: multiplex can send data - pass

2016-01-19T11:18:19.065Z - info: basic - pass
2016-01-19T11:18:19.066Z - info: another - pass

2016-01-19T11:18:19.067Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-19T11:18:19.068Z - info: successfully read a previous pkcs12 file and return hash value - pass
2016-01-19T11:18:19.068Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-19T11:18:19.069Z - info: failed to get mobile documents path - pass
2016-01-19T11:18:19.070Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-19T11:18:19.070Z - info: #init should register the networkChanged event - pass
2016-01-19T11:18:19.071Z - info: #startBroadcasting should throw on null device name - pass

2016-01-19T11:18:19.072Z - info: #startBroadcasting should throw on empty string device name - pass
2016-01-19T11:18:19.073Z - info: #startBroadcasting should throw on non-number port - pass
2016-01-19T11:18:19.073Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-19T11:18:19.074Z - info: #startBroadcasting should throw on negative port - pass
2016-01-19T11:18:19.075Z - info: #startBroadcasting should throw on too large port - pass
2016-01-19T11:18:19.076Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-19T11:18:19.076Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-19T11:18:19.077Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-19T11:18:19.078Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-19T11:18:19.079Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-01-19T11:18:19.080Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-19T11:18:19.081Z - info: should call Mobile("Disconnect") without an error - pass
2016-01-19T11:18:19.081Z - info: should call Mobile("Disconnect") and handle an error - pass
2016-01-19T11:18:19.082Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass
2016-01-19T11:18:19.083Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-19T11:18:19.083Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-19T11:18:19.084Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-19T11:18:19.085Z - info: ThaliEmitter can discover and connect to peers - pass
2016-01-19T11:18:19.086Z - info: ThaliEmitter can discover and connect to peers and then fail on double connect - pass

2016-01-19T11:18:19.086Z - info: ThaliEmitter can discover and connect to peers and then fail on double disconnect - pass
2016-01-19T11:18:19.087Z - info: ThaliEmitter can connect and send data - pass
2016-01-19T11:18:19.088Z - info: ThaliEmitter handles socket disconnect correctly - pass

2016-01-19T11:18:19.088Z - info: ThaliReplicationManager can call start without error - pass
2016-01-19T11:18:19.089Z - info: ThaliReplicationManager receives identity - pass

2016-01-19T11:18:19.090Z - info: ThaliReplicationManager replicates database - pass
2016-01-19T11:18:19.090Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-19T11:18:19.091Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-19T11:18:19.093Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-19T11:18:19.093Z - info: #start should fail if called twice in a row - pass

2016-01-19T11:18:19.094Z - info: #start should start hosting given router object - pass
2016-01-19T11:18:19.095Z - info: #stop can be called multiple times in a row - pass
2016-01-19T11:18:19.096Z - info: 

-== END ==-


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
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/564496607226f84_Wifi_infrastructure_work_vjrantal/iOS_Iphone5s-1.md)



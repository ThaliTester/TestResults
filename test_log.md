#### Test 56449660bb41d23 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-21T15:44:21.347Z - info: listening on *:3000

2016-01-21T15:44:22.143Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:0

2016-01-21T15:44:22.204Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:1

2016-01-21T15:44:22.232Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-01-21T15:44:22.234Z - info: Required number of ios devices presented (2)

2016-01-21T15:44:22.238Z - info: Starting unit test run for platform: ios

2016-01-21T15:44:22.426Z - info: Running on ios test: multiplex can send data

2016-01-21T15:44:22.598Z - info: Running on ios test: basic

2016-01-21T15:44:22.686Z - info: Running on ios test: another

2016-01-21T15:44:22.773Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-01-21T15:44:22.811Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-01-21T15:44:22.814Z - info: Required number of android devices presented (2)

2016-01-21T15:44:22.815Z - info: Starting unit test run for platform: android

2016-01-21T15:44:22.983Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-01-21T15:44:23.124Z - info: Running on android test: multiplex can send data

2016-01-21T15:44:23.169Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-01-21T15:44:23.305Z - info: Running on ios test: failed to get mobile documents path

2016-01-21T15:44:23.353Z - info: Running on android test: basic

2016-01-21T15:44:23.367Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-01-21T15:44:23.435Z - info: Running on android test: another

2016-01-21T15:44:23.450Z - info: Running on ios test: #init should register the networkChanged event

2016-01-21T15:44:23.538Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:4

2016-01-21T15:44:23.539Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-21T15:44:23.547Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-01-21T15:44:23.555Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-21T15:44:23.607Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-01-21T15:44:23.628Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:5

2016-01-21T15:44:23.631Z - info: Discarding surplus device: LGE-LG-D722

2016-01-21T15:44:23.645Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:6

2016-01-21T15:44:23.647Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-21T15:44:23.673Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-01-21T15:44:23.728Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-01-21T15:44:23.818Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-21T15:44:23.830Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-01-21T15:44:23.927Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-01-21T15:44:24.006Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-21T15:44:24.017Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-21T15:44:24.077Z - debug: Socket disconnected: transport close 4 (LGE-Nexus 5)

2016-01-21T15:44:24.112Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-21T15:44:24.139Z - info: Running on android test: failed to get mobile documents path

2016-01-21T15:44:24.184Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-21T15:44:24.201Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-21T15:44:24.249Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-21T15:44:24.283Z - info: Running on android test: #init should register the networkChanged event

2016-01-21T15:44:24.293Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-01-21T15:44:24.342Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-21T15:44:24.356Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-01-21T15:44:24.416Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-01-21T15:44:24.429Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-21T15:44:24.493Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-01-21T15:44:24.508Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-21T15:44:24.547Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-21T15:44:24.582Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-01-21T15:44:24.586Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-21T15:44:24.595Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-21T15:44:24.648Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-21T15:44:24.692Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-21T15:44:24.736Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-21T15:44:24.783Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-21T15:44:24.825Z - debug: Socket disconnected: transport close 5 (LGE-LG-D722)

2016-01-21T15:44:24.850Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-21T15:44:24.891Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-01-21T15:44:24.947Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-21T15:44:25.037Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-21T15:44:25.057Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-01-21T15:44:25.172Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-21T15:44:25.268Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-21T15:44:25.328Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-21T15:44:25.385Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-01-21T15:44:25.540Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-21T15:44:25.572Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-01-21T15:44:25.690Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:8

2016-01-21T15:44:25.693Z - info: Discarding surplus device: LGE-LG-H815

2016-01-21T15:44:26.140Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:9

2016-01-21T15:44:26.144Z - info: Discarding surplus device: Apple-Iphone6-1

2016-01-21T15:44:26.563Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-01-21T15:44:26.691Z - debug: Socket disconnected: transport close 6 (Apple-Iphone5-1)

2016-01-21T15:44:26.727Z - debug: Socket disconnected: transport close 8 (LGE-LG-H815)

2016-01-21T15:44:28.454Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-21T15:44:28.789Z - debug: Socket disconnected: transport close 9 (Apple-Iphone6-1)

2016-01-21T15:44:28.812Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-21T15:44:29.364Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-21T15:44:29.885Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-21T15:44:30.177Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-21T15:44:30.566Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:10

2016-01-21T15:44:30.568Z - info: Discarding surplus device: LGE-LG-D855

2016-01-21T15:44:30.863Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-21T15:44:30.990Z - info: Running on android test: #start should fail if called twice in a row

2016-01-21T15:44:31.288Z - debug: Socket disconnected: transport close 10 (LGE-LG-D855)

2016-01-21T15:44:31.402Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-21T15:44:31.572Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-21T15:44:31.811Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-21T15:44:32.051Z - info: Test run on android complete

2016-01-21T15:44:32.054Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-21T15:44:32.056Z - info: PLATFORM: android

2016-01-21T15:44:32.057Z - info: RESULT: PASS

2016-01-21T15:44:32.058Z - info: 34 of 34 tests completed

2016-01-21T15:44:32.059Z - info: 34/34 passed (0 failures)

2016-01-21T15:44:32.060Z - info: --- Test Details ---



2016-01-21T15:44:32.062Z - info: multiplex can send data - pass

2016-01-21T15:44:32.063Z - info: basic - pass

2016-01-21T15:44:32.064Z - info: another - pass

2016-01-21T15:44:32.066Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-21T15:44:32.067Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-21T15:44:32.068Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-21T15:44:32.069Z - info: failed to get mobile documents path - pass

2016-01-21T15:44:32.070Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-21T15:44:32.071Z - info: #init should register the networkChanged event - pass

2016-01-21T15:44:32.073Z - info: #startBroadcasting should throw on null device name - pass

2016-01-21T15:44:32.074Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-21T15:44:32.075Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-21T15:44:32.076Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-21T15:44:32.077Z - info: #startBroadcasting should throw on negative port - pass
2016-01-21T15:44:32.078Z - info: #startBroadcasting should throw on too large port - pass
2016-01-21T15:44:32.079Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-21T15:44:32.079Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-21T15:44:32.080Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
2016-01-21T15:44:32.085Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-21T15:44:32.086Z - info: #connect should call Mobile("Connect") with a port and without an error - pass
2016-01-21T15:44:32.087Z - info: #connect should call Mobile("Connect") and handle an error - pass
2016-01-21T15:44:32.088Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-21T15:44:32.088Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-21T15:44:32.089Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-21T15:44:32.090Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-21T15:44:32.092Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-21T15:44:32.093Z - info: ThaliEmitter throws on disconnect to bad peer - pass
2016-01-21T15:44:32.094Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass
2016-01-21T15:44:32.094Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-21T15:44:32.095Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-01-21T15:44:32.096Z - info: #start should fail if called twice in a row - pass
2016-01-21T15:44:32.097Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-01-21T15:44:32.100Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass
2016-01-21T15:44:32.103Z - info: #stop can be called multiple times in a row - pass
2016-01-21T15:44:32.104Z - info: 

-== END ==-

2016-01-21T15:44:33.709Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-21T15:44:38.084Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-21T15:44:42.768Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-01-21T15:44:49.060Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-01-21T15:45:00.137Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-01-21T15:45:00.534Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-01-21T15:45:01.391Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-01-21T15:45:30.473Z - info: Running on ios test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-21T15:45:31.551Z - info: Running on ios test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-21T15:45:33.131Z - info: Running on ios test: verify that Thali-specific messages are filtered correctly

2016-01-21T15:45:34.506Z - info: Running on ios test: #start should fail if called twice in a row

2016-01-21T15:45:34.601Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-21T15:45:34.777Z - info: Running on ios test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-21T15:45:35.620Z - info: Running on ios test: #stop can be called multiple times in a row

2016-01-21T15:45:36.595Z - info: Test run on ios complete

2016-01-21T15:45:36.597Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-21T15:45:36.599Z - info: PLATFORM: ios

2016-01-21T15:45:36.601Z - info: RESULT: PASS

2016-01-21T15:45:36.603Z - info: 42 of 42 tests completed

2016-01-21T15:45:36.605Z - info: 42/42 passed (0 failures)

2016-01-21T15:45:36.606Z - info: --- Test Details ---


2016-01-21T15:45:36.607Z - info: multiplex can send data - pass

2016-01-21T15:45:36.609Z - info: basic - pass

2016-01-21T15:45:36.610Z - info: another - pass

2016-01-21T15:45:36.611Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-21T15:45:36.612Z - info: successfully read a previous pkcs12 file and return hash value - pass
2016-01-21T15:45:36.612Z - info: failed to extract public key because of corrupt pkcs12 file - pass
2016-01-21T15:45:36.613Z - info: failed to get mobile documents path - pass
2016-01-21T15:45:36.614Z - info: #init should register the peerAvailabilityChanged event - pass
2016-01-21T15:45:36.614Z - info: #init should register the networkChanged event - pass
2016-01-21T15:45:36.615Z - info: #startBroadcasting should throw on null device name - pass
2016-01-21T15:45:36.616Z - info: #startBroadcasting should throw on empty string device name - pass
2016-01-21T15:45:36.616Z - info: #startBroadcasting should throw on non-number port - pass
2016-01-21T15:45:36.617Z - info: #startBroadcasting should throw on NaN port - pass
2016-01-21T15:45:36.618Z - info: #startBroadcasting should throw on negative port - pass
2016-01-21T15:45:36.619Z - info: #startBroadcasting should throw on too large port - pass
2016-01-21T15:45:36.619Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-21T15:45:36.620Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
2016-01-21T15:45:36.621Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-21T15:45:36.622Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass
2016-01-21T15:45:36.622Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-21T15:45:36.623Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-21T15:45:36.624Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-21T15:45:36.625Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-21T15:45:36.625Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-21T15:45:36.626Z - info: ThaliEmitter calls startBroadcasting twice with error - pass
2016-01-21T15:45:36.627Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-21T15:45:36.627Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-21T15:45:36.628Z - info: ThaliEmitter can discover and connect to peers - pass

2016-01-21T15:45:36.629Z - info: ThaliEmitter can discover and connect to peers and then fail on double connect - pass

2016-01-21T15:45:36.630Z - info: ThaliEmitter can discover and connect to peers and then fail on double disconnect - pass

2016-01-21T15:45:36.630Z - info: ThaliEmitter can connect and send data - pass

2016-01-21T15:45:36.631Z - info: ThaliEmitter handles socket disconnect correctly - pass

2016-01-21T15:45:36.632Z - info: ThaliReplicationManager can call start without error - pass

2016-01-21T15:45:36.633Z - info: ThaliReplicationManager receives identity - pass

2016-01-21T15:45:36.634Z - info: ThaliReplicationManager replicates database - pass

2016-01-21T15:45:36.635Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-21T15:45:36.636Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-21T15:45:36.637Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-21T15:45:36.637Z - info: #start should fail if called twice in a row - pass

2016-01-21T15:45:36.638Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-01-21T15:45:36.639Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-01-21T15:45:36.639Z - info: #stop can be called multiple times in a row - pass

2016-01-21T15:45:36.640Z - info: 

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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali09_LGE-Nexus 5.md)




###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/56449660bb41d23_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone5s-1.md)



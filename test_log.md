#### Test 564496604206eac Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-27T09:08:26.465Z - info: listening on *:3000

2016-01-27T09:08:27.859Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:1

2016-01-27T09:08:28.795Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-01-27T09:08:28.798Z - info: Required number of android devices presented (2)

2016-01-27T09:08:28.801Z - info: Starting unit test run for platform: android

2016-01-27T09:08:28.823Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-01-27T09:08:29.191Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:4

2016-01-27T09:08:29.193Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-27T09:08:29.307Z - info: Running on android test: multiplex can send data

2016-01-27T09:08:29.588Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-01-27T09:08:29.589Z - info: Required number of ios devices presented (2)

2016-01-27T09:08:29.591Z - info: Starting unit test run for platform: ios

2016-01-27T09:08:29.650Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:5

2016-01-27T09:08:29.651Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-27T09:08:29.666Z - debug: Socket disconnected: transport close 4 (LGE-Nexus 5)

2016-01-27T09:08:29.819Z - info: Running on ios test: multiplex can send data

2016-01-27T09:08:29.988Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:6

2016-01-27T09:08:29.989Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-27T09:08:30.053Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-01-27T09:08:30.054Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-27T09:08:30.654Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-01-27T09:08:30.655Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-27T09:08:30.858Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:9

2016-01-27T09:08:30.859Z - info: Discarding surplus device: LGE-LG-D722

2016-01-27T09:08:30.869Z - info: Running on android test: enqueue and run in order

2016-01-27T09:08:31.029Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F)

2016-01-27T09:08:31.191Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-01-27T09:08:31.226Z - info: Running on android test: basic

2016-01-27T09:08:31.331Z - info: Running on android test: another

2016-01-27T09:08:31.403Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-27T09:08:31.412Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-01-27T09:08:31.694Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-27T09:08:31.840Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-27T09:08:31.899Z - info: Running on android test: failed to get mobile documents path

2016-01-27T09:08:31.948Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-27T09:08:31.992Z - debug: Socket disconnected: transport close 9 (LGE-LG-D722)

2016-01-27T09:08:32.002Z - info: Running on android test: #init should register the networkChanged event

2016-01-27T09:08:32.047Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-27T09:08:32.110Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-27T09:08:32.176Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-27T09:08:32.245Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-27T09:08:32.308Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-27T09:08:32.362Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-27T09:08:32.420Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-27T09:08:32.501Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-27T09:08:32.581Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-27T09:08:32.595Z - debug: Socket disconnected: transport close 5 (Apple-Iphone5-1)

2016-01-27T09:08:32.665Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-27T09:08:32.750Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-27T09:08:32.812Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-27T09:08:32.856Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-27T09:08:32.905Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-27T09:08:32.954Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-27T09:08:34.064Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-27T09:08:34.466Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-27T09:08:34.924Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-27T09:08:35.059Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:10

2016-01-27T09:08:35.060Z - info: Discarding surplus device: LGE-LG-D855

2016-01-27T09:08:35.342Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-27T09:08:35.729Z - debug: Socket disconnected: transport close 10 (LGE-LG-D855)

2016-01-27T09:08:35.855Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-27T09:08:36.738Z - info: Running on android test: messages with invalid location or USN should be ignored

2016-01-27T09:08:36.961Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-27T09:08:37.178Z - info: Running on android test: #start should fail if called twice in a row

2016-01-27T09:08:37.240Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-27T09:08:37.324Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-01-27T09:08:37.449Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-27T09:08:37.570Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-27T09:08:37.614Z - info: Test run on android complete

2016-01-27T09:08:37.618Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-27T09:08:37.620Z - info: PLATFORM: android

2016-01-27T09:08:37.621Z - info: RESULT: PASS

2016-01-27T09:08:37.623Z - info: 37 of 37 tests completed

2016-01-27T09:08:37.624Z - info: 37/37 passed (0 failures)

2016-01-27T09:08:37.625Z - info: --- Test Details ---



2016-01-27T09:08:37.626Z - info: multiplex can send data - pass

2016-01-27T09:08:37.628Z - info: enqueue and run in order - pass

2016-01-27T09:08:37.629Z - info: basic - pass

2016-01-27T09:08:37.630Z - info: another - pass

2016-01-27T09:08:37.631Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-27T09:08:37.632Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-27T09:08:37.633Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-27T09:08:37.634Z - info: failed to get mobile documents path - pass

2016-01-27T09:08:37.635Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-27T09:08:37.636Z - info: #init should register the networkChanged event - pass

2016-01-27T09:08:37.658Z - info: #startBroadcasting should throw on null device name - pass

2016-01-27T09:08:37.669Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-27T09:08:37.672Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-27T09:08:37.673Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-27T09:08:37.674Z - info: #startBroadcasting should throw on negative port - pass

2016-01-27T09:08:37.675Z - info: #startBroadcasting should throw on too large port - pass

2016-01-27T09:08:37.676Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
2016-01-27T09:08:37.677Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-27T09:08:37.678Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-27T09:08:37.679Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-27T09:08:37.679Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-27T09:08:37.681Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-27T09:08:37.682Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-27T09:08:37.683Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-27T09:08:37.684Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-27T09:08:37.685Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-27T09:08:37.686Z - info: ThaliEmitter throws on connection to bad peer - pass
2016-01-27T09:08:37.687Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-27T09:08:37.688Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-27T09:08:37.689Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-27T09:08:37.689Z - info: messages with invalid location or USN should be ignored - pass

2016-01-27T09:08:37.690Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-27T09:08:37.694Z - info: #start should fail if called twice in a row - pass

2016-01-27T09:08:37.694Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-01-27T09:08:37.695Z - info: #startUpdateAdvertisingAndListening should fail if router server starting fails - pass

2016-01-27T09:08:37.696Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-01-27T09:08:37.697Z - info: #stop can be called multiple times in a row - pass
2016-01-27T09:08:37.698Z - info: 

-== END ==-

2016-01-27T09:10:02.631Z - debug: Socket disconnected: ping timeout 1 (motorola-Nexus 6)

2016-01-27T09:10:02.636Z - debug: Socket disconnected: ping timeout 3 (LGE-LG-H815)

2016-01-27T09:21:23.566Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-01-27T09:21:23.642Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)


 
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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/564496604206eac_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali09_LGE-Nexus 5.md)





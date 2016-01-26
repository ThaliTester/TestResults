#### Test 564496605d11e75 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-26T11:29:48.845Z - info: listening on *:3000

2016-01-26T11:29:49.605Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:0

2016-01-26T11:29:49.629Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-01-26T11:29:49.632Z - info: Required number of android devices presented (2)

2016-01-26T11:29:49.635Z - info: Starting unit test run for platform: android

2016-01-26T11:29:49.935Z - info: Running on android test: multiplex can send data

2016-01-26T11:29:50.160Z - info: Running on android test: basic

2016-01-26T11:29:50.230Z - info: Running on android test: another

2016-01-26T11:29:50.305Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-26T11:29:50.495Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-01-26T11:29:50.683Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-26T11:29:50.874Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-26T11:29:50.932Z - info: Running on android test: failed to get mobile documents path

2016-01-26T11:29:51.006Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-26T11:29:51.072Z - info: Running on android test: #init should register the networkChanged event

2016-01-26T11:29:51.121Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-26T11:29:51.183Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-26T11:29:51.237Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-26T11:29:51.304Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-26T11:29:51.344Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-26T11:29:51.385Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-26T11:29:51.447Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-26T11:29:51.515Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-26T11:29:51.573Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-26T11:29:51.633Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-26T11:29:51.680Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-26T11:29:51.738Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-26T11:29:51.838Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-26T11:29:51.921Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-26T11:29:51.968Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-26T11:29:52.175Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-01-26T11:29:52.176Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-26T11:29:52.702Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:4

2016-01-26T11:29:52.703Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-26T11:29:52.770Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-01-26T11:29:52.771Z - info: Discarding surplus device: motorola-Nexus 6

2016-01-26T11:29:52.810Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:5

2016-01-26T11:29:52.811Z - info: Required number of ios devices presented (2)

2016-01-26T11:29:52.813Z - info: Starting unit test run for platform: ios

2016-01-26T11:29:53.151Z - debug: Socket disconnected: transport close 4 (LGE-Nexus 5)

2016-01-26T11:29:53.190Z - debug: Device presented: samsung-SM-A500FU (android) unittest socket:7

2016-01-26T11:29:53.191Z - info: Discarding surplus device: samsung-SM-A500FU

2016-01-26T11:29:53.231Z - debug: Socket disconnected: transport close 3 (samsung-SM-G900F)

2016-01-26T11:29:53.239Z - info: Running on ios test: multiplex can send data

2016-01-26T11:29:53.449Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-01-26T11:29:53.693Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:8

2016-01-26T11:29:53.694Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-26T11:29:53.870Z - debug: Socket disconnected: transport close 7 (samsung-SM-A500FU)

2016-01-26T11:29:53.929Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:9

2016-01-26T11:29:53.930Z - info: Discarding surplus device: LGE-LG-H815

2016-01-26T11:29:54.070Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:10

2016-01-26T11:29:54.071Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-26T11:29:54.763Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F)

2016-01-26T11:29:54.887Z - info: Running on android test: ThaliEmitter calls startBroadcasting twice with error

2016-01-26T11:29:54.935Z - debug: Socket disconnected: transport close 9 (LGE-LG-H815)

2016-01-26T11:29:55.257Z - info: Running on android test: ThaliEmitter throws on connection to bad peer

2016-01-26T11:29:55.572Z - info: Running on android test: ThaliEmitter throws on disconnect to bad peer

2016-01-26T11:29:56.010Z - info: Running on android test: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available

2016-01-26T11:29:56.393Z - info: Running on android test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-01-26T11:29:56.541Z - info: Running on android test: messages with invalid location or USN should be ignored

2016-01-26T11:29:56.615Z - info: Running on android test: verify that Thali-specific messages are filtered correctly

2016-01-26T11:29:56.680Z - info: Running on android test: #start should fail if called twice in a row

2016-01-26T11:29:56.767Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-01-26T11:29:56.835Z - info: Running on android test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-01-26T11:29:57.038Z - info: Running on android test: #stop can be called multiple times in a row

2016-01-26T11:29:57.205Z - info: Test run on android complete

2016-01-26T11:29:57.207Z - info: 

-== UNIT TEST RESULTS ==-

2016-01-26T11:29:57.209Z - info: PLATFORM: android

2016-01-26T11:29:57.210Z - info: RESULT: PASS

2016-01-26T11:29:57.212Z - info: 35 of 35 tests completed

2016-01-26T11:29:57.213Z - info: 35/35 passed (0 failures)

2016-01-26T11:29:57.214Z - info: --- Test Details ---



2016-01-26T11:29:57.215Z - info: multiplex can send data - pass

2016-01-26T11:29:57.216Z - info: basic - pass

2016-01-26T11:29:57.217Z - info: another - pass

2016-01-26T11:29:57.218Z - info: successfully create a new pkcs12 file and return hash value - pass

2016-01-26T11:29:57.219Z - info: successfully read a previous pkcs12 file and return hash value - pass

2016-01-26T11:29:57.221Z - info: failed to extract public key because of corrupt pkcs12 file - pass

2016-01-26T11:29:57.222Z - info: failed to get mobile documents path - pass

2016-01-26T11:29:57.222Z - info: #init should register the peerAvailabilityChanged event - pass

2016-01-26T11:29:57.227Z - info: #init should register the networkChanged event - pass

2016-01-26T11:29:57.228Z - info: #startBroadcasting should throw on null device name - pass

2016-01-26T11:29:57.229Z - info: #startBroadcasting should throw on empty string device name - pass

2016-01-26T11:29:57.230Z - info: #startBroadcasting should throw on non-number port - pass

2016-01-26T11:29:57.231Z - info: #startBroadcasting should throw on NaN port - pass

2016-01-26T11:29:57.232Z - info: #startBroadcasting should throw on negative port - pass

2016-01-26T11:29:57.233Z - info: #startBroadcasting should throw on too large port - pass

2016-01-26T11:29:57.234Z - info: #startBroadcasting should call Mobile("StartBroadcasting") without an error - pass

2016-01-26T11:29:57.235Z - info: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass

2016-01-26T11:29:57.236Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass

2016-01-26T11:29:57.237Z - info: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

2016-01-26T11:29:57.238Z - info: #connect should call Mobile("Connect") with a port and without an error - pass

2016-01-26T11:29:57.239Z - info: #connect should call Mobile("Connect") and handle an error - pass

2016-01-26T11:29:57.240Z - info: should call Mobile("Disconnect") without an error - pass

2016-01-26T11:29:57.241Z - info: should call Mobile("Disconnect") and handle an error - pass

2016-01-26T11:29:57.242Z - info: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error - pass

2016-01-26T11:29:57.243Z - info: ThaliEmitter calls startBroadcasting twice with error - pass

2016-01-26T11:29:57.265Z - info: ThaliEmitter throws on connection to bad peer - pass

2016-01-26T11:29:57.277Z - info: ThaliEmitter throws on disconnect to bad peer - pass

2016-01-26T11:29:57.278Z - info: #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available - pass

2016-01-26T11:29:57.279Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass

2016-01-26T11:29:57.280Z - info: messages with invalid location or USN should be ignored - pass

2016-01-26T11:29:57.281Z - info: verify that Thali-specific messages are filtered correctly - pass

2016-01-26T11:29:57.282Z - info: #start should fail if called twice in a row - pass

2016-01-26T11:29:57.283Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-01-26T11:29:57.284Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-01-26T11:29:57.285Z - info: #stop can be called multiple times in a row - pass

2016-01-26T11:29:57.287Z - info: 

-== END ==-

2016-01-26T11:29:57.296Z - debug: Socket disconnected: transport close 10 (Apple-Iphone5-1)

2016-01-26T11:29:57.852Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:11

2016-01-26T11:29:57.853Z - info: Discarding surplus device: LGE-LG-D855

2016-01-26T11:29:58.504Z - debug: Socket disconnected: transport close 11 (LGE-LG-D855)

2016-01-26T11:31:22.175Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-D722)

2016-01-26T11:31:22.218Z - debug: Socket disconnected: ping timeout 1 (samsung-SM-N910C)

2016-01-26T11:37:16.340Z - debug: Socket disconnected: ping timeout 5 (Apple-Iphone5s-1)

2016-01-26T11:42:14.408Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)


 
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
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/564496605d11e75_First_bits_of_the_Wifi_infrastructure_work_vjrantal/thali09_LGE-Nexus 5.md)





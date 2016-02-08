#### Test 586024278176cca Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-08T12:40:00.422Z - info: listening on *:3000

2016-02-08T12:40:01.008Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:0

2016-02-08T12:40:01.034Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:1

2016-02-08T12:40:01.037Z - info: Required number of android devices presented (2)

2016-02-08T12:40:01.040Z - info: Starting unit test run for platform: android

2016-02-08T12:40:01.261Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:2

2016-02-08T12:40:01.262Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-08T12:40:01.430Z - info: Running on android test: multiplex can send data

2016-02-08T12:40:01.678Z - info: Running on android test: enqueue and run in order

2016-02-08T12:40:01.783Z - debug: Socket disconnected: transport close 2 (LGE-Nexus 5)

2016-02-08T12:40:01.955Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:3

2016-02-08T12:40:01.956Z - info: Discarding surplus device: LGE-LG-D722

2016-02-08T12:40:02.025Z - info: Running on android test: basic

2016-02-08T12:40:02.157Z - info: Running on android test: another

2016-02-08T12:40:02.206Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-08T12:40:02.404Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-08T12:40:02.545Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-08T12:40:02.658Z - info: Running on android test: failed to get mobile documents path

2016-02-08T12:40:02.710Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-08T12:40:02.796Z - info: Running on android test: #init should register the networkChanged event

2016-02-08T12:40:02.847Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-08T12:40:02.901Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-08T12:40:02.962Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-08T12:40:03.013Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-08T12:40:03.072Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-08T12:40:03.156Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-08T12:40:03.166Z - debug: Socket disconnected: transport close 3 (LGE-LG-D722)

2016-02-08T12:40:03.212Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T12:40:03.278Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T12:40:03.343Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T12:40:03.398Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T12:40:03.452Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:4

2016-02-08T12:40:03.453Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-08T12:40:03.493Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-08T12:40:03.581Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-08T12:40:03.638Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-08T12:40:03.693Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-08T12:40:03.759Z - info: Running on android test: #start should fail if called twice in a row

2016-02-08T12:40:03.816Z - info: Running on android test: #startListeningForAdvertisements should fail if start not called

2016-02-08T12:40:03.877Z - info: Running on android test: should be able to call #stopListeningForAdvertisements many times

2016-02-08T12:40:03.938Z - info: Running on android test: should be able to call #startListeningForAdvertisements many times

2016-02-08T12:40:04.005Z - info: Running on android test: should be able to call #startUpdateAdvertisingAndListening many times

2016-02-08T12:40:04.125Z - info: Running on android test: #startUpdateAdvertisingAndListening should fail if start not called

2016-02-08T12:40:04.159Z - debug: Socket disconnected: transport close 4 (motorola-Nexus 6)

2016-02-08T12:40:04.167Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T12:40:04.192Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:5

2016-02-08T12:40:04.193Z - info: Discarding surplus device: LGE-LG-D855

2016-02-08T12:40:04.393Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-02-08T12:40:04.397Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-08T12:40:04.743Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:7

2016-02-08T12:40:04.744Z - info: Discarding surplus device: LGE-LG-H815

2016-02-08T12:40:04.816Z - debug: Socket disconnected: transport close 5 (LGE-LG-D855)

2016-02-08T12:40:05.149Z - debug: Socket disconnected: transport close 6 (samsung-SM-N910C)

2016-02-08T12:40:05.716Z - debug: Socket disconnected: transport close 7 (LGE-LG-H815)

2016-02-08T12:40:11.041Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:8

2016-02-08T12:40:11.046Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-08T12:40:11.717Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F)

2016-02-08T12:41:29.190Z - debug: Socket disconnected: ping timeout 0 (samsung-SM-G900F)

2016-02-08T12:41:29.199Z - debug: Socket disconnected: ping timeout 1 (HTC-HTC One M8s)


 
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
ios: child process exited with code 254 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/586024278176cca_First_bits_of_thaliMobile_vjrantal/thali09_LGE-Nexus 5.md)





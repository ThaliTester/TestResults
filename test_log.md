#### Test 575312438097721 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-02T16:18:05.104Z - info: listening on *:3000

2016-02-02T16:18:05.575Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:1

2016-02-02T16:18:06.399Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-02-02T16:18:06.606Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:3

2016-02-02T16:18:08.104Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:4

2016-02-02T16:18:08.444Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-02-02T16:18:08.550Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:5

2016-02-02T16:18:08.729Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:6

2016-02-02T16:18:08.730Z - info: Required number of ios devices presented (2)

2016-02-02T16:18:08.734Z - info: Starting unit test run for platform: ios

2016-02-02T16:18:08.932Z - info: Running on ios test: multiplex can send data

2016-02-02T16:18:09.113Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:7

2016-02-02T16:18:09.157Z - info: Running on ios test: enqueue and run in order

2016-02-02T16:18:09.197Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-02T16:18:09.539Z - info: Running on ios test: basic

2016-02-02T16:18:09.686Z - info: Running on ios test: another

2016-02-02T16:18:09.906Z - info: Running on ios test: Can call start/stopListeningForAdvertisements

2016-02-02T16:18:10.236Z - info: Running on ios test: Calling startListeningForAdvertisements twice is an error

2016-02-02T16:18:10.732Z - info: Running on ios test: Can call start/stopUpdateAdvertisingAndListening

2016-02-02T16:18:11.480Z - info: Running on ios test: Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-02T16:18:12.236Z - info: Running on ios test: peerAvailabilityChange is called

2016-02-02T16:18:13.929Z - info: Running on ios test: Can connect to a remote peer

2016-02-02T16:18:14.971Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-02T16:18:49.511Z - debug: Socket disconnected: transport close 10 (NOT YET SET)

2016-02-02T16:18:54.150Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:11

2016-02-02T16:18:54.154Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-02T16:18:57.121Z - debug: Socket disconnected: transport close 11 (Apple-Iphone5-1)

2016-02-02T16:20:23.621Z - debug: Socket disconnected: ping timeout 5 (LGE-LG-D855)

2016-02-02T16:28:09.822Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone6-1)

2016-02-02T16:31:08.413Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-02-02T16:34:16.510Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-02-02T16:34:20.204Z - debug: Socket disconnected: transport close 4 (motorola-Nexus 6)

2016-02-02T16:34:34.899Z - debug: Socket disconnected: transport close 7 (LGE-LG-D722)

2016-02-02T16:34:35.357Z - debug: Socket disconnected: transport close 1 (samsung-SM-G900F)

2016-02-02T16:34:36.814Z - debug: Socket disconnected: transport close 3 (LGE-Nexus 5)

2016-02-02T16:38:20.197Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-02T16:38:22.611Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:null 
child process exited with code null on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/575312438097721_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali09_LGE-Nexus 5.md)





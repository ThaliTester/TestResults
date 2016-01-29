#### Test 57531243c766d4e Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-29T18:00:13.259Z - info: listening on *:3000

2016-01-29T18:00:13.720Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:0

2016-01-29T18:00:13.992Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:1

2016-01-29T18:00:14.040Z - debug: Device presented: HTC-HTC Desire 820 (android) unittest socket:2

2016-01-29T18:00:14.794Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:3

2016-01-29T18:00:14.866Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:4

2016-01-29T18:00:15.394Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:5

2016-01-29T18:00:15.438Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:6

2016-01-29T18:00:16.110Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:7

2016-01-29T18:00:16.111Z - info: Required number of ios devices presented (2)

2016-01-29T18:00:16.115Z - info: Starting unit test run for platform: ios

2016-01-29T18:00:17.348Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:8

2016-01-29T18:00:17.349Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-01-29T18:00:17.378Z - info: Running on ios test: multiplex can send data

2016-01-29T18:00:17.534Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-01-29T18:00:17.912Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:10

2016-01-29T18:00:18.084Z - debug: Device presented: samsung-SM-A300FU (android) unittest socket:11

2016-01-29T18:00:18.129Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:12

2016-01-29T18:00:19.779Z - debug: Socket disconnected: transport close 8 (Apple-Iphone5s-1)

2016-01-29T18:00:21.606Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:13

2016-01-29T18:00:22.667Z - info: Running on ios test: enqueue and run in order

2016-01-29T18:00:23.115Z - info: Running on ios test: basic

2016-01-29T18:00:23.429Z - info: Running on ios test: another

2016-01-29T18:00:23.776Z - info: Running on ios test: Can call start/stopListeningForAdvertisements

2016-01-29T18:00:23.997Z - info: Running on ios test: Calling startListeningForAdvertisements twice is an error

2016-01-29T18:00:24.692Z - info: Running on ios test: Can call start/stopUpdateAdvertisingAndListening

2016-01-29T18:00:26.270Z - info: Running on ios test: Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-01-29T18:00:27.452Z - info: Running on ios test: peerAvailabilityChange is called

2016-01-29T18:00:29.972Z - info: Running on ios test: Can connect to a remote peer

2016-01-29T18:08:39.329Z - debug: Socket disconnected: ping timeout 6 (Apple-Iphone6-1)

2016-01-29T18:12:43.467Z - debug: Socket disconnected: ping timeout 14 (NOT YET SET)

2016-01-29T18:13:19.031Z - debug: Socket disconnected: transport close 7 (Apple-IpadAir2-1)

2016-01-29T18:16:22.752Z - debug: Socket disconnected: ping timeout 13 (LGE-LG-D855)

2016-01-29T18:16:32.505Z - debug: Socket disconnected: transport close 10 (LGE-LG-H815)

2016-01-29T18:16:45.197Z - debug: Socket disconnected: transport close 3 (motorola-Nexus 6)

2016-01-29T18:16:49.308Z - debug: Socket disconnected: transport close 4 (LGE-LG-D722)

2016-01-29T18:16:51.125Z - debug: Socket disconnected: transport close 12 (LGE-Nexus 5)

2016-01-29T18:17:04.803Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-01-29T18:17:16.868Z - debug: Socket disconnected: transport close 2 (HTC-HTC Desire 820)

2016-01-29T18:17:45.023Z - debug: Socket disconnected: transport close 11 (samsung-SM-A300FU)

2016-01-29T18:17:46.878Z - debug: Socket disconnected: transport close 5 (HTC-HTC One M8s)

2016-01-29T18:18:18.892Z - debug: Socket disconnected: transport close 1 (samsung-SM-N910C)

2016-01-29T18:18:21.251Z - debug: Socket disconnected: transport close 0 (samsung-SM-G900F)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57531243c766d4e_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali09_LGE-Nexus 5.md)





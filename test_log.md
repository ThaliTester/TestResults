#### Test 57659382b63fd0b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-01-29T15:53:25.465Z - info: listening on *:3000

2016-01-29T15:53:25.848Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:0

2016-01-29T15:53:25.876Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-01-29T15:53:25.879Z - info: Required number of android devices presented (2)

2016-01-29T15:53:25.882Z - info: Starting unit test run for platform: android

2016-01-29T15:53:26.246Z - info: Running on android test: multiplex can send data

2016-01-29T15:53:26.328Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-01-29T15:53:26.457Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:3

2016-01-29T15:53:26.458Z - info: Discarding surplus device: LGE-LG-D722

2016-01-29T15:53:26.469Z - info: Running on android test: enqueue and run in order

2016-01-29T15:53:26.805Z - info: Running on android test: basic

2016-01-29T15:53:26.838Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-01-29T15:53:26.839Z - info: Required number of ios devices presented (2)

2016-01-29T15:53:26.841Z - info: Starting unit test run for platform: ios

2016-01-29T15:53:26.881Z - info: Running on android test: another

2016-01-29T15:53:26.922Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-01-29T15:53:27.111Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-01-29T15:53:27.326Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-01-29T15:53:27.391Z - info: Running on android test: failed to get mobile documents path

2016-01-29T15:53:27.430Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:5

2016-01-29T15:53:27.431Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-01-29T15:53:27.443Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-01-29T15:53:27.499Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:6

2016-01-29T15:53:27.500Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-29T15:53:27.506Z - info: Running on android test: #init should register the networkChanged event

2016-01-29T15:53:27.567Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-01-29T15:53:27.611Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-01-29T15:53:27.641Z - debug: Socket disconnected: transport close 3 (LGE-LG-D722)

2016-01-29T15:53:27.722Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-01-29T15:53:27.777Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-01-29T15:53:27.806Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:7

2016-01-29T15:53:27.807Z - info: Discarding surplus device: LGE-Nexus 5

2016-01-29T15:53:27.830Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-01-29T15:53:27.881Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-01-29T15:53:27.933Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-29T15:53:27.993Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-29T15:53:28.084Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-29T15:53:28.159Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-29T15:53:28.242Z - debug: Socket disconnected: transport close 7 (LGE-Nexus 5)

2016-01-29T15:53:28.255Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-01-29T15:53:28.310Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:8

2016-01-29T15:53:28.311Z - info: Discarding surplus device: Apple-Iphone5-1

2016-01-29T15:53:28.351Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-01-29T15:53:28.410Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-01-29T15:53:28.442Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:9

2016-01-29T15:53:28.443Z - info: Discarding surplus device: motorola-Nexus 6

2016-01-29T15:53:28.463Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-01-29T15:53:28.521Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-29T15:53:28.613Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F)

2016-01-29T15:53:29.151Z - debug: Socket disconnected: transport close 9 (motorola-Nexus 6)

2016-01-29T15:53:29.644Z - info: Running on ios test: multiplex can send data

2016-01-29T15:53:29.863Z - debug: Socket disconnected: transport close 5 (Apple-IpadAir2-1)

2016-01-29T15:53:31.650Z - debug: Socket disconnected: transport close 8 (Apple-Iphone5-1)

2016-01-29T15:53:33.371Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:10

2016-01-29T15:53:33.372Z - info: Discarding surplus device: samsung-SM-G900F

2016-01-29T15:53:34.170Z - debug: Socket disconnected: transport close 10 (samsung-SM-G900F)

2016-01-29T15:53:35.629Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:11

2016-01-29T15:53:35.630Z - info: Discarding surplus device: samsung-SM-N910C

2016-01-29T15:53:36.110Z - debug: Socket disconnected: transport close 11 (samsung-SM-N910C)

2016-01-29T15:54:53.549Z - debug: Socket disconnected: ping timeout 1 (LGE-LG-H815)

2016-01-29T16:03:37.764Z - debug: Socket disconnected: ping timeout 4 (Apple-Iphone5s-1)

2016-01-29T16:06:31.300Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-D855)

2016-01-29T16:06:34.838Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57659382b63fd0b_V_next_tompaana_486_tompaana/thali09_LGE-Nexus 5.md)





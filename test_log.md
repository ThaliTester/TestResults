#### Test 58497659c9ea290 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-05T23:31:03.989Z - info: listening on *:3000

2016-02-05T23:31:04.612Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:0

2016-02-05T23:31:04.869Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:1

2016-02-05T23:31:04.872Z - info: Required number of android devices presented (2)

2016-02-05T23:31:04.876Z - info: Starting unit test run for platform: android

2016-02-05T23:31:04.970Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-02-05T23:31:05.545Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:3

2016-02-05T23:31:05.546Z - info: Required number of ios devices presented (2)

2016-02-05T23:31:05.547Z - info: Starting unit test run for platform: ios

2016-02-05T23:31:05.700Z - info: Running on android test: multiplex can send data

2016-02-05T23:31:06.104Z - info: Running on android test: enqueue and run in order

2016-02-05T23:31:06.420Z - info: Running on android test: basic

2016-02-05T23:31:06.530Z - info: Running on android test: another

2016-02-05T23:31:06.636Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-05T23:31:06.659Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:4

2016-02-05T23:31:06.660Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-05T23:31:06.965Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-05T23:31:07.142Z - debug: Socket disconnected: transport close 4 (LGE-Nexus 5)

2016-02-05T23:31:07.222Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:5

2016-02-05T23:31:07.223Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-05T23:31:07.246Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-05T23:31:07.312Z - info: Running on android test: failed to get mobile documents path

2016-02-05T23:31:07.364Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-05T23:31:07.414Z - info: Running on android test: #init should register the networkChanged event

2016-02-05T23:31:07.475Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-05T23:31:07.531Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-05T23:31:07.596Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-05T23:31:07.659Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-05T23:31:07.710Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-05T23:31:07.753Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:6

2016-02-05T23:31:07.754Z - info: Discarding surplus device: LGE-LG-H815

2016-02-05T23:31:07.768Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-05T23:31:07.823Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-05T23:31:07.833Z - info: Running on ios test: multiplex can send data

2016-02-05T23:31:07.911Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-05T23:31:07.997Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-05T23:31:08.070Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-05T23:31:08.159Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-05T23:31:08.217Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-05T23:31:08.289Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-05T23:31:08.334Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F)

2016-02-05T23:31:08.359Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-05T23:31:08.423Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-05T23:31:08.647Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:7

2016-02-05T23:31:08.648Z - info: Discarding surplus device: LGE-LG-D855

2016-02-05T23:31:08.798Z - debug: Socket disconnected: transport close 6 (LGE-LG-H815)

2016-02-05T23:31:08.936Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-05T23:31:08.937Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-05T23:31:09.383Z - debug: Socket disconnected: transport close 7 (LGE-LG-D855)

2016-02-05T23:31:09.676Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-05T23:31:11.095Z - info: Running on ios test: enqueue and run in order

2016-02-05T23:31:11.592Z - info: Running on ios test: basic

2016-02-05T23:31:11.771Z - info: Running on ios test: another

2016-02-05T23:31:11.955Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-05T23:31:13.827Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-05T23:31:13.829Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-05T23:31:14.615Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-05T23:31:14.821Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-05T23:31:19.195Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-05T23:31:19.529Z - info: Running on ios test: failed to get mobile documents path

2016-02-05T23:31:19.640Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-05T23:31:19.720Z - info: Running on ios test: #init should register the networkChanged event

2016-02-05T23:31:19.790Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-05T23:31:19.859Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-05T23:31:19.926Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-05T23:31:19.989Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-05T23:31:20.052Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-05T23:31:20.118Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-05T23:31:20.179Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-05T23:31:20.281Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-05T23:31:20.347Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-05T23:31:20.412Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-05T23:31:20.476Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-05T23:31:20.551Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-05T23:31:20.678Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-05T23:31:20.744Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-05T23:31:20.868Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-05T23:31:21.177Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-05T23:31:21.280Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-05T23:31:21.374Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-05T23:31:21.908Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-05T23:31:27.613Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-05T23:31:31.756Z - debug: Device presented: motorola-XT1072 (android) unittest socket:11

2016-02-05T23:31:31.757Z - info: Discarding surplus device: motorola-XT1072

2016-02-05T23:31:32.415Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-05T23:31:32.587Z - debug: Socket disconnected: transport close 11 (motorola-XT1072)

2016-02-05T23:31:34.814Z - debug: Socket disconnected: transport close 10 (NOT YET SET)

2016-02-05T23:31:39.122Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:12

2016-02-05T23:31:39.123Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-05T23:31:41.693Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-05T23:31:48.733Z - debug: Socket disconnected: transport close 12 (Apple-Iphone5-1)

2016-02-05T23:32:33.453Z - debug: Socket disconnected: ping timeout 1 (motorola-Nexus 6)

2016-02-05T23:38:52.495Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone6-1)

2016-02-05T23:43:58.952Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-02-05T23:47:21.669Z - debug: Socket disconnected: transport close 0 (LGE-LG-D722)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58497659c9ea290_Fixes_from_review_yaronyg/thali09_LGE-Nexus 5.md)





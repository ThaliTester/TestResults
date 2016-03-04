#### Test 614329799926788 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
2016-03-04T07:43:23.068Z - info: listening on *:3000

2016-03-04T07:43:25.572Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-04T07:43:26.637Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-04T07:43:27.181Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-04T07:43:27.185Z - info: Required number of ios devices presented (2)

2016-03-04T07:43:27.188Z - info: Starting unit test run for platform: ios

2016-03-04T07:43:27.659Z - info: Running on ios test: 1. multiplex can send data

2016-03-04T07:43:27.883Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-04T07:43:27.884Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-04T07:43:27.974Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-03-04T07:43:27.975Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-04T07:43:28.219Z - info: Running on ios test: 2. enqueue and run in order

2016-03-04T07:43:28.357Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:5

2016-03-04T07:43:28.358Z - info: Required number of android devices presented (2)

2016-03-04T07:43:28.360Z - info: Starting unit test run for platform: android

2016-03-04T07:43:28.867Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-04T07:43:28.969Z - info: Running on android test: 1. multiplex can send data

2016-03-04T07:43:29.371Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-04T07:43:29.800Z - info: Running on android test: 2. enqueue and run in order

2016-03-04T07:43:30.007Z - info: Running on ios test: 5. queues handled independently

2016-03-04T07:43:30.469Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-04T07:43:30.659Z - info: Running on ios test: 6. basic

2016-03-04T07:43:31.022Z - info: Running on android test: 3. enqueueAtTop and run backwards

2016-03-04T07:43:31.229Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)

2016-03-04T07:43:31.241Z - info: Running on ios test: 7. another

2016-03-04T07:43:31.329Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:6

2016-03-04T07:43:31.330Z - info: Discarding surplus device: samsung-SM-N910C

2016-03-04T07:43:31.481Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-03-04T07:43:31.482Z - info: Discarding surplus device: samsung-SM-G900F

2016-03-04T07:43:32.192Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-04T07:43:32.240Z - info: Running on android test: 4. mix enqueue and enqueueAtTop

2016-03-04T07:43:32.504Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-04T07:43:32.589Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-03-04T07:43:32.675Z - debug: Socket disconnected: transport close 6 (samsung-SM-N910C)

2016-03-04T07:43:32.725Z - info: Running on android test: 5. queues handled independently

2016-03-04T07:43:32.824Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-04T07:43:33.111Z - info: Running on android test: 6. basic

2016-03-04T07:43:33.248Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-04T07:43:33.494Z - info: Running on android test: 7. another

2016-03-04T07:43:33.686Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-04T07:43:34.038Z - info: Running on android test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-04T07:43:34.159Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-04T07:43:34.595Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-04T07:43:34.600Z - info: Running on android test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-04T07:43:35.037Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-04T07:43:35.060Z - info: Running on android test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-04T07:43:35.649Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-04T07:43:35.656Z - info: Running on android test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-04T07:43:36.088Z - info: Running on ios test: 17. can get the network status

2016-03-04T07:43:36.094Z - info: Running on android test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-04T07:43:36.482Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-04T07:43:36.593Z - info: Running on android test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-04T07:43:37.185Z - info: Running on android test: 14. #start should fail if called twice in a row

2016-03-04T07:43:37.610Z - info: Running on android test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-04T07:43:38.197Z - info: Running on android test: 16. does not send duplicate availability changes

2016-03-04T07:43:38.755Z - info: Running on android test: 17. can get the network status

2016-03-04T07:43:39.252Z - info: Running on android test: 18. wifi peer is marked unavailable if announcements stop

2016-03-04T07:43:40.788Z - info: Running on android test: 19. Can call start/stopListeningForAdvertisements

2016-03-04T07:43:42.528Z - info: Running on android test: 20. Calling startListeningForAdvertisements twice is NOT an error

2016-03-04T07:43:43.063Z - info: Running on android test: 21. Can call start/stopUpdateAdvertisingAndListening

2016-03-04T07:43:43.846Z - info: Running on android test: 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-04T07:45:09.160Z - debug: Socket disconnected: ping timeout 5 (motorola-Nexus 6)

2016-03-04T07:56:09.561Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-04T07:56:09.656Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-04T07:59:26.781Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)


 
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
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali02_LGE-Nexus 5.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali04_samsung-SM-N910C.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali07_samsung-SM-A500FU.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali07_samsung-SM-G900F.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/614329799926788_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali09_LGE-Nexus 5.md)





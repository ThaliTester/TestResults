#### Test 61432979123161a Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22}}
2016-03-02T17:40:44.445Z - info: listening on *:3000

2016-03-02T17:40:47.880Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:0

2016-03-02T17:40:48.034Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:1

2016-03-02T17:40:48.558Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:2

2016-03-02T17:40:48.560Z - info: Required number of ios devices presented (2)

2016-03-02T17:40:48.564Z - info: Starting unit test run for platform: ios

2016-03-02T17:40:48.810Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-03-02T17:40:48.812Z - info: Required number of android devices presented (2)

2016-03-02T17:40:48.813Z - info: Starting unit test run for platform: android

2016-03-02T17:40:49.195Z - info: Running on ios test: 1. multiplex can send data

2016-03-02T17:40:49.500Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-03-02T17:40:49.501Z - info: Discarding surplus device: Apple-IpadAir2-1

2016-03-02T17:40:49.526Z - info: Running on android test: 1. multiplex can send data

2016-03-02T17:40:49.757Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-03-02T17:40:49.758Z - info: Discarding surplus device: LGE-LG-H815

2016-03-02T17:40:49.832Z - info: Running on ios test: 2. enqueue and run in order

2016-03-02T17:40:49.913Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:6

2016-03-02T17:40:49.914Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-02T17:40:50.174Z - info: Running on android test: 2. enqueue and run in order

2016-03-02T17:40:50.542Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-02T17:40:50.973Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-03-02T17:40:51.135Z - info: Running on android test: 3. enqueueAtTop and run backwards

2016-03-02T17:40:51.191Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-02T17:40:51.750Z - info: Running on ios test: 5. queues handled independently

2016-03-02T17:40:51.811Z - info: Running on android test: 4. mix enqueue and enqueueAtTop

2016-03-02T17:40:51.934Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-03-02T17:40:52.178Z - info: Running on ios test: 6. basic

2016-03-02T17:40:52.456Z - info: Running on android test: 5. queues handled independently

2016-03-02T17:40:52.524Z - debug: Socket disconnected: transport close 6 (Apple-Iphone5s-1)

2016-03-02T17:40:52.566Z - info: Running on ios test: 7. another

2016-03-02T17:40:53.006Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-02T17:40:53.051Z - info: Running on android test: 6. basic

2016-03-02T17:40:53.738Z - info: Running on android test: 7. another

2016-03-02T17:40:53.755Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T17:40:54.228Z - info: Running on android test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-02T17:40:54.536Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-02T17:40:54.684Z - info: Running on android test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-02T17:40:55.031Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-02T17:40:55.233Z - info: Running on android test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-02T17:40:55.417Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-02T17:40:55.713Z - info: Running on android test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-02T17:40:55.843Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-02T17:40:56.132Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-02T17:40:56.149Z - info: Running on android test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-02T17:40:56.512Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-02T17:40:56.762Z - info: Running on android test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-02T17:40:56.953Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-02T17:40:57.253Z - info: Running on android test: 14. #start should fail if called twice in a row

2016-03-02T17:40:57.376Z - info: Running on ios test: 17. can get the network status

2016-03-02T17:40:57.715Z - info: Running on android test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-02T17:40:57.778Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-02T17:40:58.692Z - info: Running on android test: 16. does not send duplicate availability changes

2016-03-02T17:40:58.751Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:7

2016-03-02T17:40:58.753Z - info: Discarding surplus device: motorola-Nexus 6

2016-03-02T17:40:59.554Z - debug: Socket disconnected: transport close 7 (motorola-Nexus 6)

2016-03-02T17:41:00.370Z - info: Running on android test: 17. can get the network status

2016-03-02T17:41:00.782Z - info: Running on android test: 18. wifi peer is marked unavailable if announcements stop

2016-03-02T17:41:02.332Z - info: Running on android test: 19. Can call start/stopListeningForAdvertisements

2016-03-02T17:41:03.033Z - info: Running on android test: 20. Calling startListeningForAdvertisements twice is NOT an error

2016-03-02T17:41:03.840Z - info: Running on android test: 21. Can call start/stopUpdateAdvertisingAndListening

2016-03-02T17:41:04.676Z - info: Running on android test: 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-02T17:41:05.676Z - info: Running on android test: 23. peerAvailabilityChange is called

2016-03-02T17:53:36.297Z - debug: Socket disconnected: transport close 1 (Apple-Iphone5-1)

2016-03-02T17:53:36.305Z - debug: Socket disconnected: transport close 2 (Apple-Iphone6-1)

2016-03-02T17:58:35.682Z - debug: Socket disconnected: transport close 3 (samsung-SM-G900F)

2016-03-02T17:58:39.932Z - debug: Socket disconnected: transport close 0 (samsung-SM-N910C)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali01_samsung-SM-A500FU.md)

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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali02_LGE-Nexus 5.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali02_LGE-LG-D722.md)

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
[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali04_samsung-SM-N910C.md)

####Node name: thali05
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT4BLJT02274 app:com.test.thalitest code:0 
child process exited with code 0 on device HT4BLJT02274 
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:0 
child process exited with code 0 on device 1d6a772d 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[htc-Nexus 9](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali05_htc-Nexus 9.md)

[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali07_samsung-SM-A500FU.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali07_samsung-SM-G900F.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/61432979123161a_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali09_LGE-Nexus 5.md)





#### Test 61432979dd0fe92 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":2}}
2016-03-10T10:43:58.140Z - info: listening on *:3000

2016-03-10T10:44:01.245Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-10T10:44:02.209Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-10T10:44:02.214Z - info: Required number of ios devices presented (2)

2016-03-10T10:44:02.218Z - info: Starting unit test run for platform: ios

2016-03-10T10:44:02.540Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-10T10:44:02.543Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-10T10:44:03.211Z - info: Running on ios test: 1. multiplex can send data

2016-03-10T10:44:05.644Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-10T10:44:06.197Z - info: Running on ios test: 2. enqueue and run in order

2016-03-10T10:44:08.817Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-10T10:44:11.309Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-10T10:44:12.845Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-10T10:44:14.595Z - info: Running on ios test: 5. queues handled independently

2016-03-10T10:44:18.094Z - info: Running on ios test: 6. basic

2016-03-10T10:44:25.421Z - info: Running on ios test: 7. another

2016-03-10T10:44:29.006Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-10T10:44:32.588Z - debug: Socket disconnected: transport close 1 (NOT YET SET)

2016-03-10T10:44:36.350Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:5

2016-03-10T10:44:36.352Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-10T10:44:41.788Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-10T10:44:42.797Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-10T10:44:45.000Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-10T10:44:46.647Z - debug: Socket disconnected: transport close 5 (Apple-Iphone6-1)

2016-03-10T10:44:48.673Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-10T10:44:50.667Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-10T10:44:51.399Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-10T10:44:53.850Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-10T10:44:54.583Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-10T10:44:56.278Z - info: Running on ios test: 17. can get the network status

2016-03-10T10:44:58.306Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-10T10:59:42.378Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-03-10T10:59:42.420Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)

2016-03-10T11:04:13.363Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)


 
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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/61432979dd0fe92_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/61432979dd0fe92_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/61432979dd0fe92_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/61432979dd0fe92_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/61432979dd0fe92_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/iOS_server.md)


###Android Logs
####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/61432979dd0fe92_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/61432979dd0fe92_PeerDictionary_and_minor_changes_to_thaliNotificationAction_juhanak/thali04_samsung-SM-N910C.md)





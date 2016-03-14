#### Test 6262501074dad8f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":8}}
2016-03-14T22:40:58.491Z - info: listening on *:3000

2016-03-14T22:41:00.010Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:0

2016-03-14T22:41:00.918Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-14T22:41:02.343Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:3

2016-03-14T22:41:02.346Z - info: Required number of ios devices presented (2)

2016-03-14T22:41:02.349Z - info: Starting unit test run for platform: ios

2016-03-14T22:41:02.871Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-14T22:41:03.211Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:4

2016-03-14T22:41:03.214Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-14T22:41:03.309Z - info: Running on ios test: 2. closeAll with promise

2016-03-14T22:41:03.685Z - info: Running on ios test: 3. multiplex can send data

2016-03-14T22:41:03.997Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-14T22:41:04.000Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-14T22:41:04.668Z - info: Running on ios test: 4. enqueue and run in order

2016-03-14T22:41:05.251Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-14T22:41:05.626Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-14T22:41:06.064Z - info: Running on ios test: 7. queues handled independently

2016-03-14T22:41:06.422Z - info: Running on ios test: 8. basic

2016-03-14T22:41:06.452Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5-1)

2016-03-14T22:41:06.835Z - info: Running on ios test: 9. another

2016-03-14T22:41:06.845Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)

2016-03-14T22:41:07.317Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-14T22:41:07.665Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-14T22:41:08.182Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-14T22:41:08.653Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-14T22:41:09.286Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-14T22:41:09.918Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-14T22:41:10.846Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-14T22:41:12.756Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-14T22:41:13.319Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-14T22:41:13.923Z - info: Running on ios test: 19. can get the network status

2016-03-14T22:41:14.497Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-14T22:41:16.958Z - info: Running on ios test: 21. Can call start/stopListeningForAdvertisements

2016-03-14T22:41:17.530Z - info: Running on ios test: 22. Calling startListeningForAdvertisements twice is NOT an error

2016-03-14T22:41:18.133Z - info: Running on ios test: 23. Can call start/stopUpdateAdvertisingAndListening

2016-03-14T22:41:19.115Z - info: Running on ios test: 24. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-14T22:41:19.637Z - info: Running on ios test: 25. peerAvailabilityChange is called

2016-03-14T22:41:21.724Z - info: Running on ios test: 26. Can connect to a remote peer

2016-03-14T22:58:57.853Z - debug: Socket disconnected: transport close 3 (Apple-IpadAir2-1)

2016-03-14T22:58:57.885Z - debug: Socket disconnected: transport close 0 (Apple-Iphone6-1)

2016-03-14T23:01:13.783Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)


 
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
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/thali01_samsung-SM-A500FU.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/thali05_LGE-LG-H815.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6262501074dad8f_WIP_yaronyg/thali08_samsung-SM-A300FU.md)





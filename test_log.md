#### Test 60124347e678b8e Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":10}}
2016-03-10T18:30:14.187Z - info: listening on *:3000

2016-03-10T18:30:17.082Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-03-10T18:30:17.290Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-10T18:30:17.294Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:2

2016-03-10T18:30:17.296Z - info: Required number of ios devices presented (2)

2016-03-10T18:30:17.300Z - info: Starting unit test run for platform: ios

2016-03-10T18:30:17.687Z - info: Running on ios test: 1. closeAll can close even when connections open

2016-03-10T18:30:18.155Z - info: Running on ios test: 2. closeAll with promise

2016-03-10T18:30:18.163Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-10T18:30:18.164Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-10T18:30:18.548Z - info: Running on ios test: 3. multiplex can send data

2016-03-10T18:30:18.901Z - info: Running on ios test: 4. enqueue and run in order

2016-03-10T18:30:19.431Z - info: Running on ios test: 5. enqueueAtTop and run backwards

2016-03-10T18:30:19.547Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:4

2016-03-10T18:30:19.548Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-10T18:30:19.758Z - info: Running on ios test: 6. mix enqueue and enqueueAtTop

2016-03-10T18:30:20.152Z - info: Running on ios test: 7. queues handled independently

2016-03-10T18:30:20.531Z - info: Running on ios test: 8. basic

2016-03-10T18:30:20.881Z - info: Running on ios test: 9. another

2016-03-10T18:30:21.241Z - info: Running on ios test: 10. #startListeningForAdvertisements should fail if start not called

2016-03-10T18:30:21.308Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-10T18:30:21.570Z - info: Running on ios test: 11. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-10T18:30:21.938Z - info: Running on ios test: 12. should be able to call #stopListeningForAdvertisements many times

2016-03-10T18:30:22.088Z - debug: Socket disconnected: transport close 4 (Apple-Iphone5s-1)

2016-03-10T18:30:22.277Z - info: Running on ios test: 13. should be able to call #startListeningForAdvertisements many times

2016-03-10T18:30:22.627Z - info: Running on ios test: 14. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-10T18:30:22.960Z - info: Running on ios test: 15. should be able to call #stopAdvertisingAndListening many times

2016-03-10T18:30:23.294Z - info: Running on ios test: 16. #start should fail if called twice in a row

2016-03-10T18:30:23.630Z - info: Running on ios test: 17. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-10T18:30:24.047Z - info: Running on ios test: 18. does not send duplicate availability changes

2016-03-10T18:30:24.409Z - info: Running on ios test: 19. can get the network status

2016-03-10T18:30:24.887Z - info: Running on ios test: 20. wifi peer is marked unavailable if announcements stop

2016-03-10T18:44:50.588Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1)

2016-03-10T18:44:50.595Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-10T18:47:29.112Z - debug: Socket disconnected: transport close 0 (LGE-LG-H815)


 
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
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:0 
child process exited with code 0 on device f56ad48d 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/thali02_LGE-LG-D722.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/thali03_samsung-SM-N910C.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/thali04_motorola-XT1072.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/thali05_LGE-LG-H815.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/thali06_HTC-HTC One M8s.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/60124347e678b8e_tcpServersManager_and_tests_tobybrad/thali09_LGE-Nexus 5.md)





#### Test 6122644500803c8 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":22}}
2016-03-01T15:21:02.753Z - info: listening on *:3000

2016-03-01T15:21:03.708Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-01T15:21:06.017Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-01T15:21:06.022Z - info: Required number of ios devices presented (2)

2016-03-01T15:21:06.025Z - info: Starting unit test run for platform: ios

2016-03-01T15:21:06.328Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-01T15:21:06.329Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-01T15:21:06.498Z - info: Running on ios test: 1. multiplex can send data

2016-03-01T15:21:07.076Z - info: Running on ios test: 2. enqueue and run in order

2016-03-01T15:21:08.129Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-01T15:21:08.640Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-01T15:21:08.641Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-01T15:21:08.684Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-01T15:21:09.156Z - info: Running on ios test: 5. queues handled independently

2016-03-01T15:21:09.601Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)

2016-03-01T15:21:09.712Z - info: Running on ios test: 6. basic

2016-03-01T15:21:10.285Z - info: Running on ios test: 7. another

2016-03-01T15:21:10.770Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-01T15:21:11.179Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-01T15:21:11.262Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-01T15:21:11.550Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-01T15:21:11.919Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-01T15:21:12.318Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-01T15:21:12.719Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-01T15:21:13.090Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-01T15:21:13.467Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-01T15:21:13.860Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-01T15:21:14.252Z - info: Running on ios test: 17. can get the network status

2016-03-01T15:21:14.726Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-01T15:31:56.823Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-03-01T15:31:56.863Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)


 
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
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali01_samsung-SM-A500FU.md)

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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali02_LGE-Nexus 5.md)

[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali02_LGE-LG-D722.md)

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
[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:0 
child process exited with code 0 on device 0be0c6c6 
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali04_samsung-SM-N910C.md)

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT4BLJT02274 app:com.test.thalitest code:0 
child process exited with code 0 on device HT4BLJT02274 
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
Android task is completed. [FAILED]
```
[htc-Nexus 9](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali05_htc-Nexus 9.md)

[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali07_samsung-SM-A500FU.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali07_samsung-SM-G900F.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/6122644500803c8_CI_test_vjrantal/thali09_LGE-Nexus 5.md)





#### Test 57972094912017a Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-02T13:49:46.921Z - info: listening on *:3000

2016-02-02T13:49:47.789Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:0

2016-02-02T13:49:47.861Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:1

2016-02-02T13:49:48.446Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:2

2016-02-02T13:49:48.448Z - info: Required number of android devices presented (2)

2016-02-02T13:49:48.452Z - info: Starting unit test run for platform: android

2016-02-02T13:49:48.572Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:3

2016-02-02T13:49:48.573Z - info: Discarding surplus device: LGE-LG-D855

2016-02-02T13:49:49.110Z - info: Running on android test: multiplex can send data

2016-02-02T13:49:49.283Z - info: Running on android test: enqueue and run in order

2016-02-02T13:49:49.422Z - debug: Socket disconnected: transport close 3 (LGE-LG-D855)

2016-02-02T13:49:49.519Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:4

2016-02-02T13:49:49.520Z - info: Discarding surplus device: LGE-LG-D722

2016-02-02T13:49:49.585Z - info: Running on android test: basic

2016-02-02T13:49:49.706Z - info: Running on android test: another

2016-02-02T13:49:49.799Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-02T13:49:50.034Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-02T13:49:50.222Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-02T13:49:50.276Z - info: Running on android test: failed to get mobile documents path

2016-02-02T13:49:50.321Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-02T13:49:50.371Z - info: Running on android test: #init should register the networkChanged event

2016-02-02T13:49:50.379Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:5

2016-02-02T13:49:50.380Z - info: Discarding surplus device: LGE-LG-H815

2016-02-02T13:49:50.411Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-02T13:49:50.475Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-02T13:49:50.528Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-02T13:49:50.569Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-02T13:49:50.622Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-02T13:49:50.638Z - debug: Socket disconnected: transport close 4 (LGE-LG-D722)

2016-02-02T13:49:50.694Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-02T13:49:50.743Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-02T13:49:50.792Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:6

2016-02-02T13:49:50.793Z - info: Required number of ios devices presented (2)

2016-02-02T13:49:50.795Z - info: Starting unit test run for platform: ios

2016-02-02T13:49:50.815Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-02T13:49:50.885Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-02-02T13:49:50.886Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-02T13:49:50.900Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-02T13:49:50.975Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-02T13:49:51.053Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-02T13:49:51.125Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-02T13:49:51.173Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-02T13:49:51.214Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-02T13:49:51.261Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-02T13:49:51.343Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815)

2016-02-02T13:49:52.311Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-02-02T13:49:52.817Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:8

2016-02-02T13:49:52.818Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-02T13:49:53.323Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:9

2016-02-02T13:49:53.324Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-02T13:49:53.437Z - debug: Socket disconnected: transport close 8 (samsung-SM-N910C)

2016-02-02T13:49:53.922Z - debug: Socket disconnected: transport close 9 (samsung-SM-G900F)

2016-02-02T13:49:54.413Z - info: Running on ios test: multiplex can send data

2016-02-02T13:51:16.289Z - debug: Socket disconnected: ping timeout 2 (motorola-Nexus 6)

2016-02-02T13:52:05.746Z - debug: Socket disconnected: ping timeout 6 (Apple-Iphone5-1)

2016-02-02T14:03:03.488Z - debug: Socket disconnected: transport close 1 (Apple-IpadAir2-1)

2016-02-02T14:06:28.403Z - debug: Socket disconnected: transport close 0 (LGE-Nexus 5)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali04_samsung-SM-N910C.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/57972094912017a_Address_test_setup_issue_vjrantal/thali09_LGE-Nexus 5.md)





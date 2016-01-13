#### Test 558877588826def Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-13T12:41:14.987Z - info: listening on *:3000

2016-01-13T12:41:15.703Z - debug: Device presented: UNITTEST-0.9367811766694991 (android) unittest socket:0

2016-01-13T12:41:16.052Z - debug: Device presented: UNITTEST-0.31414718098197447 (android) unittest socket:1

2016-01-13T12:41:16.056Z - info: Required number of android devices presented (2)

2016-01-13T12:41:16.059Z - info: Starting unit test run for platform: android

2016-01-13T12:41:16.332Z - debug: Device presented: UNITTEST-0.7219283098803198 (ios) unittest socket:2

2016-01-13T12:41:16.339Z - info: Running test: multiplex can send data

2016-01-13T12:41:16.410Z - debug: Device presented: UNITTEST-0.23280090754912086 (android) unittest socket:3

2016-01-13T12:41:16.411Z - info: Discarding surplus device: UNITTEST-0.23280090754912086

2016-01-13T12:41:16.416Z - debug: Device presented: UNITTEST-0.7478800524923258 (android) unittest socket:4

2016-01-13T12:41:16.417Z - info: Discarding surplus device: UNITTEST-0.7478800524923258

2016-01-13T12:41:16.481Z - info: Running test: basic

2016-01-13T12:41:16.524Z - info: Running test: another

2016-01-13T12:41:16.587Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-13T12:41:16.764Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-13T12:41:16.925Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-13T12:41:16.951Z - debug: Device presented: UNITTEST-0.50186807997831 (ios) unittest socket:5

2016-01-13T12:41:16.952Z - info: Required number of ios devices presented (2)

2016-01-13T12:41:16.954Z - info: Starting unit test run for platform: ios

2016-01-13T12:41:16.989Z - info: Running test: failed to get mobile documents path

2016-01-13T12:41:17.044Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-13T12:41:17.113Z - info: Running test: #init should register the networkChanged event

2016-01-13T12:41:17.165Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-13T12:41:17.200Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.7478800524923258)

2016-01-13T12:41:17.228Z - debug: Device presented: UNITTEST-0.38644778084415554 (android) unittest socket:6

2016-01-13T12:41:17.229Z - info: Discarding surplus device: UNITTEST-0.38644778084415554

2016-01-13T12:41:17.234Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-13T12:41:17.291Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-13T12:41:17.301Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.23280090754912086)

2016-01-13T12:41:17.309Z - info: Running test: multiplex can send data

2016-01-13T12:41:17.360Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-13T12:41:17.410Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-13T12:41:17.454Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-13T12:41:17.503Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-13T12:41:17.564Z - info: Running test: basic

2016-01-13T12:41:17.581Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-13T12:41:17.615Z - debug: Device presented: UNITTEST-0.6945617201282709 (android) unittest socket:7

2016-01-13T12:41:17.616Z - info: Discarding surplus device: UNITTEST-0.6945617201282709

2016-01-13T12:41:17.663Z - info: Running test: another

2016-01-13T12:41:17.676Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-13T12:41:17.752Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-13T12:41:17.759Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-13T12:41:17.811Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-13T12:41:17.868Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-13T12:41:17.908Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.38644778084415554)

2016-01-13T12:41:17.920Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-13T12:41:17.974Z - debug: Device presented: UNITTEST-0.8330561588615252 (android) unittest socket:8

2016-01-13T12:41:17.975Z - info: Discarding surplus device: UNITTEST-0.8330561588615252

2016-01-13T12:41:18.022Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-13T12:41:18.028Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-13T12:41:18.113Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-13T12:41:18.258Z - debug: Device presented: UNITTEST-0.5542581600181123 (android) unittest socket:9

2016-01-13T12:41:18.259Z - info: Discarding surplus device: UNITTEST-0.5542581600181123

2016-01-13T12:41:18.264Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-13T12:41:18.283Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.6945617201282709)

2016-01-13T12:41:18.367Z - debug: Device presented: UNITTEST-0.8168322890321433 (android) unittest socket:10

2016-01-13T12:41:18.370Z - info: Discarding surplus device: UNITTEST-0.8168322890321433

2016-01-13T12:41:18.376Z - info: Running test: failed to get mobile documents path

2016-01-13T12:41:18.443Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-13T12:41:18.500Z - debug: Device presented: UNITTEST-0.24714674380470603 (android) unittest socket:11

2016-01-13T12:41:18.501Z - info: Discarding surplus device: UNITTEST-0.24714674380470603

2016-01-13T12:41:18.511Z - info: Running test: #init should register the networkChanged event

2016-01-13T12:41:18.572Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-13T12:41:18.635Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-13T12:41:18.693Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-13T12:41:18.764Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-13T12:41:18.811Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-13T12:41:18.875Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-13T12:41:18.928Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-13T12:41:19.012Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-13T12:41:19.067Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-13T12:41:19.114Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.8330561588615252)

2016-01-13T12:41:19.122Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-13T12:41:19.148Z - debug: Device presented: UNITTEST-0.6857244496268944 (android) unittest socket:12

2016-01-13T12:41:19.149Z - info: Discarding surplus device: UNITTEST-0.6857244496268944

2016-01-13T12:41:19.154Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.24714674380470603)

2016-01-13T12:41:19.177Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-13T12:41:19.207Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.5542581600181123)

2016-01-13T12:41:19.223Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-13T12:41:19.291Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-13T12:41:19.377Z - debug: Device presented: UNITTEST-0.049022344141965934 (android) unittest socket:13

2016-01-13T12:41:19.378Z - info: Discarding surplus device: UNITTEST-0.049022344141965934

2016-01-13T12:41:19.387Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-13T12:41:19.397Z - debug: Device presented: UNITTEST-0.5831122257615909 (android) unittest socket:14

2016-01-13T12:41:19.397Z - info: Discarding surplus device: UNITTEST-0.5831122257615909

2016-01-13T12:41:19.439Z - debug: Device presented: UNITTEST-0.0007814873498029895 (ios) unittest socket:15

2016-01-13T12:41:19.440Z - info: Discarding surplus device: UNITTEST-0.0007814873498029895

2016-01-13T12:41:19.446Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-13T12:41:19.491Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.8168322890321433)

2016-01-13T12:41:19.769Z - debug: Device presented: UNITTEST-0.4587461547040974 (ios) unittest socket:16

2016-01-13T12:41:19.770Z - info: Discarding surplus device: UNITTEST-0.4587461547040974

2016-01-13T12:41:19.780Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-13T12:41:19.832Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.5831122257615909)

2016-01-13T12:41:19.861Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-13T12:41:19.867Z - debug: Device presented: UNITTEST-0.4942219951310973 (android) unittest socket:17

2016-01-13T12:41:19.868Z - info: Discarding surplus device: UNITTEST-0.4942219951310973

2016-01-13T12:41:19.883Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.049022344141965934)

2016-01-13T12:41:19.968Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-13T12:41:19.980Z - debug: Device presented: UNITTEST-0.5227255759719358 (android) unittest socket:18

2016-01-13T12:41:19.981Z - info: Discarding surplus device: UNITTEST-0.5227255759719358

2016-01-13T12:41:20.085Z - debug: Device presented: UNITTEST-0.6258745242830249 (android) unittest socket:19

2016-01-13T12:41:20.086Z - info: Discarding surplus device: UNITTEST-0.6258745242830249

2016-01-13T12:41:20.156Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.6857244496268944)

2016-01-13T12:41:20.325Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-13T12:41:20.462Z - debug: Device presented: UNITTEST-0.07854865694856539 (android) unittest socket:20

2016-01-13T12:41:20.465Z - info: Discarding surplus device: UNITTEST-0.07854865694856539

2016-01-13T12:41:20.704Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-13T12:41:20.820Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.4942219951310973)

2016-01-13T12:41:20.902Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.6258745242830249)

2016-01-13T12:41:21.146Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.07854865694856539)

2016-01-13T12:41:21.364Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.5227255759719358)

2016-01-13T12:41:22.144Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.0007814873498029895)

2016-01-13T12:41:22.252Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.4587461547040974)

2016-01-13T12:41:22.317Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-13T12:41:24.219Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-13T12:41:25.527Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-13T12:41:28.150Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-13T12:41:30.029Z - debug: Device presented: UNITTEST-0.035287521488094775 (android) unittest socket:21

2016-01-13T12:41:30.030Z - info: Discarding surplus device: UNITTEST-0.035287521488094775

2016-01-13T12:41:31.313Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.035287521488094775)

2016-01-13T12:41:31.751Z - debug: Device presented: UNITTEST-0.07049200472195483 (android) unittest socket:22

2016-01-13T12:41:31.752Z - info: Discarding surplus device: UNITTEST-0.07049200472195483

2016-01-13T12:41:33.249Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.07049200472195483)

2016-01-13T12:41:50.927Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-13T12:43:11.095Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-13T12:43:38.434Z - info: Running test: ThaliEmitter can connect and send data

2016-01-13T12:44:01.932Z - info: Running test: ThaliEmitter handles socket disconnect correctly

2016-01-13T12:44:07.773Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.7219283098803198)

2016-01-13T12:44:32.843Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.50186807997831)

2016-01-13T13:08:05.786Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.9367811766694991)

2016-01-13T13:09:22.980Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.31414718098197447)


 
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
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/iOS_Iphone5s-1.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Device test finished on 320414cd475f91e3 
Android task is completed. [SUCCESS]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on FA55PYS00566 
Device test finished on 022678fb504e29b0 
Android task is completed. [SUCCESS]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on HT574YC04723 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/558877588826def_Run_desktop_tests_in_CI__vjrantal/thali09_LGE-Nexus 5.md)





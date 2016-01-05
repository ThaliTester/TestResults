#### Test 549702617d40def Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-05T01:24:40.041Z - info: listening on *:3000

2016-01-05T01:24:40.807Z - debug: Device presented: UNITTEST-0.021629734735573614 (android) unittest socket:0

2016-01-05T01:24:40.835Z - debug: Device presented: UNITTEST-0.4454420012912953 (android) unittest socket:1

2016-01-05T01:24:40.838Z - info: Required number of devices presented

2016-01-05T01:24:40.887Z - debug: Socket disconnected: client error 1 (UNITTEST-0.4454420012912953)

2016-01-05T01:24:40.895Z - debug: Device presented: UNITTEST-0.10311516438041124 (android) unittest socket:2

2016-01-05T01:24:41.726Z - debug: Device presented: UNITTEST-0.912095390625914 (android) unittest socket:3

2016-01-05T01:24:41.775Z - debug: Device presented: UNITTEST-0.39277985047712727 (android) unittest socket:4

2016-01-05T01:24:41.911Z - debug: Device presented: UNITTEST-0.0032231306935418536 (android) unittest socket:5

2016-01-05T01:24:42.080Z - debug: Device presented: UNITTEST-0.6325124120375434 (android) unittest socket:6

2016-01-05T01:24:42.226Z - debug: Device presented: UNITTEST-0.19259923132351442 (android) unittest socket:7

2016-01-05T01:24:42.283Z - debug: Device presented: UNITTEST-0.7334208870056997 (android) unittest socket:8

2016-01-05T01:24:42.481Z - debug: Device presented: UNITTEST-0.25050653300544157 (ios) unittest socket:9

2016-01-05T01:24:43.101Z - debug: Device presented: UNITTEST-0.4343726327776348 (android) unittest socket:10

2016-01-05T01:24:43.152Z - debug: Device presented: UNITTEST-0.9364724704478162 (android) unittest socket:11

2016-01-05T01:24:43.172Z - debug: Device presented: UNITTEST-0.24038550444790918 (android) unittest socket:12

2016-01-05T01:24:43.736Z - debug: Device presented: UNITTEST-0.5849929725565483 (ios) unittest socket:13

2016-01-05T01:24:43.737Z - info: Required number of devices presented

2016-01-05T01:24:43.751Z - debug: Socket disconnected: client error 13 (UNITTEST-0.5849929725565483)

2016-01-05T01:24:43.795Z - debug: Device presented: UNITTEST-0.527389917826899 (android) unittest socket:14

2016-01-05T01:24:43.953Z - debug: Device presented: UNITTEST-0.950468129205152 (ios) unittest socket:15

2016-01-05T01:24:44.225Z - debug: Device presented: UNITTEST-0.7137638357708973 (ios) unittest socket:16

2016-01-05T01:24:44.253Z - debug: Device presented: UNITTEST-0.9916094088799979 (android) unittest socket:17

2016-01-05T01:24:44.332Z - debug: Device presented: UNITTEST-0.659902383871958 (android) unittest socket:18

2016-01-05T01:24:44.948Z - debug: Device presented: UNITTEST-0.5327002185466752 (android) unittest socket:19

2016-01-05T01:25:00.142Z - debug: Device presented: UNITTEST-0.2619933943142495 (android) unittest socket:20

2016-01-05T01:25:10.298Z - debug: Device presented: UNITTEST-0.10738921224200271 (android) unittest socket:21

2016-01-05T01:46:49.391Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.25050653300544157)

2016-01-05T01:46:49.415Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.7137638357708973)

2016-01-05T01:46:49.425Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.950468129205152)

2016-01-05T01:50:45.103Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.0032231306935418536)

2016-01-05T01:50:45.913Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.021629734735573614)

2016-01-05T01:50:46.760Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.7334208870056997)

2016-01-05T01:50:47.221Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.527389917826899)

2016-01-05T01:50:49.881Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.912095390625914)

2016-01-05T01:50:51.884Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.6325124120375434)

2016-01-05T01:50:54.275Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.24038550444790918)

2016-01-05T01:51:15.240Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.659902383871958)

2016-01-05T01:51:17.603Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.39277985047712727)

2016-01-05T01:51:47.495Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.9916094088799979)

2016-01-05T01:51:52.921Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.9364724704478162)

2016-01-05T01:52:19.631Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.4343726327776348)

2016-01-05T01:52:21.939Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.10311516438041124)

2016-01-05T01:52:24.423Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.19259923132351442)

2016-01-05T01:55:05.994Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.2619933943142495)

2016-01-05T01:55:11.614Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.10738921224200271)

2016-01-05T01:55:12.891Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.5327002185466752)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
Missing error handler on `socket`.

TypeError: Cannot call method 'slice' of undefined
    at UnitTestFramework.startTests (/home/pi/Test/server_549702617d40def/test/TestServer/UnitTestFramework.js:36:22)
    at UnitTestFramework.TestFramework.addDevice (/home/pi/Test/server_549702617d40def/test/TestServer/TestFramework.js:88:10)
    at Socket.<anonymous> (/home/pi/Test/server_549702617d40def/test/TestServer/index.js:89:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/lib/client.js:175:18)

Missing error handler on `socket`.

TypeError: Cannot call method 'slice' of undefined
    at UnitTestFramework.startTests (/home/pi/Test/server_549702617d40def/test/TestServer/UnitTestFramework.js:36:22)
    at UnitTestFramework.TestFramework.addDevice (/home/pi/Test/server_549702617d40def/test/TestServer/TestFramework.js:88:10)
    at Socket.<anonymous> (/home/pi/Test/server_549702617d40def/test/TestServer/index.js:89:25)
    at Socket.emit (events.js:82:17)
    at Socket.onevent (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/lib/socket.js:330:8)
    at Socket.onpacket (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/lib/socket.js:290:12)
    at Client.ondecoded (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/lib/client.js:193:14)
    at Decoder.Emitter.emit (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:20)
    at Decoder.add (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/node_modules/socket.io-parser/index.js:247:12)
    at Client.ondata (/home/pi/Test/server_549702617d40def/test/TestServer/node_modules/socket.io/lib/client.js:175:18)


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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Android task is completed. [FAILED]
```
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali03_LGE-LG-D855.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702617d40def_Switch_to_Unit_Tests_tobybrad/thali09_LGE-Nexus 5.md)





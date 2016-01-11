#### Test 549702617e2936d Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-11T15:24:31.170Z - info: listening on *:3000

2016-01-11T15:24:31.896Z - debug: Device presented: UNITTEST-0.5270898397212642 (android) unittest socket:0

2016-01-11T15:24:32.495Z - debug: Device presented: UNITTEST-0.19677850207671954 (android) unittest socket:1

2016-01-11T15:24:32.500Z - info: Required number of android devices presented (2)

2016-01-11T15:24:32.503Z - info: Starting unit test run for platform: android

2016-01-11T15:24:32.979Z - debug: Device presented: UNITTEST-0.11888385915040267 (android) unittest socket:4

2016-01-11T15:24:32.980Z - info: Discarding surplus device: UNITTEST-0.11888385915040267

2016-01-11T15:24:32.991Z - debug: Device presented: UNITTEST-0.6682456239263366 (android) unittest socket:2

2016-01-11T15:24:32.994Z - info: Discarding surplus device: UNITTEST-0.6682456239263366

2016-01-11T15:24:33.075Z - debug: Device presented: UNITTEST-0.7541648722558515 (android) unittest socket:5

2016-01-11T15:24:33.076Z - info: Discarding surplus device: UNITTEST-0.7541648722558515

2016-01-11T15:24:33.143Z - debug: Device presented: UNITTEST-0.4024875898950321 (android) unittest socket:6

2016-01-11T15:24:33.144Z - info: Discarding surplus device: UNITTEST-0.4024875898950321

2016-01-11T15:24:33.178Z - debug: Device presented: UNITTEST-0.9937975801780851 (ios) unittest socket:3

2016-01-11T15:24:33.403Z - debug: Device presented: UNITTEST-0.3105476316722485 (ios) unittest socket:7

2016-01-11T15:24:33.404Z - info: Required number of ios devices presented (2)

2016-01-11T15:24:33.406Z - info: Starting unit test run for platform: ios

2016-01-11T15:24:33.557Z - info: Running test: multiplex can send data

2016-01-11T15:24:33.666Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.4024875898950321)

2016-01-11T15:24:33.861Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.7541648722558515)

2016-01-11T15:24:33.936Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.6682456239263366)

2016-01-11T15:24:34.019Z - debug: Device presented: UNITTEST-0.8008861874851496 (ios) unittest socket:8

2016-01-11T15:24:34.020Z - info: Discarding surplus device: UNITTEST-0.8008861874851496

2016-01-11T15:24:34.043Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.11888385915040267)

2016-01-11T15:24:34.199Z - debug: Device presented: UNITTEST-0.09236596523810026 (android) unittest socket:9

2016-01-11T15:24:34.200Z - info: Discarding surplus device: UNITTEST-0.09236596523810026

2016-01-11T15:24:34.409Z - debug: Device presented: UNITTEST-0.01088336492296671 (android) unittest socket:10

2016-01-11T15:24:34.410Z - info: Discarding surplus device: UNITTEST-0.01088336492296671

2016-01-11T15:24:34.435Z - info: Running test: multiplex can send data

2016-01-11T15:24:34.619Z - debug: Device presented: UNITTEST-0.263709903070077 (android) unittest socket:11

2016-01-11T15:24:34.622Z - info: Discarding surplus device: UNITTEST-0.263709903070077

2016-01-11T15:24:34.772Z - debug: Device presented: UNITTEST-0.08162904086704947 (android) unittest socket:12

2016-01-11T15:24:34.774Z - info: Discarding surplus device: UNITTEST-0.08162904086704947

2016-01-11T15:24:34.796Z - info: Running test: muxServerBridge

2016-01-11T15:24:34.938Z - debug: Device presented: UNITTEST-0.9574994772151062 (android) unittest socket:13

2016-01-11T15:24:34.939Z - info: Discarding surplus device: UNITTEST-0.9574994772151062

2016-01-11T15:24:35.129Z - debug: Device presented: UNITTEST-0.5679588877459778 (android) unittest socket:14

2016-01-11T15:24:35.130Z - info: Discarding surplus device: UNITTEST-0.5679588877459778

2016-01-11T15:24:35.181Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.01088336492296671)

2016-01-11T15:24:35.197Z - debug: Device presented: UNITTEST-0.5641325355614865 (android) unittest socket:16

2016-01-11T15:24:35.198Z - info: Discarding surplus device: UNITTEST-0.5641325355614865

2016-01-11T15:24:35.252Z - debug: Device presented: UNITTEST-0.553056156939952 (android) unittest socket:15

2016-01-11T15:24:35.253Z - info: Discarding surplus device: UNITTEST-0.553056156939952

2016-01-11T15:24:35.288Z - debug: Device presented: UNITTEST-0.5509084518661824 (android) unittest socket:17

2016-01-11T15:24:35.289Z - info: Discarding surplus device: UNITTEST-0.5509084518661824

2016-01-11T15:24:35.357Z - debug: Device presented: UNITTEST-0.8666571089968171 (ios) unittest socket:18

2016-01-11T15:24:35.358Z - info: Discarding surplus device: UNITTEST-0.8666571089968171

2016-01-11T15:24:35.370Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.263709903070077)

2016-01-11T15:24:35.375Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.09236596523810026)

2016-01-11T15:24:35.446Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.08162904086704947)

2016-01-11T15:24:35.595Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.9574994772151062)

2016-01-11T15:24:35.615Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.5679588877459778)

2016-01-11T15:24:35.827Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.5641325355614865)

2016-01-11T15:24:36.093Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.553056156939952)

2016-01-11T15:24:36.139Z - debug: Device presented: UNITTEST-0.7572041437850119 (android) unittest socket:19

2016-01-11T15:24:36.140Z - info: Discarding surplus device: UNITTEST-0.7572041437850119

2016-01-11T15:24:36.149Z - debug: Device presented: UNITTEST-0.8603489283026262 (android) unittest socket:20

2016-01-11T15:24:36.150Z - info: Discarding surplus device: UNITTEST-0.8603489283026262

2016-01-11T15:24:36.271Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.5509084518661824)

2016-01-11T15:24:36.553Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.8008861874851496)

2016-01-11T15:24:36.763Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.7572041437850119)

2016-01-11T15:24:36.956Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.8603489283026262)

2016-01-11T15:24:38.631Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.8666571089968171)

2016-01-11T15:24:45.195Z - debug: Device presented: UNITTEST-0.26009198097204 (android) unittest socket:21

2016-01-11T15:24:45.196Z - info: Discarding surplus device: UNITTEST-0.26009198097204

2016-01-11T15:24:46.319Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.26009198097204)

2016-01-11T15:25:05.986Z - debug: Device presented: UNITTEST-0.7792841090942044 (android) unittest socket:22

2016-01-11T15:25:05.987Z - info: Discarding surplus device: UNITTEST-0.7792841090942044

2016-01-11T15:25:06.742Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.7792841090942044)

2016-01-11T15:46:51.534Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.3105476316722485)

2016-01-11T15:46:51.578Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.9937975801780851)

2016-01-11T15:50:42.299Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.19677850207671954)

2016-01-11T15:51:55.607Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.5270898397212642)


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed. [SUCCESS]
```
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali03_LGE-LG-D855.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1C223JKW 
Device test finished on 0be0c6c6 
Android task is completed. [SUCCESS]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on HT574YC04723 
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702617e2936d_Switch_to_Unit_Tests_tobybrad/thali09_LGE-Nexus 5.md)





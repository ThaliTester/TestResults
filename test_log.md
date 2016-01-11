#### Test 549702617cfd775 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-11T14:05:12.116Z - info: listening on *:3000

2016-01-11T14:05:12.785Z - debug: Device presented: UNITTEST-0.9915626827066782 (android) unittest socket:0

2016-01-11T14:05:12.807Z - debug: Device presented: UNITTEST-0.7533069737949123 (ios) unittest socket:1

2016-01-11T14:05:12.853Z - debug: Device presented: UNITTEST-0.2012846932927902 (ios) unittest socket:2

2016-01-11T14:05:12.856Z - info: Required number of ios devices presented (2)

2016-01-11T14:05:12.860Z - info: Starting unit test run for platform: ios

2016-01-11T14:05:13.081Z - info: Running test: multiplex can send data

2016-01-11T14:05:13.201Z - debug: Device presented: UNITTEST-0.5742912214454623 (android) unittest socket:3

2016-01-11T14:05:13.202Z - info: Required number of android devices presented (2)

2016-01-11T14:05:13.204Z - info: Starting unit test run for platform: android

2016-01-11T14:05:13.327Z - info: Running test: muxServerBridge

2016-01-11T14:05:13.552Z - debug: Device presented: UNITTEST-0.20385626470861662 (android) unittest socket:4

2016-01-11T14:05:13.555Z - info: Discarding surplus device: UNITTEST-0.20385626470861662

2016-01-11T14:05:13.676Z - debug: Device presented: UNITTEST-0.014811267148089002 (android) unittest socket:5

2016-01-11T14:05:13.677Z - info: Discarding surplus device: UNITTEST-0.014811267148089002

2016-01-11T14:05:13.834Z - debug: Device presented: UNITTEST-0.005086356638965062 (android) unittest socket:6

2016-01-11T14:05:13.835Z - info: Discarding surplus device: UNITTEST-0.005086356638965062

2016-01-11T14:05:13.884Z - debug: Device presented: UNITTEST-0.3566824058040804 (android) unittest socket:7

2016-01-11T14:05:13.885Z - info: Discarding surplus device: UNITTEST-0.3566824058040804

2016-01-11T14:05:14.008Z - debug: Device presented: UNITTEST-0.8233495135222029 (android) unittest socket:8

2016-01-11T14:05:14.009Z - info: Discarding surplus device: UNITTEST-0.8233495135222029

2016-01-11T14:05:14.051Z - info: Running test: multiplex can send data

2016-01-11T14:05:14.172Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.014811267148089002)

2016-01-11T14:05:14.188Z - debug: Device presented: UNITTEST-0.8416401052273101 (ios) unittest socket:9

2016-01-11T14:05:14.189Z - info: Discarding surplus device: UNITTEST-0.8416401052273101

2016-01-11T14:05:14.272Z - debug: Device presented: UNITTEST-0.8036049483438522 (android) unittest socket:11

2016-01-11T14:05:14.275Z - info: Discarding surplus device: UNITTEST-0.8036049483438522

2016-01-11T14:05:14.312Z - debug: Device presented: UNITTEST-0.8773251361468476 (android) unittest socket:10

2016-01-11T14:05:14.314Z - info: Discarding surplus device: UNITTEST-0.8773251361468476

2016-01-11T14:05:14.371Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.20385626470861662)

2016-01-11T14:05:14.427Z - info: Running test: muxServerBridge

2016-01-11T14:05:14.432Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.005086356638965062)

2016-01-11T14:05:14.623Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.8233495135222029)

2016-01-11T14:05:14.743Z - debug: Device presented: UNITTEST-0.22429446527932684 (android) unittest socket:12

2016-01-11T14:05:14.744Z - info: Discarding surplus device: UNITTEST-0.22429446527932684

2016-01-11T14:05:14.990Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.3566824058040804)

2016-01-11T14:05:15.147Z - debug: Device presented: UNITTEST-0.6982263157068438 (android) unittest socket:13

2016-01-11T14:05:15.148Z - info: Discarding surplus device: UNITTEST-0.6982263157068438

2016-01-11T14:05:15.293Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.8036049483438522)

2016-01-11T14:05:15.337Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.22429446527932684)

2016-01-11T14:05:15.445Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.8773251361468476)

2016-01-11T14:05:15.527Z - debug: Device presented: UNITTEST-0.3103172152477336 (android) unittest socket:14

2016-01-11T14:05:15.528Z - info: Discarding surplus device: UNITTEST-0.3103172152477336

2016-01-11T14:05:15.652Z - debug: Device presented: UNITTEST-0.8093599977026357 (android) unittest socket:15

2016-01-11T14:05:15.653Z - info: Discarding surplus device: UNITTEST-0.8093599977026357

2016-01-11T14:05:15.926Z - debug: Device presented: UNITTEST-0.6565840910159989 (ios) unittest socket:16

2016-01-11T14:05:15.927Z - info: Discarding surplus device: UNITTEST-0.6565840910159989

2016-01-11T14:05:15.992Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.3103172152477336)

2016-01-11T14:05:16.046Z - debug: Device presented: UNITTEST-0.03565062330040569 (android) unittest socket:17

2016-01-11T14:05:16.050Z - info: Discarding surplus device: UNITTEST-0.03565062330040569

2016-01-11T14:05:16.241Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.6982263157068438)

2016-01-11T14:05:16.705Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.8093599977026357)

2016-01-11T14:05:16.711Z - debug: Device presented: UNITTEST-0.5016684603143235 (android) unittest socket:18

2016-01-11T14:05:16.714Z - info: Discarding surplus device: UNITTEST-0.5016684603143235

2016-01-11T14:05:16.728Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.8416401052273101)

2016-01-11T14:05:16.820Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.03565062330040569)

2016-01-11T14:05:16.967Z - debug: Device presented: UNITTEST-0.42191166814552405 (android) unittest socket:19

2016-01-11T14:05:16.969Z - info: Discarding surplus device: UNITTEST-0.42191166814552405

2016-01-11T14:05:17.093Z - debug: Device presented: UNITTEST-0.024852740003749374 (android) unittest socket:20

2016-01-11T14:05:17.097Z - info: Discarding surplus device: UNITTEST-0.024852740003749374

2016-01-11T14:05:17.355Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.5016684603143235)

2016-01-11T14:05:17.617Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.42191166814552405)

2016-01-11T14:05:17.900Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.024852740003749374)

2016-01-11T14:05:18.416Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.6565840910159989)

2016-01-11T14:05:24.632Z - debug: Device presented: UNITTEST-0.13722787297746808 (android) unittest socket:21

2016-01-11T14:05:24.634Z - info: Discarding surplus device: UNITTEST-0.13722787297746808

2016-01-11T14:05:25.727Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.13722787297746808)

2016-01-11T14:06:08.664Z - debug: Device presented: UNITTEST-0.5056357683318967 (android) unittest socket:22

2016-01-11T14:06:08.666Z - info: Discarding surplus device: UNITTEST-0.5056357683318967

2016-01-11T14:06:09.372Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.5056357683318967)

2016-01-11T14:27:46.484Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.7533069737949123)

2016-01-11T14:27:46.507Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.2012846932927902)

2016-01-11T14:31:54.690Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.9915626827066782)

2016-01-11T14:33:06.268Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.5742912214454623)


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on ZX1C223JKW 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/549702617cfd775_Switch_to_Unit_Tests_tobybrad/thali09_LGE-Nexus 5.md)





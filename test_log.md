#### Test 51335028813a553 Logs

Status: 
```

ios : false

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
Start Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}

Start iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}

listening on *:3000

Android  LGE-LG-D802_PT5463 added : 0.609 sec., device count 1

Android  LGE-LG-D722_PT3649 added : 0.776 sec., device count 2

Android  samsung-SM-N9005_PT8082 added : 0.907 sec., device count 3

Android  motorola-Nexus 6_PT3253 added : 1.151 sec., device count 4

Android  motorola-XT1039_PT5642 added : 1.493 sec., device count 5

Android  samsung-SM-A300FU_PT2780 added : 1.505 sec., device count 6

Android  LGE-Nexus 5_PT5707 added : 2.052 sec., device count 7

Android  LGE-LG-H815_PT2470 added : 2.195 sec., device count 8

Android  HTC-HTC One_M8_PT5322 added : 2.354 sec., device count 9

Android  samsung-SM-A500FU_PT3216 added : 3 sec., device count 10

Android  HTC-HTC Desire 820_PT7281 added : 3.06 sec., device count 11

Android  LGE-Nexus 5_PT8041 added : 3.157 sec., device count 12

Android  HUAWEI-ALE-L21_PT9771 added : 3.356 sec., device count 13

Android  LGE-LG-D855_PT9528 added : 3.48 sec., device count 14

iOs  Apple-Iphone6-1_PT2043 added : 4.265 sec., device count 1

Android  HTC-HTC Desire 820_PT1823 added : 4.287 sec., device count 15

Android  samsung-SM-G800F_PT7313 added : 4.58 sec., device count 16

Android  samsung-SM-A300FU_PT8636 added : 4.611 sec., device count 17

Android  samsung-SM-G900F_PT8620 added : 4.748 sec., device count 18

iOs  Apple-Iphone5-1_PT2716 added : 4.914 sec., device count 2

iOs  Apple-Iphone5s-1_PT497 added : 4.967 sec., device count 3

iOs  Apple-IpadAir2-1_PT7072 added : 5.291 sec., device count 4

Android  motorola-XT1072_PT6286 added : 6.035 sec., device count 19

Android  samsung-SM-N910C_PT543 added : 10.19 sec., device count 20

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 20 devices, time now: 300.081 sec.

start test[0] with 20 devices.

-----iOs start testing now with 4 devices, time now: 300.111 sec.

start test[0] with 4 devices.

iOs Apple-Iphone5s-1_PT497 got disconnected

Android samsung-SM-A300FU_PT8636 got disconnected

Android LGE-Nexus 5_PT5707 got disconnected

iOs Apple-Iphone6-1_PT2043 got disconnected

iOs Apple-Iphone6-1_PT2043 got re-connected event  ####################################################

Android LGE-LG-D722_PT3649 got disconnected

iOs with Apple-IpadAir2-1_PT7072 request took : 142091 ms. results peers[0], reConnects[0], sendData[3], time now: 442.206 sec.

iOs Apple-Iphone5s-1_PT497 got re-connected event  ####################################################

iOs with Apple-Iphone5-1_PT2716 request took : 167777 ms. results peers[0], reConnects[0], sendData[3], time now: 467.89 sec.

iOs with Apple-Iphone6-1_PT2043 request took : 174064 ms. results peers[0], reConnects[0], sendData[3], time now: 474.177 sec.

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android LGE-Nexus 5_PT5707 got disconnected

iOs with Apple-Iphone5s-1_PT497 request took : 264964 ms. results peers[0], reConnects[0], sendData[3], time now: 565.078 sec.

------------------------------------------------------
iOs test[ 0] done now. , time now: 565.079 sec.

iOs All tests are done, preparing test report. , time now: 565.088 sec.

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT2043 --------------------- : 1

sendList : 100% : 84289 ms, 99% : 84289 ms, 95 : 84289 ms, 90% : 84289 ms.

Result count 3, range 31207 ms to  84289 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT2716 --------------------- : 2

sendList : 100% : 107161 ms, 99% : 107161 ms, 95 : 107161 ms, 90% : 107161 ms.
Result count 3, range 26141 ms to  107161 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT497 --------------------- : 3
sendList : 100% : 70969 ms, 99% : 70969 ms, 95 : 70969 ms, 90% : 70969 ms.

Result count 2, range 31099 ms to  70969 ms.
sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone5-1_PT2716.py/N2Q==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT7072 --------------------- : 4
sendList : 100% : 58779 ms, 99% : 58779 ms, 95 : 58779 ms, 90% : 58779 ms.

Result count 3, range 29961 ms to  58779 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 107161 ms, 99% : 107161 ms, 95 : 84289 ms, 90% : 84289 ms.

--------------- end of test report ---------------------

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android LGE-Nexus 5_PT5707 got disconnected

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android LGE-Nexus 5_PT5707 got disconnected

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT1823 got disconnected

Android LGE-Nexus 5_PT5707 got disconnected

Android motorola-Nexus 6_PT3253 got re-connected event  ####################################################

Android motorola-XT1072_PT6286 got re-connected event  ####################################################

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android motorola-XT1072_PT6286 got disconnected

Android motorola-Nexus 6_PT3253 got disconnected

Android LGE-Nexus 5_PT5707 got disconnected

Android samsung-SM-N910C_PT543 got disconnected

Android LGE-Nexus 5_PT5707 got disconnected

Android LGE-Nexus 5_PT8041 got disconnected

Android HTC-HTC Desire 820_PT7281 got disconnected

Android LGE-LG-H815_PT2470 got disconnected

Android HUAWEI-ALE-L21_PT9771 got disconnected

Android samsung-SM-A500FU_PT3216 got disconnected

Android samsung-SM-A300FU_PT2780 got disconnected

Android LGE-LG-D802_PT5463 got disconnected

Android samsung-SM-N9005_PT8082 got disconnected

Android motorola-Nexus 6_PT3253 got disconnected

Android HTC-HTC One_M8_PT5322 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali01
####Node name: thali02
####Node name: thali03
Console output:
```
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:null 
child process exited with code null on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:null 
child process exited with code null on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed 
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/51335028813a553_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/51335028813a553_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/51335028813a553_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:null 
child process exited with code null on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed 
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/51335028813a553_Work_in_progress__vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/51335028813a553_Work_in_progress__vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/51335028813a553_Work_in_progress__vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali05
####Node name: thali06
####Node name: thali07
####Node name: thali08
####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
```



###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/51335028813a553_Work_in_progress__vjrantal/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/51335028813a553_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/51335028813a553_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/51335028813a553_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)


#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":21}}
Start Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}

Start iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"10000000","conReTryTimeout":"1000","conReTryCount":"5"}

listening on *:3000

Android  LGE-LG-D802_PT5463 added : 0.609 sec., device count 1

Android  LGE-LG-D722_PT3649 added : 0.776 sec., device count 2

Android  samsung-SM-N9005_PT8082 added : 0.907 sec., device count 3

Android  motorola-Nexus 6_PT3253 added : 1.151 sec., device count 4

Android  motorola-XT1039_PT5642 added : 1.493 sec., device count 5

Android  samsung-SM-A300FU_PT2780 added : 1.505 sec., device count 6

Android  LGE-Nexus 5_PT5707 added : 2.052 sec., device count 7

Android  LGE-LG-H815_PT2470 added : 2.195 sec., device count 8

Android  HTC-HTC One_M8_PT5322 added : 2.354 sec., device count 9

Android  samsung-SM-A500FU_PT3216 added : 3 sec., device count 10

Android  HTC-HTC Desire 820_PT7281 added : 3.06 sec., device count 11

Android  LGE-Nexus 5_PT8041 added : 3.157 sec., device count 12

Android  HUAWEI-ALE-L21_PT9771 added : 3.356 sec., device count 13

Android  LGE-LG-D855_PT9528 added : 3.48 sec., device count 14

iOs  Apple-Iphone6-1_PT2043 added : 4.265 sec., device count 1

Android  HTC-HTC Desire 820_PT1823 added : 4.287 sec., device count 15

Android  samsung-SM-G800F_PT7313 added : 4.58 sec., device count 16

Android  samsung-SM-A300FU_PT8636 added : 4.611 sec., device count 17

Android  samsung-SM-G900F_PT8620 added : 4.748 sec., device count 18

iOs  Apple-Iphone5-1_PT2716 added : 4.914 sec., device count 2

iOs  Apple-Iphone5s-1_PT497 added : 4.967 sec., device count 3

iOs  Apple-IpadAir2-1_PT7072 added : 5.291 sec., device count 4

Android  motorola-XT1072_PT6286 added : 6.035 sec., device count 19

Android  samsung-SM-N910C_PT543 added : 10.19 sec., device count 20

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 20 devices, time now: 300.081 sec.

start test[0] with 20 devices.

-----iOs start testing now with 4 devices, time now: 300.111 sec.

start test[0] with 4 devices.

iOs Apple-Iphone5s-1_PT497 got disconnected

Android samsung-SM-A300FU_PT8636 got disconnected

Android LGE-Nexus 5_PT5707 got disconnected

iOs Apple-Iphone6-1_PT2043 got disconnected

iOs Apple-Iphone6-1_PT2043 got re-connected event  ####################################################

Android LGE-LG-D722_PT3649 got disconnected

iOs with Apple-IpadAir2-1_PT7072 request took : 142091 ms. results peers[0], reConnects[0], sendData[3], time now: 442.206 sec.

iOs Apple-Iphone5s-1_PT497 got re-connected event  ####################################################

iOs with Apple-Iphone5-1_PT2716 request took : 167777 ms. results peers[0], reConnects[0], sendData[3], time now: 467.89 sec.

iOs with Apple-Iphone6-1_PT2043 request took : 174064 ms. results peers[0], reConnects[0], sendData[3], time now: 474.177 sec.

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android LGE-Nexus 5_PT5707 got disconnected

iOs with Apple-Iphone5s-1_PT497 request took : 264964 ms. results peers[0], reConnects[0], sendData[3], time now: 565.078 sec.

------------------------------------------------------
iOs test[ 0] done now. , time now: 565.079 sec.

iOs All tests are done, preparing test report. , time now: 565.088 sec.

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT2043 --------------------- : 1

sendList : 100% : 84289 ms, 99% : 84289 ms, 95 : 84289 ms, 90% : 84289 ms.

Result count 3, range 31207 ms to  84289 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5-1_PT2716 --------------------- : 2

sendList : 100% : 107161 ms, 99% : 107161 ms, 95 : 107161 ms, 90% : 107161 ms.
Result count 3, range 26141 ms to  107161 ms.

sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT497 --------------------- : 3
sendList : 100% : 70969 ms, 99% : 70969 ms, 95 : 70969 ms, 90% : 70969 ms.

Result count 2, range 31099 ms to  70969 ms.
sendList failed peers count : 1 [33.333333333333336 %]

- Peer ID : Apple-Iphone5-1_PT2716.py/N2Q==, Tried : 5
sendList never tried peers count : 0 [0 %]

--------------- Apple-IpadAir2-1_PT7072 --------------------- : 4
sendList : 100% : 58779 ms, 99% : 58779 ms, 95 : 58779 ms, 90% : 58779 ms.

Result count 3, range 29961 ms to  58779 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------

sendList : 100% : 107161 ms, 99% : 107161 ms, 95 : 84289 ms, 90% : 84289 ms.

--------------- end of test report ---------------------

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android LGE-Nexus 5_PT5707 got disconnected

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android LGE-Nexus 5_PT5707 got disconnected

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT1823 got disconnected

Android LGE-Nexus 5_PT5707 got disconnected

Android motorola-Nexus 6_PT3253 got re-connected event  ####################################################

Android motorola-XT1072_PT6286 got re-connected event  ####################################################

Android LGE-Nexus 5_PT5707 got re-connected event  ####################################################

Android motorola-XT1072_PT6286 got disconnected

Android motorola-Nexus 6_PT3253 got disconnected

Android LGE-Nexus 5_PT5707 got disconnected

Android samsung-SM-N910C_PT543 got disconnected

Android LGE-Nexus 5_PT5707 got disconnected

Android LGE-Nexus 5_PT8041 got disconnected

Android HTC-HTC Desire 820_PT7281 got disconnected

Android LGE-LG-H815_PT2470 got disconnected

Android HUAWEI-ALE-L21_PT9771 got disconnected

Android samsung-SM-A500FU_PT3216 got disconnected

Android samsung-SM-A300FU_PT2780 got disconnected

Android LGE-LG-D802_PT5463 got disconnected

Android samsung-SM-N9005_PT8082 got disconnected

Android motorola-Nexus 6_PT3253 got disconnected

Android HTC-HTC One_M8_PT5322 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


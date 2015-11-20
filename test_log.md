#### Test 513350285301d5d Logs

Status: 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":18}}
Start Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}
Start iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}

listening on *:3000

Android  LGE-Nexus 5_PT256 added : 0.501 sec., device count 1

Android  LGE-LG-D855_PT3840 added : 0.516 sec., device count 2

Android  samsung-SM-N9005_PT1397 added : 0.553 sec., device count 3

Android  samsung-SM-A300FU_PT3480 added : 0.75 sec., device count 4

Android  motorola-Nexus 6_PT8419 added : 1.304 sec., device count 5

Android  HTC-HTC Desire 820_PT1268 added : 1.359 sec., device count 6

Android  samsung-SM-G900F_PT6801 added : 1.68 sec., device count 7

iOs  Apple-Iphone6-1_PT1072 added : 1.685 sec., device count 1

Android  LGE-LG-H815_PT4879 added : 1.866 sec., device count 8

Android  LGE-LG-D722_PT9856 added : 2.86 sec., device count 9

Android  HTC-HTC One_M8_PT9545 added : 3.654 sec., device count 10

Android  LGE-Nexus 5_PT6584 added : 4.256 sec., device count 11

iOs  Apple-IpadAir2-1_PT9009 added : 4.272 sec., device count 2

Android  HTC-HTC Desire 820_PT2083 added : 4.432 sec., device count 12

iOs  Apple-Iphone5s-1_PT4752 added : 4.645 sec., device count 3

Android  motorola-XT1072_PT7166 added : 4.968 sec., device count 13

Android  HUAWEI-ALE-L21_PT4378 added : 5.171 sec., device count 14

Android  samsung-SM-N910C_PT7533 added : 5.205 sec., device count 15

Android  samsung-SM-A500FU_PT7255 added : 5.208 sec., device count 16

Android  samsung-SM-G800F_PT230 added : 5.307 sec., device count 17

Android  motorola-XT1039_PT5843 added : 5.445 sec., device count 18

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 18 devices, time now: 300.078 sec.

start test[0] with 18 devices.

-----iOs start testing now with 3 devices, time now: 300.106 sec.

start test[0] with 3 devices.

iOs with Apple-Iphone5s-1_PT4752 request took : 17899 ms. results peers[0], reConnects[0], sendData[2], time now: 318.007 sec.

iOs with Apple-Iphone6-1_PT1072 request took : 18466 ms. results peers[0], reConnects[0], sendData[2], time now: 318.573 sec.

iOs with Apple-IpadAir2-1_PT9009 request took : 18482 ms. results peers[0], reConnects[0], sendData[2], time now: 318.59 sec.

------------------------------------------------------
iOs test[ 0] done now. , time now: 318.591 sec.

iOs All tests are done, preparing test report. , time now: 318.597 sec.

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT1072 --------------------- : 1

sendList : 100% : 9143 ms, 99% : 9143 ms, 95 : 9143 ms, 90% : 9143 ms.

Result count 2, range 8431 ms to  9143 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT9009 --------------------- : 2

sendList : 100% : 8788 ms, 99% : 8788 ms, 95 : 8788 ms, 90% : 8788 ms.

Result count 2, range 8391 ms to  8788 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT4752 --------------------- : 3

sendList : 100% : 8368 ms, 99% : 8368 ms, 95 : 8368 ms, 90% : 8368 ms.
Result count 2, range 8359 ms to  8368 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
sendList : 100% : 9143 ms, 99% : 9143 ms, 95 : 9143 ms, 90% : 8788 ms.

--------------- end of test report ---------------------

Android HTC-HTC One_M8_PT9545 got re-connected event  ####################################################

Android LGE-Nexus 5_PT256 got disconnected

Android samsung-SM-N910C_PT7533 got disconnected

Android HTC-HTC One_M8_PT9545 got disconnected

Android motorola-Nexus 6_PT8419 got re-connected event  ####################################################

Android motorola-Nexus 6_PT8419 got disconnected

Android samsung-SM-A500FU_PT7255 got disconnected

Android LGE-Nexus 5_PT256 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT2083 got disconnected

Android motorola-XT1039_PT5843 got disconnected

Android HTC-HTC Desire 820_PT1268 got re-connected event  ####################################################

Android LGE-Nexus 5_PT256 got disconnected

Android motorola-XT1039_PT5843 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT1268 got disconnected

Android LGE-Nexus 5_PT256 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT1268 got re-connected event  ####################################################

Android with samsung-SM-A300FU_PT3480 request took : 471238 ms. results peers[0], reConnects[0], sendData[17], time now: 771.33 sec.

Android HTC-HTC Desire 820_PT1268 got disconnected

Android LGE-Nexus 5_PT256 got disconnected

Android LGE-LG-H815_PT4879 got disconnected

Android samsung-SM-G900F_PT6801 got disconnected

Android motorola-Nexus 6_PT8419 got re-connected event  ####################################################

Android motorola-XT1072_PT7166 got re-connected event  ####################################################

Android motorola-Nexus 6_PT8419 got disconnected

Android LGE-Nexus 5_PT256 got re-connected event  ####################################################

Android motorola-XT1072_PT7166 got disconnected

Android motorola-Nexus 6_PT8419 got re-connected event  ####################################################

Android LGE-Nexus 5_PT256 got disconnected

Android motorola-Nexus 6_PT8419 got disconnected

Android HTC-HTC Desire 820_PT2083 got re-connected event  ####################################################

Android motorola-XT1039_PT5843 got re-connected event  ####################################################

Android motorola-XT1039_PT5843 got disconnected

Android with samsung-SM-N9005_PT1397 request took : 1155988 ms. results peers[0], reConnects[0], sendData[17], time now: 1456.079 sec.

Android motorola-XT1039_PT5843 got re-connected event  ####################################################

Android LGE-LG-D722_PT9856 got disconnected

Android LGE-Nexus 5_PT6584 got disconnected

Android HTC-HTC Desire 820_PT2083 got disconnected

Android HTC-HTC Desire 820_PT1268 got disconnected

Android samsung-SM-A300FU_PT3480 got disconnected

Android HUAWEI-ALE-L21_PT4378 got disconnected

Android motorola-XT1039_PT5843 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m


android : Error: Command failed: COPY_LOGS timeout reached
Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!COPY_LOGS timeout reached

```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/513350285301d5d_Work_in_progress__vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali06


Couldn't parse the device logs for thali06
````SyntaxError: Unexpected end of input```
####Node name: thali08


Couldn't parse the device logs for thali08
````SyntaxError: Unexpected end of input```



#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":18}}
Start Android tests : performance tests, start tests with timer

Test[0]: testSendData.js, timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}
Start iOs tests : performance tests, start tests with timer
Test[0]: testSendData.js, timeout : 1600000, data : {"timeout":"1500000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}

listening on *:3000

Android  LGE-Nexus 5_PT256 added : 0.501 sec., device count 1

Android  LGE-LG-D855_PT3840 added : 0.516 sec., device count 2

Android  samsung-SM-N9005_PT1397 added : 0.553 sec., device count 3

Android  samsung-SM-A300FU_PT3480 added : 0.75 sec., device count 4

Android  motorola-Nexus 6_PT8419 added : 1.304 sec., device count 5

Android  HTC-HTC Desire 820_PT1268 added : 1.359 sec., device count 6

Android  samsung-SM-G900F_PT6801 added : 1.68 sec., device count 7

iOs  Apple-Iphone6-1_PT1072 added : 1.685 sec., device count 1

Android  LGE-LG-H815_PT4879 added : 1.866 sec., device count 8

Android  LGE-LG-D722_PT9856 added : 2.86 sec., device count 9

Android  HTC-HTC One_M8_PT9545 added : 3.654 sec., device count 10

Android  LGE-Nexus 5_PT6584 added : 4.256 sec., device count 11

iOs  Apple-IpadAir2-1_PT9009 added : 4.272 sec., device count 2

Android  HTC-HTC Desire 820_PT2083 added : 4.432 sec., device count 12

iOs  Apple-Iphone5s-1_PT4752 added : 4.645 sec., device count 3

Android  motorola-XT1072_PT7166 added : 4.968 sec., device count 13

Android  HUAWEI-ALE-L21_PT4378 added : 5.171 sec., device count 14

Android  samsung-SM-N910C_PT7533 added : 5.205 sec., device count 15

Android  samsung-SM-A500FU_PT7255 added : 5.208 sec., device count 16

Android  samsung-SM-G800F_PT230 added : 5.307 sec., device count 17

Android  motorola-XT1039_PT5843 added : 5.445 sec., device count 18

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 18 devices, time now: 300.078 sec.

start test[0] with 18 devices.

-----iOs start testing now with 3 devices, time now: 300.106 sec.

start test[0] with 3 devices.

iOs with Apple-Iphone5s-1_PT4752 request took : 17899 ms. results peers[0], reConnects[0], sendData[2], time now: 318.007 sec.

iOs with Apple-Iphone6-1_PT1072 request took : 18466 ms. results peers[0], reConnects[0], sendData[2], time now: 318.573 sec.

iOs with Apple-IpadAir2-1_PT9009 request took : 18482 ms. results peers[0], reConnects[0], sendData[2], time now: 318.59 sec.

------------------------------------------------------
iOs test[ 0] done now. , time now: 318.591 sec.

iOs All tests are done, preparing test report. , time now: 318.597 sec.

--------------- test report ---------------------

--------------- Apple-Iphone6-1_PT1072 --------------------- : 1

sendList : 100% : 9143 ms, 99% : 9143 ms, 95 : 9143 ms, 90% : 9143 ms.

Result count 2, range 8431 ms to  9143 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT9009 --------------------- : 2

sendList : 100% : 8788 ms, 99% : 8788 ms, 95 : 8788 ms, 90% : 8788 ms.

Result count 2, range 8391 ms to  8788 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Apple-Iphone5s-1_PT4752 --------------------- : 3

sendList : 100% : 8368 ms, 99% : 8368 ms, 95 : 8368 ms, 90% : 8368 ms.
Result count 2, range 8359 ms to  8368 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- Combined ---------------------
sendList : 100% : 9143 ms, 99% : 9143 ms, 95 : 9143 ms, 90% : 8788 ms.

--------------- end of test report ---------------------

Android HTC-HTC One_M8_PT9545 got re-connected event  ####################################################

Android LGE-Nexus 5_PT256 got disconnected

Android samsung-SM-N910C_PT7533 got disconnected

Android HTC-HTC One_M8_PT9545 got disconnected

Android motorola-Nexus 6_PT8419 got re-connected event  ####################################################

Android motorola-Nexus 6_PT8419 got disconnected

Android samsung-SM-A500FU_PT7255 got disconnected

Android LGE-Nexus 5_PT256 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT2083 got disconnected

Android motorola-XT1039_PT5843 got disconnected

Android HTC-HTC Desire 820_PT1268 got re-connected event  ####################################################

Android LGE-Nexus 5_PT256 got disconnected

Android motorola-XT1039_PT5843 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT1268 got disconnected

Android LGE-Nexus 5_PT256 got re-connected event  ####################################################

Android HTC-HTC Desire 820_PT1268 got re-connected event  ####################################################

Android with samsung-SM-A300FU_PT3480 request took : 471238 ms. results peers[0], reConnects[0], sendData[17], time now: 771.33 sec.

Android HTC-HTC Desire 820_PT1268 got disconnected

Android LGE-Nexus 5_PT256 got disconnected

Android LGE-LG-H815_PT4879 got disconnected

Android samsung-SM-G900F_PT6801 got disconnected

Android motorola-Nexus 6_PT8419 got re-connected event  ####################################################

Android motorola-XT1072_PT7166 got re-connected event  ####################################################

Android motorola-Nexus 6_PT8419 got disconnected

Android LGE-Nexus 5_PT256 got re-connected event  ####################################################

Android motorola-XT1072_PT7166 got disconnected

Android motorola-Nexus 6_PT8419 got re-connected event  ####################################################

Android LGE-Nexus 5_PT256 got disconnected

Android motorola-Nexus 6_PT8419 got disconnected

Android HTC-HTC Desire 820_PT2083 got re-connected event  ####################################################

Android motorola-XT1039_PT5843 got re-connected event  ####################################################

Android motorola-XT1039_PT5843 got disconnected

Android with samsung-SM-N9005_PT1397 request took : 1155988 ms. results peers[0], reConnects[0], sendData[17], time now: 1456.079 sec.

Android motorola-XT1039_PT5843 got re-connected event  ####################################################

Android LGE-LG-D722_PT9856 got disconnected

Android LGE-Nexus 5_PT6584 got disconnected

Android HTC-HTC Desire 820_PT2083 got disconnected

Android HTC-HTC Desire 820_PT1268 got disconnected

Android samsung-SM-A300FU_PT3480 got disconnected

Android HUAWEI-ALE-L21_PT4378 got disconnected

Android motorola-XT1039_PT5843 got disconnected


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


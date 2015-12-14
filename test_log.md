#### Test 50650278ec2c976 Logs

#### Test Server Logs
```
Error: Command failed: 

/home/pi/Test/server_50650278ec2c976/test/TestServer/PerfTestFramework.js:199
          console.log("server timeout for test: %s (%s)", test, );
                                                                ^

SyntaxError: Unexpected token )
    at Module._compile (module.js:565:25)
    at Object.Module._extensions..js (module.js:625:10)
    at Module.load (module.js:416:36)
    at Function.Module._load (module.js:380:12)
    at Module.require (module.js:451:17)
    at require (module.js:469:17)
    at Object.<anonymous> (/home/pi/Test/server_50650278ec2c976/test/TestServer/index.js:19:25)
    at Module._compile (module.js:595:26)
    at Object.Module._extensions..js (module.js:625:10)
    at Module.load (module.js:416:36)

IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":23}}

 
Run IS script aborted
 
One or more Android tests are failed.
 [0m


/home/pi/Test/server_50650278ec2c976/test/TestServer/PerfTestFramework.js:199
          console.log("server timeout for test: %s (%s)", test, );
                                                                ^

SyntaxError: Unexpected token )
    at Module._compile (module.js:565:25)
    at Object.Module._extensions..js (module.js:625:10)
    at Module.load (module.js:416:36)
    at Function.Module._load (module.js:380:12)
    at Module.require (module.js:451:17)
    at require (module.js:469:17)
    at Object.<anonymous> (/home/pi/Test/server_50650278ec2c976/test/TestServer/index.js:19:25)
    at Module._compile (module.js:595:26)
    at Object.Module._extensions..js (module.js:625:10)
    at Module.load (module.js:416:36)


```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###Android Logs
####Node name: thali01
Console output:
```
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:null 
child process exited with code null on device LGH8153b36be34 
Error! Unexpected exit on device W3D7N15428022572 app:com.test.thalitest code:null 
child process exited with code null on device W3D7N15428022572 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[HUAWEI-ALE-L21](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali01_HUAWEI-ALE-L21.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:null 
child process exited with code null on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:null 
child process exited with code null on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
Error: problem running Android apk(com.test.thalitest) on device motorola-XT1039 
 
Error! true 
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:null 
child process exited with code null on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:null 
child process exited with code null on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:null 
child process exited with code null on device ZX1C223JKW 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:null 
child process exited with code null on device 954a12ed 
Android task is completed. [FAILED]
```
[samsung-SM-N9005](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali05_samsung-SM-N9005.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:null 
child process exited with code null on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:null 
child process exited with code null on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/50650278ec2c976_Enable_UnitTest_tobybrad/iOS_server.md)





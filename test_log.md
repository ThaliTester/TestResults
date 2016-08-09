#### Test 79751015ccfe79c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-08-09T13:04:25.641Z - info: Require 3 ios devices

2016-08-09T13:04:25.661Z - info: Require 3 android devices

2016-08-09T13:04:25.720Z - info: listening on *:3000

2016-08-09T13:04:26.353Z - debug: Device presented: LGE-LG-D855 (a3bfe50e-7d43-4113-a294-099d22f22f27) - android 5.0

2016-08-09T13:04:27.310Z - debug: Device presented: LGE-LG-D855 (a3bfe50e-7d43-4113-a294-099d22f22f27) - android 5.0

2016-08-09T13:04:27.316Z - info: Updating existing device: LGE-LG-D855 (a3bfe50e-7d43-4113-a294-099d22f22f27)

2016-08-09T13:04:30.028Z - debug: Device presented: LGE-LG-D722 (2c0a0bfe-7f28-4779-b178-3ea1069533e0) - android 5.0.2

2016-08-09T13:04:30.954Z - debug: Device presented: LGE-LG-D722 (2c0a0bfe-7f28-4779-b178-3ea1069533e0) - android 5.0.2

2016-08-09T13:04:30.955Z - info: Updating existing device: LGE-LG-D722 (2c0a0bfe-7f28-4779-b178-3ea1069533e0)

2016-08-09T13:05:13.734Z - debug: Device presented: samsung-SM-G900F (ed82b351-e24a-48ad-9442-0d631e7948d1) - android 6.0.1

2016-08-09T13:24:28.501Z - info: Socket to device LGE-LG-D722 disconnected: transport close

2016-08-09T13:24:30.467Z - info: Socket to device LGE-LG-D855 disconnected: transport close

2016-08-09T13:28:12.832Z - info: Socket to device samsung-SM-G900F disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
9/8/2016@14:58:23 Getting the list of iOS devices 
9/8/2016@14:58:24 Deploying iOS test app 
9/8/2016@14:58:24 uninstalling the application 
9/8/2016@14:58:25 installing the application 
9/8/2016@14:58:57 ios: child process exited with code 253 on device 17df3859480c382d3b761fa2643dde395ced1bd8 
9/8/2016@14:59:49 ios: child process exited with code 253 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
9/8/2016@14:59:53 ios: child process exited with code 253 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
9/8/2016@14:59:56 ios: child process exited with code 253 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/79751015ccfe79c_Check_811_failures_in_CI_do_not_merge__czyzm/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/79751015ccfe79c_Check_811_failures_in_CI_do_not_merge__czyzm/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/79751015ccfe79c_Check_811_failures_in_CI_do_not_merge__czyzm/iOS_Iphone5s-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/79751015ccfe79c_Check_811_failures_in_CI_do_not_merge__czyzm/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/79751015ccfe79c_Check_811_failures_in_CI_do_not_merge__czyzm/iOS_server.md)


###Android Logs
####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device LGD855a6933058 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD855a6933058 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/79751015ccfe79c_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D722.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/79751015ccfe79c_Check_811_failures_in_CI_do_not_merge__czyzm/thali05_LGE-LG-D855.md)

####Node name: thali08
Console output:
```

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.

Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/79751015ccfe79c_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_samsung-SM-G900F.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/79751015ccfe79c_Check_811_failures_in_CI_do_not_merge__czyzm/thali08_motorola-Nexus 6.md)





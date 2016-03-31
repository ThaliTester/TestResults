#### Test 646138038d447f5 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-31T07:43:50.429Z - info: listening on *:3000

2016-03-31T07:43:51.044Z - debug: Device presented: Apple-Iphone6-1 (ios) f113909a-fb4a-415f-bea2-168ce10b990b

2016-03-31T07:43:52.077Z - debug: Device presented: Apple-Iphone6-1 (ios) f113909a-fb4a-415f-bea2-168ce10b990b

2016-03-31T07:43:52.080Z - info: Updating existing device: Apple-Iphone6-1 (f113909a-fb4a-415f-bea2-168ce10b990b)

2016-03-31T07:43:52.612Z - debug: Device presented: LGE-LG-H815 (android) d88e576b-12c0-47eb-a14e-06a3cb07d2b4

2016-03-31T07:43:53.735Z - debug: Device presented: LGE-LG-H815 (android) d88e576b-12c0-47eb-a14e-06a3cb07d2b4

2016-03-31T07:43:53.737Z - info: Updating existing device: LGE-LG-H815 (d88e576b-12c0-47eb-a14e-06a3cb07d2b4)

2016-03-31T07:43:55.555Z - debug: Device presented: Apple-Iphone5s-1 (ios) 5c175efe-94ca-4587-a5bb-1640b10776a2

2016-03-31T07:43:55.577Z - debug: Device presented: Apple-Iphone5-1 (ios) 16a6402e-41c5-4742-9879-fc1d1acf46dc

2016-03-31T07:43:56.641Z - debug: Device presented: Apple-Iphone5s-1 (ios) 5c175efe-94ca-4587-a5bb-1640b10776a2

2016-03-31T07:43:56.642Z - info: Updating existing device: Apple-Iphone5s-1 (5c175efe-94ca-4587-a5bb-1640b10776a2)

2016-03-31T07:43:56.725Z - debug: Device presented: Apple-Iphone5-1 (ios) 16a6402e-41c5-4742-9879-fc1d1acf46dc

2016-03-31T07:43:56.726Z - info: Updating existing device: Apple-Iphone5-1 (16a6402e-41c5-4742-9879-fc1d1acf46dc)

2016-03-31T07:43:58.826Z - debug: Device presented: samsung-SM-N910C (android) 82bc767f-647f-4b5e-a123-5151b1956769

2016-03-31T07:44:04.628Z - debug: Device presented: motorola-Nexus 6 (android) c3713fc3-7ba0-422c-a0b5-d3a36478d2a4

2016-03-31T08:03:21.936Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-03-31T08:03:21.959Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-03-31T08:03:21.967Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-03-31T08:04:58.557Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-03-31T08:07:17.477Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-03-31T08:07:19.275Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/646138038d447f5_Test_framework_improvements_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/646138038d447f5_Test_framework_improvements_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/646138038d447f5_Test_framework_improvements_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/646138038d447f5_Test_framework_improvements_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/646138038d447f5_Test_framework_improvements_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali07
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/646138038d447f5_Test_framework_improvements_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/646138038d447f5_Test_framework_improvements_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/646138038d447f5_Test_framework_improvements_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/646138038d447f5_Test_framework_improvements_vjrantal/thali08_motorola-Nexus 6.md)





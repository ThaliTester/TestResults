#### Test 113351851fe156cf Logs

#### Test Server Logs
```
[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
11/7/2017@12:19:09 Getting the list of iOS devices 
11/7/2017@12:19:10 ios: device name: Thali56 , device identifier:  8effff55cdeae82604a08043752b940f94063299
11/7/2017@12:19:10 ios: device name: Thali55 , device identifier:  d7a40d176e510e468af45ed03d4ca45fd18dbe43
11/7/2017@12:19:10 ios: device name: Thali54 , device identifier:  5f598c405d20d04b836dd4c89356e94737c1c2d2
11/7/2017@12:19:10 Deploying iOS test app 
11/7/2017@12:19:10 uninstalling the application 
11/7/2017@12:19:10 installing the application 
11/7/2017@12:19:48 ios: child process exited with code 253 on device 8effff55cdeae82604a08043752b940f94063299 
11/7/2017@12:19:50 ios: child process exited with code 253 on device d7a40d176e510e468af45ed03d4ca45fd18dbe43 
11/7/2017@12:19:51 ios: child process exited with code 253 on device 5f598c405d20d04b836dd4c89356e94737c1c2d2 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Thali56](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_Thali56.md)

[Thali55](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_Thali55.md)

[Thali54](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_Thali54.md)

[server](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Error: No Android device found. 
```
####Node name: thali03
Console output:
```
Error: No Android device found. 
```
####Node name: thali04
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce061606e320561102

Starting application ThaliTest on ce061606c181d71003

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce061606e320561102

App was succesfully started on ce0616068b9f212302

App was succesfully started on ce061606c181d71003

STOP log received from ce061606e320561102
Test has SUCCEED

Device test finished on ce061606e320561102 
STOP log received from ce061606c181d71003
Test has SUCCEED

Device test finished on ce061606c181d71003 
STOP log received from ce0616068b9f212302
Test has SUCCEED

Device test finished on ce0616068b9f212302 
Android task is completed. [SUCCESS]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





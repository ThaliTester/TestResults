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
11/7/2017@09:47:34 Getting the list of iOS devices 
11/7/2017@09:47:35 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
11/7/2017@09:47:35 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
11/7/2017@09:47:35 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
11/7/2017@09:47:35 Deploying iOS test app 
11/7/2017@09:47:35 uninstalling the application 
11/7/2017@09:47:35 installing the application 
11/7/2017@09:49:48 ios: child process exited with code 253 on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
11/7/2017@09:50:02 ios: child process exited with code 253 on device bffa901fefdea07f59339a6737776943349f5077 
11/7/2017@09:50:04 ios: child process exited with code 253 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

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

App was succesfully started on ce0616068b9f212302

App was succesfully started on ce061606c181d71003

App was succesfully started on ce061606e320561102

STOP log received from ce0616068b9f212302
Test has SUCCEED

Device test finished on ce0616068b9f212302 
STOP log received from ce061606e320561102
Test has SUCCEED

Device test finished on ce061606e320561102 
STOP log received from ce061606c181d71003
Test has SUCCEED

Device test finished on ce061606c181d71003 
Android task is completed. [SUCCESS]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/thali04_samsung-SM-G935F.md)

[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/113351851fe156cf_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





#### Test 11335185196ab692 Logs

#### Test Server Logs
```
[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
12/7/2017@16:24:34 Getting the list of iOS devices 
12/7/2017@16:24:35 ios: device name: Iphone6s-1 , device identifier:  215bdffeb3a34d2191f54b854f090ea15ebcd35c
12/7/2017@16:24:35 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
12/7/2017@16:24:35 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
12/7/2017@16:24:35 Deploying iOS test app 
12/7/2017@16:24:35 uninstalling the application 
12/7/2017@16:24:35 Error: uninstalling app from device. { [Error: Command failed: Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /usr/local/lib/node_modules/.staging/ios-deploy-298c9491/src/ios-deploy/ios-deploy.m, line 1509.
] killed: false, code: null, signal: 'SIGABRT' } [....] Waiting for iOS device to be connected
[....] Using iPhone 6s 'Iphone6s-1' (215bdffeb3a34d2191f54b854f090ea15ebcd35c).
------ Uninstall phase ------
 Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /usr/local/lib/node_modules/.staging/ios-deploy-298c9491/src/ios-deploy/ios-deploy.m, line 1509.
 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[server](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has SUCCEED

Device test finished on ce061606e320561102 
Android task is completed. [SUCCESS]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/thali01_samsung-SM-G935F.md)

####Node name: thali03
Console output:
```
Error: No Android device found. 
```
####Node name: thali04
Console output:
```
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce061606c181d71003

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce061606c181d71003

App was succesfully started on ce0616068b9f212302

STOP log received from ce061606c181d71003
Test has SUCCEED

Device test finished on ce061606c181d71003 
STOP log received from ce0616068b9f212302
Test has SUCCEED

Device test finished on ce0616068b9f212302 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)





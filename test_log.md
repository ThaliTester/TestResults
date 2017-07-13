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
13/7/2017@08:29:22 Getting the list of iOS devices 
13/7/2017@08:29:23 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
13/7/2017@08:29:23 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
13/7/2017@08:29:23 ios: device name: Iphone6s-1 , device identifier:  215bdffeb3a34d2191f54b854f090ea15ebcd35c
13/7/2017@08:29:23 Deploying iOS test app 
13/7/2017@08:29:23 uninstalling the application 
13/7/2017@08:29:23 Error: uninstalling app from device. { [Error: Command failed: Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /usr/local/lib/node_modules/.staging/ios-deploy-298c9491/src/ios-deploy/ios-deploy.m, line 1509.
] killed: false, code: null, signal: 'SIGABRT' } [....] Waiting for iOS device to be connected
Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
[....] Using iPhone 6s 'Iphone6s-1' (215bdffeb3a34d2191f54b854f090ea15ebcd35c).
------ Uninstall phase ------
 Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /usr/local/lib/node_modules/.staging/ios-deploy-298c9491/src/ios-deploy/ios-deploy.m, line 1509.
 
true


android : No Error
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
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

Starting application ThaliTest on ce061606c181d71003

App was succesfully started on ce061606c181d71003

STOP log received from ce061606c181d71003
Test has SUCCEED

Device test finished on ce061606c181d71003 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/thali03_samsung-SM-G930F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

STOP log received from ce0616068b9f212302
Test has SUCCEED

Device test finished on ce0616068b9f212302 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/11335185196ab692_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)



#### Test 11335185196ab692_iOS_server Logs


```
Error: Command failed: Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /usr/local/lib/node_modules/.staging/ios-deploy-298c9491/src/ios-deploy/ios-deploy.m, line 1509.


[....] Waiting for iOS device to be connected
Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
[....] Using iPhone 6s 'Iphone6s-1' (215bdffeb3a34d2191f54b854f090ea15ebcd35c).
------ Uninstall phase ------
Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /usr/local/lib/node_modules/.staging/ios-deploy-298c9491/src/ios-deploy/ios-deploy.m, line 1509.


**Call Log**  
ios-deploy -t 0 -9 -1 com.thaliproject.thalitest -i 00b2e2c1b30013159b62125fe7f097bdcc055c10
ios-deploy -t 0 -9 -1 com.thaliproject.thalitest -i bffa901fefdea07f59339a6737776943349f5077
ios-deploy -t 0 -9 -1 com.thaliproject.thalitest -i 215bdffeb3a34d2191f54b854f090ea15ebcd35c

```

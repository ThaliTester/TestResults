#### Test 104320879c47ddeb_iOS_server Logs


```
Error: Command failed: Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /usr/local/lib/node_modules/.staging/ios-deploy-298c9491/src/ios-deploy/ios-deploy.m, line 1509.


[....] Waiting for iOS device to be connected
[....] Using iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
------ Uninstall phase ------
Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /usr/local/lib/node_modules/.staging/ios-deploy-298c9491/src/ios-deploy/ios-deploy.m, line 1509.


**Call Log**  
ios-deploy -t 0 -9 -1 com.test.thalitest -i 7ed231f0829a4ace34162e6c18308bcd995bc25a
ios-deploy -t 0 -9 -1 com.test.thalitest -i 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
ios-deploy -t 0 -9 -1 com.test.thalitest -i bffa901fefdea07f59339a6737776943349f5077
ios-deploy -t 0 -9 -1 com.test.thalitest -i 83aab4e7f1dde3becec287ac4c44362439d2595b
ios-deploy -t 0 -9 -1 com.test.thalitest -i 00b2e2c1b30013159b62125fe7f097bdcc055c10

```

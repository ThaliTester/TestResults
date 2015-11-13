#### Test 5065027881baad9 Logs

Status: 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
Error: uninstalling app from device. { [Error: Command failed: Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /testMoz/lib/node_modules/ios-deploy/src/ios-deploy.c, line 1553.
] killed: false, code: null, signal: 'SIGABRT' } [....] Waiting for iOS device to be connected
Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
[....] Using (17df3859480c382d3b761fa2643dde395ced1bd8ss).
------ Uninstall phase ------
 Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /testMoz/lib/node_modules/ios-deploy/src/ios-deploy.c, line 1553.
 
true


server : 
 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```
###iOS Logs

```
server: 
Error: Command failed: Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /testMoz/lib/node_modules/ios-deploy/src/ios-deploy.c, line 1553.


[....] Waiting for iOS device to be connected
Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
[....] Using (17df3859480c382d3b761fa2643dde395ced1bd8ss).
------ Uninstall phase ------
Assertion failed: (AMDeviceIsPaired(device)), function uninstall_app, file /testMoz/lib/node_modules/ios-deploy/src/ios-deploy.c, line 1553.


**Call Log**  
ios-deploy -t 0 -9 -1 com.test.thalitest -i 00b2e2c1b30013159b62125fe7f097bdcc055c10
ios-deploy -t 0 -9 -1 com.test.thalitest -i 17df3859480c382d3b761fa2643dde395ced1bd8
ios-deploy -t 0 -9 -1 com.test.thalitest -i 2a65f58f9902a701b5c9a55b2befb18672927474
ios-deploy -t 0 -9 -1 com.test.thalitest -i 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe



```



#### Integration Server Logs
```

 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```


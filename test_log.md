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
11/7/2017@14:14:48 Getting the list of iOS devices 
11/7/2017@14:14:49 ios: device name: Thali56 , device identifier:  8effff55cdeae82604a08043752b940f94063299
11/7/2017@14:14:49 ios: device name: Thali55 , device identifier:  d7a40d176e510e468af45ed03d4ca45fd18dbe43
11/7/2017@14:14:49 ios: device name: Thali54 , device identifier:  5f598c405d20d04b836dd4c89356e94737c1c2d2
11/7/2017@14:14:49 Deploying iOS test app 
11/7/2017@14:14:49 uninstalling the application 
11/7/2017@14:14:49 installing the application 
11/7/2017@14:15:31 ios: child process exited with code 253 on device 8effff55cdeae82604a08043752b940f94063299 
11/7/2017@14:15:32 ios: child process exited with code 253 on device d7a40d176e510e468af45ed03d4ca45fd18dbe43 
11/7/2017@14:15:32 ios: child process exited with code 253 on device 5f598c405d20d04b836dd4c89356e94737c1c2d2 
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
Stopping app on  ce051605cd40422604
Uninstalling app on  ce051605cd40422604
Stopping app on  ce061606c181d71003
Uninstalling app on  ce061606c181d71003
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce051605cd40422604
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce051605cd40422604
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce051605cd40422604
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.


Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.
 Error: problem deploying Android apk(/home/pi/test/builder/builds/113351851fe156cf/build_android/android_0_113351851fe156cf.apk) to device ce051605cd40422604
Error: Command failed: protocol failure
- waiting for device -

```




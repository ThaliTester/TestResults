#### Test 112761991d9ed552 Logs

#### Test Server Logs
```
Enter ____.js
Targets defined
http required
Creating internal server
Got request
URL:  [ 'ios', '3' ]
Enter checkIt
Got request
URL:  [ 'nodes', '2' ]
Got request
URL:  [ 'cancel', '1' ]
Got request
URL:  [ 'cancel', '1' ]
Enter checkIt
[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : No Error

ios : false
```


###Android Logs
####Node name: thali03
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.


Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.
 Error: problem deploying Android apk(/home/pi/test/builder/builds/112761991d9ed552/build_android/android_0_112761991d9ed552.apk) to device ce061606e320561102
```
####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.


Test on this node has failed but the reason wasn't the test application itself.
 Cancelling the test result on this node.
 Error: problem deploying Android apk(/home/pi/test/builder/builds/112761991d9ed552/build_android/android_0_112761991d9ed552.apk) to device ce0616068b9f212302
```

###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/112761991d9ed552_Add_sinon_s_sandboxing_functionality_to_the_test_framework__1347_opetkevich/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/112761991d9ed552_Add_sinon_s_sandboxing_functionality_to_the_test_framework__1347_opetkevich/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/112761991d9ed552_Add_sinon_s_sandboxing_functionality_to_the_test_framework__1347_opetkevich/iOS_ipad-air-2-1.md)



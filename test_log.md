#### Test 1133518519d655d1 Logs

#### Test Server Logs
```
Enter ____.js
Targets defined
http required
Creating internal server
Got request
URL:  [ 'nodes', '3' ]
Got request
URL:  [ 'ios', '3' ]
Enter checkIt
Got request
URL:  [ 'droid', '1' ]
Got request
URL:  [ 'droid', '1' ]
[0;31merror: command 'sudo jx ______.js all' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : false

android : Error: Command failed: job.nodes [ { name: 'thali03', ip: '192.168.1.52' },
  { name: 'thali01', ip: '192.168.1.50' },
  { name: 'thali04', ip: '192.168.1.53' } ]
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk pi@192.168.1.52:~/test/builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk pi@192.168.1.50:~/test/builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk pi@192.168.1.53:~/test/builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk
copyCmd scp pi@192.168.1.52:~/*.json /Users/thali/Github/CI/tasker/results/1133518519d655d1/thali03/
copyCmd scp pi@192.168.1.50:~/*.json /Users/thali/Github/CI/tasker/results/1133518519d655d1/thali01/
copyCmd scp pi@192.168.1.53:~/*.json /Users/thali/Github/CI/tasker/results/1133518519d655d1/thali04/
Error: Command failed: Android testing process has failed
 [0m

job.nodes [ { name: 'thali03', ip: '192.168.1.52' },
  { name: 'thali01', ip: '192.168.1.50' },
  { name: 'thali04', ip: '192.168.1.53' } ]
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk pi@192.168.1.52:~/test/builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk pi@192.168.1.50:~/test/builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk
copyCmd cd /Users/thali/Github/CI/tasker;scp ../builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk pi@192.168.1.53:~/test/builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk
copyCmd scp pi@192.168.1.52:~/*.json /Users/thali/Github/CI/tasker/results/1133518519d655d1/thali03/
copyCmd scp pi@192.168.1.50:~/*.json /Users/thali/Github/CI/tasker/results/1133518519d655d1/thali01/
copyCmd scp pi@192.168.1.53:~/*.json /Users/thali/Github/CI/tasker/results/1133518519d655d1/thali04/

```
###Android Logs
####Node name: thali01
Console output:
```
Error: No Android device found. 
```
####Node name: thali03
Console output:
```
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606e320561102 install -r /home/pi/test/builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk&& adb -s ce061606e320561102 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce061606e320561102 install -r /home/pi/test/builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk&& adb -s ce061606e320561102 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce061606e320561102

Starting application ThaliTest on ce061606e320561102

App was succesfully started on ce061606e320561102

STOP log received from ce061606e320561102
Test has SUCCEED

Device test finished on ce061606e320561102 
Android task is completed. [SUCCESS]
```
[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/1133518519d655d1_CI_sanity_check_jareksl/thali03_samsung-SM-G935F.md)

####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce0616068b9f212302 install -r /home/pi/test/builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk&& adb -s ce0616068b9f212302 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
deploy command: adb -s ce0616068b9f212302 install -r /home/pi/test/builder/builds/1133518519d655d1/build_android/android_0_1133518519d655d1.apk&& adb -s ce0616068b9f212302 shell pm grant com.rockwellautomation.thalitest android.permission.ACCESS_COARSE_LOCATION
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

STOP log received from ce0616068b9f212302
Test has SUCCEED

Device test finished on ce0616068b9f212302 
Android task is completed. [SUCCESS]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/1133518519d655d1_CI_sanity_check_jareksl/thali04_samsung-SM-G930F.md)




###iOS Logs
[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/1133518519d655d1_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/1133518519d655d1_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/1133518519d655d1_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)



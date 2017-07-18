#### Test 130589065a18bb20 Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 0 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_130589065a18bb20/serverApp/index.js',
  '{"devices":{"android":3}}' ]

JSON { devices: { android: 3 } }

[0;31merror: command 'sudo jx ______.js android' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 0 ]

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali01
Console output:
```
Stopping app on  ce061606e320561102
Stopping App:com.example.hello ce061606e320561102 green
Uninstalling app on  ce061606e320561102
Uninstalling App:com.example.hello ce061606e320561102 green
is Device booted ce061606e320561102 0 green
Checking:  adb -s ce061606e320561102 shell getprop sys.boot_completed green
is Device booted ce061606e320561102 10000 green
Checking:  adb -s ce061606e320561102 shell getprop sys.boot_completed green

All devices are ready!

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

```
####Node name: thali03
Console output:
```
Stopping app on  ce061606c181d71003
Stopping App:com.example.hello ce061606c181d71003 green
Uninstalling app on  ce061606c181d71003
Uninstalling App:com.example.hello ce061606c181d71003 green
is Device booted ce061606c181d71003 0 green
Checking:  adb -s ce061606c181d71003 shell getprop sys.boot_completed green
is Device booted ce061606c181d71003 10000 green
Checking:  adb -s ce061606c181d71003 shell getprop sys.boot_completed green
is Device booted ce061606c181d71003 10000 green
Checking:  adb -s ce061606c181d71003 shell getprop sys.boot_completed green

All devices are ready!

Deploying to ce061606c181d71003
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606c181d71003

```
####Node name: thali04
Console output:
```
Stopping app on  ce0616068b9f212302
Stopping App:com.example.hello ce0616068b9f212302 green
Uninstalling app on  ce0616068b9f212302
Uninstalling App:com.example.hello ce0616068b9f212302 green
is Device booted ce0616068b9f212302 0 green
Checking:  adb -s ce0616068b9f212302 shell getprop sys.boot_completed green
is Device booted ce0616068b9f212302 10000 green
Checking:  adb -s ce0616068b9f212302 shell getprop sys.boot_completed green

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Starting application ThaliTest on ce0616068b9f212302

App was succesfully started on ce0616068b9f212302

Error! Unexpected exit on device ce0616068b9f212302 app:com.example.hello code:0 
Child process exited with code 0 on device ce0616068b9f212302
Android task is completed. [FAILED]
Stopping App:com.example.hello ce0616068b9f212302 green
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/130589065a18bb20_trigger_test_on_android_devices_jareksl/thali04_samsung-SM-G930F.md)





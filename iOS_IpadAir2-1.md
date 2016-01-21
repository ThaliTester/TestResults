#### Test 56672827039a409_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56672827039a409/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/C5ADA476-4338-4359-926E-54D1B75AF962/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C5ADA476-4338-4359-926E-54D1B75AF962/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56672827039a409/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56672827039a409/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F183D011-000D-4AC9-80CD-06436CF425BE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59860"
,(lldb)     command script import "/tmp/C5ADA476-4338-4359-926E-54D1B75AF962/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-21 18:13:24.114 ThaliTest[2518:5420207] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C80EC180-3473-4F8E-94DF-0CAE1A4209C2/Library/Cookies/Cookies.binarycookies
,2016-01-21 18:13:24.350 ThaliTest[2518:5420207] Apache Cordova native platform version 3.9.2 is starting.
2016-01-21 18:13:24.351 ThaliTest[2518:5420207] Multi-tasking -> Device: YES, App: YES
,2016-01-21 18:13:24.357 ThaliTest[2518:5420207] Unlimited access to network resources
,2016-01-21 18:13:24.363 ThaliTest[2518:5420207] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 18:13:28.560 ThaliTest[2518:5420207] Resetting plugins due to page load.
,2016-01-21 18:13:30.020 ThaliTest[2518:5420207] Finished load of: file:///var/mobile/Containers/Bundle/Application/F183D011-000D-4AC9-80CD-06436CF425BE/ThaliTest.app/www/index.html
,2016-01-21 18:13:30.151 ThaliTest[2518:5420207] JXcore Cordova plugin initializing
2016-01-21 18:13:30.152 ThaliTest[2518:5420382] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F183D011-000D-4AC9-80CD-06436CF425BE/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F183D011-000D-4AC9-80CD-06436CF425BE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F183D011-000D-4AC9-80CD-06436CF425BE/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F183D011-000D-4AC9-80CD-06436CF425BE/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F183D011-000D-4AC9-80CD-06436CF425BE/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F183D011-000D-4AC9-80CD-06436CF425BE/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F183D011-000D-4AC9-80CD-06436CF425BE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F183D011-000D-4AC9-80CD-06436CF425BE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data


```

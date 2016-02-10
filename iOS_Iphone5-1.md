#### Test 58752353dc32d9f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58752353dc32d9f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/CFF59C04-F44C-4AC1-A2B7-18267FC3593C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/CFF59C04-F44C-4AC1-A2B7-18267FC3593C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58752353dc32d9f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58752353dc32d9f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54302"
,(lldb)     command script import "/tmp/CFF59C04-F44C-4AC1-A2B7-18267FC3593C/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-10 15:09:26.071 ThaliTest[2957:8819635] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/69CB3D97-A810-44DF-9F6B-1503DA99A860/Library/Cookies/Cookies.binarycookies
,2016-02-10 15:09:26.187 ThaliTest[2957:8819635] Apache Cordova native platform version 4.0.1 is starting.
2016-02-10 15:09:26.188 ThaliTest[2957:8819635] Multi-tasking -> Device: YES, App: YES
,2016-02-10 15:09:26.206 ThaliTest[2957:8819635] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-10 15:09:28.300 ThaliTest[2957:8819635] Using UIWebView
,2016-02-10 15:09:28.306 ThaliTest[2957:8819635] [CDVTimer][handleopenurl] 0.539005ms
,2016-02-10 15:09:28.312 ThaliTest[2957:8819635] [CDVTimer][intentandnavigationfilter] 5.584002ms
2016-02-10 15:09:28.313 ThaliTest[2957:8819635] [CDVTimer][gesturehandler] 0.275016ms
2016-02-10 15:09:28.313 ThaliTest[2957:8819635] [CDVTimer][TotalPluginStartup] 7.479012ms
,2016-02-10 15:09:36.782 ThaliTest[2957:8819635] Resetting plugins due to page load.
,2016-02-10 15:09:40.972 ThaliTest[2957:8819635] Finished load of: file:///var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/index.html
,2016-02-10 15:09:41.188 ThaliTest[2957:8819635] JXcore Cordova plugin initializing
2016-02-10 15:09:41.190 ThaliTest[2957:8819966] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6F47B640-F82F-47F3-ABAC-58F72E969D65/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

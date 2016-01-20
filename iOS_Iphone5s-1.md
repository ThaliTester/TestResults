#### Test 564496606be5677_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/564496606be5677/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9E1A40FB-3A85-4881-AB4B-9984A4A93251/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9E1A40FB-3A85-4881-AB4B-9984A4A93251/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/564496606be5677/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/564496606be5677/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BBF9C927-6648-446E-B6AD-E76E1B185467/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59013"
,(lldb)     command script import "/tmp/9E1A40FB-3A85-4881-AB4B-9984A4A93251/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-20 12:15:03.778 ThaliTest[2325:5878680] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CF9D2D9F-5524-4ACA-AD3C-98F89EF79251/Library/Cookies/Cookies.binarycookies
,2016-01-20 12:15:04.091 ThaliTest[2325:5878680] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-20 12:15:04.092 ThaliTest[2325:5878680] Multi-tasking -> Device: YES, App: YES
,2016-01-20 12:15:04.100 ThaliTest[2325:5878680] Unlimited access to network resources
,2016-01-20 12:15:04.110 ThaliTest[2325:5878680] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-20 12:15:08.856 ThaliTest[2325:5878680] Resetting plugins due to page load.
,2016-01-20 12:15:10.528 ThaliTest[2325:5878680] Finished load of: file:///var/mobile/Containers/Bundle/Application/BBF9C927-6648-446E-B6AD-E76E1B185467/ThaliTest.app/www/index.html
,2016-01-20 12:15:10.780 ThaliTest[2325:5878680] JXcore Cordova plugin initializing
2016-01-20 12:15:10.780 ThaliTest[2325:5878861] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBF9C927-6648-446E-B6AD-E76E1B185467/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBF9C927-6648-446E-B6AD-E76E1B185467/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBF9C927-6648-446E-B6AD-E76E1B185467/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBF9C927-6648-446E-B6AD-E76E1B185467/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBF9C927-6648-446E-B6AD-E76E1B185467/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBF9C927-6648-446E-B6AD-E76E1B185467/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BBF9C927-6648-446E-B6AD-E76E1B185467/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

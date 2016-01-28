#### Test 573480789efee08_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/37D994DC-0042-4617-B087-4E2923FB6BE7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/37D994DC-0042-4617-B087-4E2923FB6BE7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5A19BEE4-99EA-4595-8331-E3E13CFC4053/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62130"
,(lldb)     command script import "/tmp/37D994DC-0042-4617-B087-4E2923FB6BE7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-28 12:45:48.612 ThaliTest[2776:7940927] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A7BBAACA-2E9C-41AC-B1B9-63D0C9365A6E/Library/Cookies/Cookies.binarycookies
,2016-01-28 12:45:48.908 ThaliTest[2776:7940927] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-28 12:45:48.909 ThaliTest[2776:7940927] Multi-tasking -> Device: YES, App: YES
,2016-01-28 12:45:48.916 ThaliTest[2776:7940927] Unlimited access to network resources
,2016-01-28 12:45:48.927 ThaliTest[2776:7940927] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-28 12:45:53.504 ThaliTest[2776:7940927] Resetting plugins due to page load.
,2016-01-28 12:45:54.983 ThaliTest[2776:7940927] Finished load of: file:///var/mobile/Containers/Bundle/Application/5A19BEE4-99EA-4595-8331-E3E13CFC4053/ThaliTest.app/www/index.html
,2016-01-28 12:45:55.191 ThaliTest[2776:7940927] JXcore Cordova plugin initializing
2016-01-28 12:45:55.192 ThaliTest[2776:7941213] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5A19BEE4-99EA-4595-8331-E3E13CFC4053/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5A19BEE4-99EA-4595-8331-E3E13CFC4053/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5A19BEE4-99EA-4595-8331-E3E13CFC4053/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5A19BEE4-99EA-4595-8331-E3E13CFC4053/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5A19BEE4-99EA-4595-8331-E3E13CFC4053/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5A19BEE4-99EA-4595-8331-E3E13CFC4053/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5A19BEE4-99EA-4595-8331-E3E13CFC4053/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5A19BEE4-99EA-4595-8331-E3E13CFC4053/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

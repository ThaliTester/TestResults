#### Test 568182548138a64_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/568182548138a64/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E3E87B31-3E94-44AF-AF54-A29522015F12/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E3E87B31-3E94-44AF-AF54-A29522015F12/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/568182548138a64/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/568182548138a64/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DBD12C73-A3F6-4A65-84A0-A1FF280936BB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60020"
,(lldb)     command script import "/tmp/E3E87B31-3E94-44AF-AF54-A29522015F12/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 23:38:12.555 ThaliTest[2534:5455586] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D0D7DBAE-7DBC-4693-9021-22898CFBACA9/Library/Cookies/Cookies.binarycookies
,2016-01-21 23:38:12.805 ThaliTest[2534:5455586] Apache Cordova native platform version 3.9.2 is starting.
2016-01-21 23:38:12.806 ThaliTest[2534:5455586] Multi-tasking -> Device: YES, App: YES
,2016-01-21 23:38:12.812 ThaliTest[2534:5455586] Unlimited access to network resources
,2016-01-21 23:38:12.818 ThaliTest[2534:5455586] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 23:38:17.124 ThaliTest[2534:5455586] Resetting plugins due to page load.
,2016-01-21 23:38:18.601 ThaliTest[2534:5455586] Finished load of: file:///var/mobile/Containers/Bundle/Application/DBD12C73-A3F6-4A65-84A0-A1FF280936BB/ThaliTest.app/www/index.html
,2016-01-21 23:38:18.740 ThaliTest[2534:5455586] JXcore Cordova plugin initializing
2016-01-21 23:38:18.740 ThaliTest[2534:5455754] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBD12C73-A3F6-4A65-84A0-A1FF280936BB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBD12C73-A3F6-4A65-84A0-A1FF280936BB/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBD12C73-A3F6-4A65-84A0-A1FF280936BB/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBD12C73-A3F6-4A65-84A0-A1FF280936BB/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBD12C73-A3F6-4A65-84A0-A1FF280936BB/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBD12C73-A3F6-4A65-84A0-A1FF280936BB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DBD12C73-A3F6-4A65-84A0-A1FF280936BB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

#### Test 573480789efee08_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/91770C39-D119-4A63-B71C-7349DC295356/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/91770C39-D119-4A63-B71C-7349DC295356/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/573480789efee08/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9E1099FB-9AA1-4DE8-9A42-26D3B7CB13BB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62117"
,(lldb)     command script import "/tmp/91770C39-D119-4A63-B71C-7349DC295356/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-28 12:44:47.607 ThaliTest[4075:6694986] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2B599B85-1B17-4A46-89C0-1011A55D113D/Library/Cookies/Cookies.binarycookies
,2016-01-28 12:44:47.863 ThaliTest[4075:6694986] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-28 12:44:47.864 ThaliTest[4075:6694986] Multi-tasking -> Device: YES, App: YES
,2016-01-28 12:44:47.870 ThaliTest[4075:6694986] Unlimited access to network resources
,2016-01-28 12:44:47.876 ThaliTest[4075:6694986] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-28 12:44:52.043 ThaliTest[4075:6694986] Resetting plugins due to page load.
,2016-01-28 12:44:53.529 ThaliTest[4075:6694986] Finished load of: file:///var/mobile/Containers/Bundle/Application/9E1099FB-9AA1-4DE8-9A42-26D3B7CB13BB/ThaliTest.app/www/index.html
,2016-01-28 12:44:53.676 ThaliTest[4075:6694986] JXcore Cordova plugin initializing
,2016-01-28 12:44:53.677 ThaliTest[4075:6695152] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9E1099FB-9AA1-4DE8-9A42-26D3B7CB13BB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9E1099FB-9AA1-4DE8-9A42-26D3B7CB13BB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9E1099FB-9AA1-4DE8-9A42-26D3B7CB13BB/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9E1099FB-9AA1-4DE8-9A42-26D3B7CB13BB/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9E1099FB-9AA1-4DE8-9A42-26D3B7CB13BB/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9E1099FB-9AA1-4DE8-9A42-26D3B7CB13BB/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9E1099FB-9AA1-4DE8-9A42-26D3B7CB13BB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9E1099FB-9AA1-4DE8-9A42-26D3B7CB13BB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

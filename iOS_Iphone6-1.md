#### Test 573480784751f5c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/573480784751f5c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BEB73B5E-D40C-49EB-B30B-B6C91CB4A1C9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BEB73B5E-D40C-49EB-B30B-B6C91CB4A1C9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/573480784751f5c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/573480784751f5c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0F8FDA78-6447-4973-BC1F-82B73D540595/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62264"
,(lldb)     command script import "/tmp/BEB73B5E-D40C-49EB-B30B-B6C91CB4A1C9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-28 13:51:29.004 ThaliTest[663:1129091] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/84B4F6E4-F13D-4F6A-B9B5-2A0BC5A4F0B3/Library/Cookies/Cookies.binarycookies
,2016-01-28 13:51:29.348 ThaliTest[663:1129091] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-28 13:51:29.349 ThaliTest[663:1129091] Multi-tasking -> Device: YES, App: YES
,2016-01-28 13:51:29.358 ThaliTest[663:1129091] Unlimited access to network resources
,2016-01-28 13:51:29.369 ThaliTest[663:1129091] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-28 13:51:37.821 ThaliTest[663:1129091] Resetting plugins due to page load.
,2016-01-28 13:51:41.121 ThaliTest[663:1129091] Finished load of: file:///var/mobile/Containers/Bundle/Application/0F8FDA78-6447-4973-BC1F-82B73D540595/ThaliTest.app/www/index.html
,2016-01-28 13:51:41.310 ThaliTest[663:1129091] JXcore Cordova plugin initializing
2016-01-28 13:51:41.311 ThaliTest[663:1129309] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F8FDA78-6447-4973-BC1F-82B73D540595/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F8FDA78-6447-4973-BC1F-82B73D540595/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F8FDA78-6447-4973-BC1F-82B73D540595/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F8FDA78-6447-4973-BC1F-82B73D540595/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F8FDA78-6447-4973-BC1F-82B73D540595/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F8FDA78-6447-4973-BC1F-82B73D540595/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F8FDA78-6447-4973-BC1F-82B73D540595/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F8FDA78-6447-4973-BC1F-82B73D540595/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded


```

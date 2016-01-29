#### Test 57659382b63fd0b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57659382b63fd0b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/329901F1-562D-4AB0-9BA6-86F3C9B9BA24/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/329901F1-562D-4AB0-9BA6-86F3C9B9BA24/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57659382b63fd0b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57659382b63fd0b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/369492A9-0ED0-4BB6-92D4-A7D5B8663D64/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62864"
,(lldb)     command script import "/tmp/329901F1-562D-4AB0-9BA6-86F3C9B9BA24/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 16:48:55.884 ThaliTest[2921:8258419] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B531FE22-4E67-4013-9C6C-900C6410B5D3/Library/Cookies/Cookies.binarycookies
,2016-01-29 16:48:56.147 ThaliTest[2921:8258419] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-29 16:48:56.149 ThaliTest[2921:8258419] Multi-tasking -> Device: YES, App: YES
,2016-01-29 16:48:56.156 ThaliTest[2921:8258419] Unlimited access to network resources
,2016-01-29 16:48:56.167 ThaliTest[2921:8258419] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 16:49:00.488 ThaliTest[2921:8258419] Resetting plugins due to page load.
,2016-01-29 16:49:02.129 ThaliTest[2921:8258419] Finished load of: file:///var/mobile/Containers/Bundle/Application/369492A9-0ED0-4BB6-92D4-A7D5B8663D64/ThaliTest.app/www/index.html
,2016-01-29 16:49:02.339 ThaliTest[2921:8258419] JXcore Cordova plugin initializing
2016-01-29 16:49:02.342 ThaliTest[2921:8258715] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369492A9-0ED0-4BB6-92D4-A7D5B8663D64/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369492A9-0ED0-4BB6-92D4-A7D5B8663D64/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369492A9-0ED0-4BB6-92D4-A7D5B8663D64/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369492A9-0ED0-4BB6-92D4-A7D5B8663D64/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369492A9-0ED0-4BB6-92D4-A7D5B8663D64/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369492A9-0ED0-4BB6-92D4-A7D5B8663D64/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369492A9-0ED0-4BB6-92D4-A7D5B8663D64/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/369492A9-0ED0-4BB6-92D4-A7D5B8663D64/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown


```

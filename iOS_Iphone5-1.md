#### Test 584164489c56086_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/584164489c56086/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8FE1B09C-6903-4A34-B133-1E5E0D0814E6/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/8FE1B09C-6903-4A34-B133-1E5E0D0814E6/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/584164489c56086/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/584164489c56086/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52708"
,(lldb)     command script import "/tmp/8FE1B09C-6903-4A34-B133-1E5E0D0814E6/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 10:17:54.161 ThaliTest[2809:8612005] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/507B9B5E-E38E-45A5-BF7D-45B1A23C63ED/Library/Cookies/Cookies.binarycookies
,2016-02-09 10:17:54.283 ThaliTest[2809:8612005] Apache Cordova native platform version 4.0.1 is starting.
,2016-02-09 10:17:54.285 ThaliTest[2809:8612005] Multi-tasking -> Device: YES, App: YES
,2016-02-09 10:17:54.308 ThaliTest[2809:8612005] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 10:17:56.279 ThaliTest[2809:8612005] Using UIWebView
,2016-02-09 10:17:56.283 ThaliTest[2809:8612005] [CDVTimer][handleopenurl] 0.254035ms
,2016-02-09 10:17:56.289 ThaliTest[2809:8612005] [CDVTimer][intentandnavigationfilter] 5.312979ms
2016-02-09 10:17:56.289 ThaliTest[2809:8612005] [CDVTimer][gesturehandler] 0.334024ms
2016-02-09 10:17:56.290 ThaliTest[2809:8612005] [CDVTimer][TotalPluginStartup] 6.902993ms
,2016-02-09 10:18:04.687 ThaliTest[2809:8612005] Resetting plugins due to page load.
,2016-02-09 10:18:08.483 ThaliTest[2809:8612005] Finished load of: file:///var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app/www/index.html
,2016-02-09 10:18:08.687 ThaliTest[2809:8612005] JXcore Cordova plugin initializing
,2016-02-09 10:18:08.689 ThaliTest[2809:8612229] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8C7B7C88-99CF-49B1-B823-6D965FAD8376/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded


```

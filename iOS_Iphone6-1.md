#### Test 5841644866d9c0e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5841644866d9c0e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/E6704676-3166-4370-B74E-2706A017F3F4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E6704676-3166-4370-B74E-2706A017F3F4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5841644866d9c0e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5841644866d9c0e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52886"
,(lldb)     command script import "/tmp/E6704676-3166-4370-B74E-2706A017F3F4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 13:08:14.984 ThaliTest[1611:2951507] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/29EB4D72-AF40-4032-9789-10E5F1CA0A93/Library/Cookies/Cookies.binarycookies
,2016-02-09 13:08:15.383 ThaliTest[1611:2951507] Apache Cordova native platform version 4.0.1 is starting.
,2016-02-09 13:08:15.384 ThaliTest[1611:2951507] Multi-tasking -> Device: YES, App: YES
,2016-02-09 13:08:15.410 ThaliTest[1611:2951507] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 13:08:17.442 ThaliTest[1611:2951507] Using UIWebView
,2016-02-09 13:08:17.449 ThaliTest[1611:2951507] [CDVTimer][handleopenurl] 0.554025ms
,2016-02-09 13:08:17.458 ThaliTest[1611:2951507] [CDVTimer][intentandnavigationfilter] 7.927001ms
2016-02-09 13:08:17.458 ThaliTest[1611:2951507] [CDVTimer][gesturehandler] 0.353992ms
2016-02-09 13:08:17.459 ThaliTest[1611:2951507] [CDVTimer][TotalPluginS,tartup] 10.500968ms
,2016-02-09 13:08:24.868 ThaliTest[1611:2951507] Resetting plugins due to page load.
,2016-02-09 13:08:28.237 ThaliTest[1611:2951507] Finished load of: file:///var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app/www/index.html
,2016-02-09 13:08:28.462 ThaliTest[1611:2951507] JXcore Cordova plugin initializing
2016-02-09 13:08:28.462 ThaliTest[1611:2951753] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A844D898-4996-4325-8AD3-C556F100E73D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded


```

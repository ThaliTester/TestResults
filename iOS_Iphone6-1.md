#### Test 568182548138a64_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/568182548138a64/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/99456C27-7E2F-49F8-9C9B-282DC019BFD9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/99456C27-7E2F-49F8-9C9B-282DC019BFD9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/568182548138a64/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/568182548138a64/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C0812A7B-C04C-4FC6-B779-1783E8778EDD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60022"
,(lldb)     command script import "/tmp/99456C27-7E2F-49F8-9C9B-282DC019BFD9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 23:38:42.892 ThaliTest[348:254536] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5725711D-087B-4DDB-BD91-EEB5EE64195D/Library/Cookies/Cookies.binarycookies
,2016-01-21 23:38:43.359 ThaliTest[348:254536] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-21 23:38:43.361 ThaliTest[348:254536] Multi-tasking -> Device: YES, App: YES
,2016-01-21 23:38:43.371 ThaliTest[348:254536] Unlimited access to network resources
,2016-01-21 23:38:43.385 ThaliTest[348:254536] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 23:38:53.621 ThaliTest[348:254536] Resetting plugins due to page load.
,2016-01-21 23:38:57.573 ThaliTest[348:254536] Finished load of: file:///var/mobile/Containers/Bundle/Application/C0812A7B-C04C-4FC6-B779-1783E8778EDD/ThaliTest.app/www/index.html
,2016-01-21 23:38:57.758 ThaliTest[348:254536] JXcore Cordova plugin initializing
2016-01-21 23:38:57.759 ThaliTest[348:254760] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0812A7B-C04C-4FC6-B779-1783E8778EDD/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0812A7B-C04C-4FC6-B779-1783E8778EDD/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0812A7B-C04C-4FC6-B779-1783E8778EDD/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0812A7B-C04C-4FC6-B779-1783E8778EDD/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0812A7B-C04C-4FC6-B779-1783E8778EDD/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0812A7B-C04C-4FC6-B779-1783E8778EDD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0812A7B-C04C-4FC6-B779-1783E8778EDD/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data


```

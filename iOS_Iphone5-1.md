#### Test 5615109370bee58_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5615109370bee58/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/49722864-275F-4D54-8EC3-FBEC95A3A49E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/49722864-275F-4D54-8EC3-FBEC95A3A49E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5615109370bee58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5615109370bee58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/995041C1-8B88-4F03-9059-EABBB1123814/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57884"
,(lldb)     command script import "/tmp/49722864-275F-4D54-8EC3-FBEC95A3A49E/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-18 15:14:03.259 ThaliTest[1588:5082901] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2F422E6D-94E2-4FC7-B7E7-C7F5788C44B4/Library/Cookies/Cookies.binarycookies
,2016-01-18 15:14:03.590 ThaliTest[1588:5082901] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-18 15:14:03.591 ThaliTest[1588:5082901] Multi-tasking -> Device: YES, App: YES
,2016-01-18 15:14:03.596 ThaliTest[1588:5082901] Unlimited access to network resources
,2016-01-18 15:14:03.608 ThaliTest[1588:5082901] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-18 15:14:09.692 ThaliTest[1588:5082901] Resetting plugins due to page load.
,2016-01-18 15:14:11.630 ThaliTest[1588:5082901] Finished load of: file:///var/mobile/Containers/Bundle/Application/995041C1-8B88-4F03-9059-EABBB1123814/ThaliTest.app/www/index.html
,2016-01-18 15:14:11.830 ThaliTest[1588:5082901] JXcore Cordova plugin initializing
,2016-01-18 15:14:11.836 ThaliTest[1588:5083019] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/995041C1-8B88-4F03-9059-EABBB1123814/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/995041C1-8B88-4F03-9059-EABBB1123814/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/995041C1-8B88-4F03-9059-EABBB1123814/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/995041C1-8B88-4F03-9059-EABBB1123814/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/995041C1-8B88-4F03-9059-EABBB1123814/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/995041C1-8B88-4F03-9059-EABBB1123814/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/995041C1-8B88-4F03-9059-EABBB1123814/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test app app.js loaded
,--= Surplus to requirements =--
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

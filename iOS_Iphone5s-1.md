#### Test 5615109389cecbd_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5615109389cecbd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B41C81D1-544E-46D2-AB35-2C3D145FE857/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B41C81D1-544E-46D2-AB35-2C3D145FE857/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5615109389cecbd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5615109389cecbd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6FBF8272-65FF-412E-A0E8-DED2BEF39242/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56896"
,(lldb)     command script import "/tmp/B41C81D1-544E-46D2-AB35-2C3D145FE857/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-17 10:44:39.055 ThaliTest[2071:5087528] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7B4A64B0-DE26-44B2-826D-A37BFAE62EC1/Library/Cookies/Cookies.binarycookies
,2016-01-17 10:44:39.345 ThaliTest[2071:5087528] Apache Cordova native platform version 3.9.2 is starting.
2016-01-17 10:44:39.346 ThaliTest[2071:5087528] Multi-tasking -> Device: YES, App: YES
,2016-01-17 10:44:39.353 ThaliTest[2071:5087528] Unlimited access to network resources
,2016-01-17 10:44:39.361 ThaliTest[2071:5087528] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-17 10:44:43.683 ThaliTest[2071:5087528] Resetting plugins due to page load.
,2016-01-17 10:44:45.240 ThaliTest[2071:5087528] Finished load of: file:///var/mobile/Containers/Bundle/Application/6FBF8272-65FF-412E-A0E8-DED2BEF39242/ThaliTest.app/www/index.html
,2016-01-17 10:44:45.423 ThaliTest[2071:5087528] JXcore Cordova plugin initializing
,2016-01-17 10:44:45.424 ThaliTest[2071:5087675] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FBF8272-65FF-412E-A0E8-DED2BEF39242/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FBF8272-65FF-412E-A0E8-DED2BEF39242/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FBF8272-65FF-412E-A0E8-DED2BEF39242/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FBF8272-65FF-412E-A0E8-DED2BEF39242/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FBF8272-65FF-412E-A0E8-DED2BEF39242/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FBF8272-65FF-412E-A0E8-DED2BEF39242/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FBF8272-65FF-412E-A0E8-DED2BEF39242/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test app app.js loaded
,TAP version 13
,# setup
,# multiplex can send data

```

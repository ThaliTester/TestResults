#### Test 56449660311ec66_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56449660311ec66/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/324B52EE-4717-442C-8F2F-FA4317C554AF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/324B52EE-4717-442C-8F2F-FA4317C554AF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56449660311ec66/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56449660311ec66/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D78B418C-EF28-4ABF-957A-839432EF303F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59281"
,(lldb)     command script import "/tmp/324B52EE-4717-442C-8F2F-FA4317C554AF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 10:16:34.979 ThaliTest[286:180110] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C38B6FF2-95CD-4E69-89AC-E1FD32DA6B77/Library/Cookies/Cookies.binarycookies
,2016-01-21 10:16:35.425 ThaliTest[286:180110] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-21 10:16:35.426 ThaliTest[286:180110] Multi-tasking -> Device: YES, App: YES
,2016-01-21 10:16:35.436 ThaliTest[286:180110] Unlimited access to network resources
,2016-01-21 10:16:35.451 ThaliTest[286:180110] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 10:16:42.961 ThaliTest[286:180110] Resetting plugins due to page load.
,2016-01-21 10:16:46.535 ThaliTest[286:180110] Finished load of: file:///var/mobile/Containers/Bundle/Application/D78B418C-EF28-4ABF-957A-839432EF303F/ThaliTest.app/www/index.html
,2016-01-21 10:16:46.709 ThaliTest[286:180110] JXcore Cordova plugin initializing
2016-01-21 10:16:46.710 ThaliTest[286:180708] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D78B418C-EF28-4ABF-957A-839432EF303F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D78B418C-EF28-4ABF-957A-839432EF303F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D78B418C-EF28-4ABF-957A-839432EF303F/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D78B418C-EF28-4ABF-957A-839432EF303F/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D78B418C-EF28-4ABF-957A-839432EF303F/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D78B418C-EF28-4ABF-957A-839432EF303F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D78B418C-EF28-4ABF-957A-839432EF303F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded


```

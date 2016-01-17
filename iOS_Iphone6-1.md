#### Test 561510933390750_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/561510933390750/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8B2BD9AD-194B-4FE8-B389-4ECE09D576D0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8B2BD9AD-194B-4FE8-B389-4ECE09D576D0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/561510933390750/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/561510933390750/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D55EEE03-96AB-44A9-8A6C-8C722BEF581D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57034"
,(lldb)     command script import "/tmp/8B2BD9AD-194B-4FE8-B389-4ECE09D576D0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-17 13:11:27.114 ThaliTest[2111:4492189] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/123A2220-20E7-4501-B583-E66E8C75853D/Library/Cookies/Cookies.binarycookies
,2016-01-17 13:11:27.353 ThaliTest[2111:4492189] Apache Cordova native platform version 3.9.2 is starting.
2016-01-17 13:11:27.354 ThaliTest[2111:4492189] Multi-tasking -> Device: YES, App: YES
,2016-01-17 13:11:27.361 ThaliTest[2111:4492189] Unlimited access to network resources
,2016-01-17 13:11:27.368 ThaliTest[2111:4492189] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-17 13:11:31.571 ThaliTest[2111:4492189] Resetting plugins due to page load.
,2016-01-17 13:11:33.081 ThaliTest[2111:4492189] Finished load of: file:///var/mobile/Containers/Bundle/Application/D55EEE03-96AB-44A9-8A6C-8C722BEF581D/ThaliTest.app/www/index.html
,2016-01-17 13:11:33.239 ThaliTest[2111:4492189] JXcore Cordova plugin initializing
,2016-01-17 13:11:33.241 ThaliTest[2111:4492355] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D55EEE03-96AB-44A9-8A6C-8C722BEF581D/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D55EEE03-96AB-44A9-8A6C-8C722BEF581D/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D55EEE03-96AB-44A9-8A6C-8C722BEF581D/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D55EEE03-96AB-44A9-8A6C-8C722BEF581D/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D55EEE03-96AB-44A9-8A6C-8C722BEF581D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D55EEE03-96AB-44A9-8A6C-8C722BEF581D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test app app.js loaded
,--= Surplus to requirements =--
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

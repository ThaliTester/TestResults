#### Test 575312431be71d2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312431be71d2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/63DFCC26-7E81-45B1-86FC-F97383324BD0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/63DFCC26-7E81-45B1-86FC-F97383324BD0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312431be71d2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312431be71d2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4BCB36F5-22AF-43AD-939E-B4F4C30DBB1F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64387"
,(lldb)     command script import "/tmp/63DFCC26-7E81-45B1-86FC-F97383324BD0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 14:16:30.156 ThaliTest[1012:1879200] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2FB15626-F037-438A-80F8-417B27F38941/Library/Cookies/Cookies.binarycookies
,2016-02-02 14:16:30.632 ThaliTest[1012:1879200] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 14:16:30.634 ThaliTest[1012:1879200] Multi-tasking -> Device: YES, App: YES
,2016-02-02 14:16:30.645 ThaliTest[1012:1879200] Unlimited access to network resources
,2016-02-02 14:16:30.659 ThaliTest[1012:1879200] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 14:16:40.444 ThaliTest[1012:1879200] Resetting plugins due to page load.
,2016-02-02 14:16:43.116 ThaliTest[1012:1879200] Finished load of: file:///var/mobile/Containers/Bundle/Application/4BCB36F5-22AF-43AD-939E-B4F4C30DBB1F/ThaliTest.app/www/index.html
,2016-02-02 14:16:43.281 ThaliTest[1012:1879200] JXcore Cordova plugin initializing
,2016-02-02 14:16:43.384 ThaliTest[1012:1879532] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCB36F5-22AF-43AD-939E-B4F4C30DBB1F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCB36F5-22AF-43AD-939E-B4F4C30DBB1F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCB36F5-22AF-43AD-939E-B4F4C30DBB1F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCB36F5-22AF-43AD-939E-B4F4C30DBB1F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCB36F5-22AF-43AD-939E-B4F4C30DBB1F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,appEnteringBackground wasn't registered

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

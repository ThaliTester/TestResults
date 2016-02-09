#### Test 586983493da948e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/586983493da948e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/59F3F45D-839C-43ED-A196-B499B70FFD33/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/59F3F45D-839C-43ED-A196-B499B70FFD33/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/586983493da948e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/586983493da948e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6A219B01-24D6-4418-A0EF-936559A70DDB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52587"
,(lldb)     command script import "/tmp/59F3F45D-839C-43ED-A196-B499B70FFD33/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 03:50:05.284 ThaliTest[1008:1680061] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6D129FE0-2CBF-476A-9949-7FC584F5FBC7/Library/Cookies/Cookies.binarycookies
,2016-02-09 03:50:05.738 ThaliTest[1008:1680061] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 03:50:05.739 ThaliTest[1008:1680061] Multi-tasking -> Device: YES, App: YES
,2016-02-09 03:50:05.747 ThaliTest[1008:1680061] Unlimited access to network resources
,2016-02-09 03:50:05.756 ThaliTest[1008:1680061] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 03:50:15.927 ThaliTest[1008:1680061] Resetting plugins due to page load.
,2016-02-09 03:50:20.070 ThaliTest[1008:1680061] Finished load of: file:///var/mobile/Containers/Bundle/Application/6A219B01-24D6-4418-A0EF-936559A70DDB/ThaliTest.app/www/index.html
,2016-02-09 03:50:20.233 ThaliTest[1008:1680061] JXcore Cordova plugin initializing
,2016-02-09 03:50:20.233 ThaliTest[1008:1680289] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A219B01-24D6-4418-A0EF-936559A70DDB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A219B01-24D6-4418-A0EF-936559A70DDB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A219B01-24D6-4418-A0EF-936559A70DDB/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A219B01-24D6-4418-A0EF-936559A70DDB/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A219B01-24D6-4418-A0EF-936559A70DDB/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A219B01-24D6-4418-A0EF-936559A70DDB/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A219B01-24D6-4418-A0EF-936559A70DDB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6A219B01-24D6-4418-A0EF-936559A70DDB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data


```

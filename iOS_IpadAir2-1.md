#### Test 57924002d5e0b14_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57924002d5e0b14/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/6E1713DE-A586-4B70-8EB8-F52628D5996F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6E1713DE-A586-4B70-8EB8-F52628D5996F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57924002d5e0b14/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57924002d5e0b14/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/91CC85D1-2E7B-4844-8B4E-5094142544FD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65099"
,(lldb)     command script import "/tmp/6E1713DE-A586-4B70-8EB8-F52628D5996F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 20:16:44.369 ThaliTest[519:726529] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/150B7E51-A8E7-43C1-BB17-F2D79A1EAFA6/Library/Cookies/Cookies.binarycookies
,2016-02-02 20:16:44.723 ThaliTest[519:726529] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 20:16:44.724 ThaliTest[519:726529] Multi-tasking -> Device: YES, App: YES
,2016-02-02 20:16:44.732 ThaliTest[519:726529] Unlimited access to network resources
,2016-02-02 20:16:44.740 ThaliTest[519:726529] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 20:16:54.706 ThaliTest[519:726529] Resetting plugins due to page load.
,2016-02-02 20:16:58.461 ThaliTest[519:726529] Finished load of: file:///var/mobile/Containers/Bundle/Application/91CC85D1-2E7B-4844-8B4E-5094142544FD/ThaliTest.app/www/index.html
,2016-02-02 20:16:58.621 ThaliTest[519:726529] JXcore Cordova plugin initializing
2016-02-02 20:16:58.622 ThaliTest[519:726766] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/91CC85D1-2E7B-4844-8B4E-5094142544FD/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/91CC85D1-2E7B-4844-8B4E-5094142544FD/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/91CC85D1-2E7B-4844-8B4E-5094142544FD/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/91CC85D1-2E7B-4844-8B4E-5094142544FD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/91CC85D1-2E7B-4844-8B4E-5094142544FD/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

#### Test 57659382b63fd0b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57659382b63fd0b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F715BE45-7BB6-4759-A39F-13CB7946A3EC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F715BE45-7BB6-4759-A39F-13CB7946A3EC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57659382b63fd0b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57659382b63fd0b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/83E357C6-2A4F-4EAD-9DF4-6BDB7DD33C74/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62860"
,(lldb)     command script import "/tmp/F715BE45-7BB6-4759-A39F-13CB7946A3EC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 16:48:53.459 ThaliTest[255:162610] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1465AC3E-0CBF-4C0A-9009-4DDC7D167AD2/Library/Cookies/Cookies.binarycookies
,2016-01-29 16:48:53.783 ThaliTest[255:162610] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-29 16:48:53.784 ThaliTest[255:162610] Multi-tasking -> Device: YES, App: YES
,2016-01-29 16:48:53.792 ThaliTest[255:162610] Unlimited access to network resources
,2016-01-29 16:48:53.798 ThaliTest[255:162610] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 16:49:01.950 ThaliTest[255:162610] Resetting plugins due to page load.
,2016-01-29 16:49:04.910 ThaliTest[255:162610] Finished load of: file:///var/mobile/Containers/Bundle/Application/83E357C6-2A4F-4EAD-9DF4-6BDB7DD33C74/ThaliTest.app/www/index.html
,2016-01-29 16:49:05.082 ThaliTest[255:162610] JXcore Cordova plugin initializing
,2016-01-29 16:49:05.082 ThaliTest[255:162836] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83E357C6-2A4F-4EAD-9DF4-6BDB7DD33C74/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83E357C6-2A4F-4EAD-9DF4-6BDB7DD33C74/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83E357C6-2A4F-4EAD-9DF4-6BDB7DD33C74/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83E357C6-2A4F-4EAD-9DF4-6BDB7DD33C74/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83E357C6-2A4F-4EAD-9DF4-6BDB7DD33C74/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83E357C6-2A4F-4EAD-9DF4-6BDB7DD33C74/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83E357C6-2A4F-4EAD-9DF4-6BDB7DD33C74/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/83E357C6-2A4F-4EAD-9DF4-6BDB7DD33C74/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

#### Test 575312431f256a6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312431f256a6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/425AC1D4-4D2B-4188-A350-3B751EC3F0CB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/425AC1D4-4D2B-4188-A350-3B751EC3F0CB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312431f256a6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312431f256a6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/56E2B1A1-8AB6-4EB2-BDFE-7492F6EF9D4D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64922"
,(lldb)     command script import "/tmp/425AC1D4-4D2B-4188-A350-3B751EC3F0CB/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-02-02 18:25:00.328 ThaliTest[508:715238] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4B6CE376-053E-4398-B17D-4A7BE3A9D0F8/Library/Cookies/Cookies.binarycookies
,2016-02-02 18:25:00.641 ThaliTest[508:715238] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 18:25:00.642 ThaliTest[508:715238] Multi-tasking -> Device: YES, App: YES
,2016-02-02 18:25:00.650 ThaliTest[508:715238] Unlimited access to network resources
,2016-02-02 18:25:00.656 ThaliTest[508:715238] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 18:25:10.028 ThaliTest[508:715238] Resetting plugins due to page load.
,2016-02-02 18:25:13.918 ThaliTest[508:715238] Finished load of: file:///var/mobile/Containers/Bundle/Application/56E2B1A1-8AB6-4EB2-BDFE-7492F6EF9D4D/ThaliTest.app/www/index.html
,2016-02-02 18:25:14.088 ThaliTest[508:715238] JXcore Cordova plugin initializing
,2016-02-02 18:25:14.089 ThaliTest[508:715508] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E2B1A1-8AB6-4EB2-BDFE-7492F6EF9D4D/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E2B1A1-8AB6-4EB2-BDFE-7492F6EF9D4D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E2B1A1-8AB6-4EB2-BDFE-7492F6EF9D4D/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E2B1A1-8AB6-4EB2-BDFE-7492F6EF9D4D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E2B1A1-8AB6-4EB2-BDFE-7492F6EF9D4D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****
,
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

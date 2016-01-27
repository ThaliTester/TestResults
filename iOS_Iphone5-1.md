#### Test 564496604206eac_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/564496604206eac/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/75E6235E-DA72-4EAE-AA3E-887271F73BD8/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/75E6235E-DA72-4EAE-AA3E-887271F73BD8/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/564496604206eac/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/564496604206eac/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FFE723F1-8509-4516-A038-80A2401EDB7A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61626"
,(lldb)     command script import "/tmp/75E6235E-DA72-4EAE-AA3E-887271F73BD8/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-27 10:02:43.609 ThaliTest[2003:6433579] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6F37CFBB-3BA6-42EE-96B6-8240A94946AD/Library/Cookies/Cookies.binarycookies
,2016-01-27 10:02:43.716 ThaliTest[2003:6433579] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-27 10:02:43.718 ThaliTest[2003:6433579] Multi-tasking -> Device: YES, App: YES
,2016-01-27 10:02:43.722 ThaliTest[2003:6433579] Unlimited access to network resources
,2016-01-27 10:02:43.734 ThaliTest[2003:6433579] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-27 10:02:49.954 ThaliTest[2003:6433579] Resetting plugins due to page load.
,2016-01-27 10:02:52.368 ThaliTest[2003:6433579] Finished load of: file:///var/mobile/Containers/Bundle/Application/FFE723F1-8509-4516-A038-80A2401EDB7A/ThaliTest.app/www/index.html
,2016-01-27 10:02:52.565 ThaliTest[2003:6433579] JXcore Cordova plugin initializing
,2016-01-27 10:02:52.566 ThaliTest[2003:6433809] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFE723F1-8509-4516-A038-80A2401EDB7A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFE723F1-8509-4516-A038-80A2401EDB7A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFE723F1-8509-4516-A038-80A2401EDB7A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFE723F1-8509-4516-A038-80A2401EDB7A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFE723F1-8509-4516-A038-80A2401EDB7A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFE723F1-8509-4516-A038-80A2401EDB7A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFE723F1-8509-4516-A038-80A2401EDB7A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FFE723F1-8509-4516-A038-80A2401EDB7A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

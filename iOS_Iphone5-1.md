#### Test 58135655c662d33_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655c662d33/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A51C54EE-1CC5-484F-98F0-C09C995BBD95/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/A51C54EE-1CC5-484F-98F0-C09C995BBD95/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655c662d33/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655c662d33/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C0738669-F7DF-4B22-954F-1B82BE5C5076/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49231"
,(lldb)     command script import "/tmp/A51C54EE-1CC5-484F-98F0-C09C995BBD95/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-03 19:09:57.155 ThaliTest[2454:7659441] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7F823AB0-D205-4D4C-BFAA-73395413E413/Library/Cookies/Cookies.binarycookies
,2016-02-03 19:09:57.265 ThaliTest[2454:7659441] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-03 19:09:57.267 ThaliTest[2454:7659441] Multi-tasking -> Device: YES, App: YES
,2016-02-03 19:09:57.271 ThaliTest[2454:7659441] Unlimited access to network resources
,2016-02-03 19:09:57.284 ThaliTest[2454:7659441] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-03 19:10:08.066 ThaliTest[2454:7659441] Resetting plugins due to page load.
,2016-02-03 19:10:12.233 ThaliTest[2454:7659441] Finished load of: file:///var/mobile/Containers/Bundle/Application/C0738669-F7DF-4B22-954F-1B82BE5C5076/ThaliTest.app/www/index.html
,2016-02-03 19:10:12.443 ThaliTest[2454:7659441] JXcore Cordova plugin initializing
2016-02-03 19:10:12.444 ThaliTest[2454:7659786] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0738669-F7DF-4B22-954F-1B82BE5C5076/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0738669-F7DF-4B22-954F-1B82BE5C5076/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0738669-F7DF-4B22-954F-1B82BE5C5076/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0738669-F7DF-4B22-954F-1B82BE5C5076/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0738669-F7DF-4B22-954F-1B82BE5C5076/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0738669-F7DF-4B22-954F-1B82BE5C5076/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0738669-F7DF-4B22-954F-1B82BE5C5076/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0738669-F7DF-4B22-954F-1B82BE5C5076/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

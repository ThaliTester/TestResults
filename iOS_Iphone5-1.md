#### Test 58135655a685cd3_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655a685cd3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/37FBB3B4-D845-4934-A741-6CE558D876E0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/37FBB3B4-D845-4934-A741-6CE558D876E0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655a685cd3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655a685cd3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CC3D2C2D-D1CC-47D2-97A1-2ABA67BA102F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50024"
,(lldb)     command script import "/tmp/37FBB3B4-D845-4934-A741-6CE558D876E0/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-04 14:02:14.568 ThaliTest[2545:7804942] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1E7A904A-B3CA-4A2A-B645-946670C9612A/Library/Cookies/Cookies.binarycookies
,2016-02-04 14:02:15.091 ThaliTest[2545:7804942] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-04 14:02:15.092 ThaliTest[2545:7804942] Multi-tasking -> Device: YES, App: YES
,2016-02-04 14:02:15.097 ThaliTest[2545:7804942] Unlimited access to network resources
,2016-02-04 14:02:15.108 ThaliTest[2545:7804942] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-04 14:02:25.776 ThaliTest[2545:7804942] Resetting plugins due to page load.
,2016-02-04 14:02:29.625 ThaliTest[2545:7804942] Finished load of: file:///var/mobile/Containers/Bundle/Application/CC3D2C2D-D1CC-47D2-97A1-2ABA67BA102F/ThaliTest.app/www/index.html
,2016-02-04 14:02:29.837 ThaliTest[2545:7804942] JXcore Cordova plugin initializing
,2016-02-04 14:02:29.841 ThaliTest[2545:7805296] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC3D2C2D-D1CC-47D2-97A1-2ABA67BA102F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC3D2C2D-D1CC-47D2-97A1-2ABA67BA102F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC3D2C2D-D1CC-47D2-97A1-2ABA67BA102F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC3D2C2D-D1CC-47D2-97A1-2ABA67BA102F/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC3D2C2D-D1CC-47D2-97A1-2ABA67BA102F/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC3D2C2D-D1CC-47D2-97A1-2ABA67BA102F/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC3D2C2D-D1CC-47D2-97A1-2ABA67BA102F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CC3D2C2D-D1CC-47D2-97A1-2ABA67BA102F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

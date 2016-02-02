#### Test 579720943a29850_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/579720943a29850/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/B68D184A-CF12-44A2-AA8A-BC2ED7F08951/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B68D184A-CF12-44A2-AA8A-BC2ED7F08951/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/579720943a29850/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/579720943a29850/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/159238EA-D0AE-493A-BFB2-0E00C2DF9F46/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64122"
,(lldb)     command script import "/tmp/B68D184A-CF12-44A2-AA8A-BC2ED7F08951/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-02-02 13:05:45.717 ThaliTest[967:1867258] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/37E504C6-72FF-473F-9DEB-2E31F2136999/Library/Cookies/Cookies.binarycookies
,2016-02-02 13:05:46.006 ThaliTest[967:1867258] Apache Cordova native platform version 3.9.2 is starting.
2016-02-02 13:05:46.007 ThaliTest[967:1867258] Multi-tasking -> Device: YES, App: YES
,2016-02-02 13:05:46.012 ThaliTest[967:1867258] Unlimited access to network resources
,2016-02-02 13:05:46.019 ThaliTest[967:1867258] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 13:05:53.866 ThaliTest[967:1867258] Resetting plugins due to page load.
,2016-02-02 13:05:57.050 ThaliTest[967:1867258] Finished load of: file:///var/mobile/Containers/Bundle/Application/159238EA-D0AE-493A-BFB2-0E00C2DF9F46/ThaliTest.app/www/index.html
,2016-02-02 13:05:57.246 ThaliTest[967:1867258] JXcore Cordova plugin initializing
2016-02-02 13:05:57.247 ThaliTest[967:1867707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/159238EA-D0AE-493A-BFB2-0E00C2DF9F46/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/159238EA-D0AE-493A-BFB2-0E00C2DF9F46/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/159238EA-D0AE-493A-BFB2-0E00C2DF9F46/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/159238EA-D0AE-493A-BFB2-0E00C2DF9F46/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/159238EA-D0AE-493A-BFB2-0E00C2DF9F46/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/159238EA-D0AE-493A-BFB2-0E00C2DF9F46/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/159238EA-D0AE-493A-BFB2-0E00C2DF9F46/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/159238EA-D0AE-493A-BFB2-0E00C2DF9F46/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,appEnteringBackground wasn't registered

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

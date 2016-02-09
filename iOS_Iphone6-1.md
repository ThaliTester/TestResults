#### Test 58380500c26a9ef_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500c26a9ef/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/FA07347F-99AB-4764-9729-6538E20DF492/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/FA07347F-99AB-4764-9729-6538E20DF492/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500c26a9ef/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500c26a9ef/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52463"
,(lldb)     command script import "/tmp/FA07347F-99AB-4764-9729-6538E20DF492/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 03:05:27.328 ThaliTest[1550:2882063] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/36C5BFC4-23EF-45E7-8322-C802FCB95BB5/Library/Cookies/Cookies.binarycookies
,2016-02-09 03:05:27.805 ThaliTest[1550:2882063] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 03:05:27.807 ThaliTest[1550:2882063] Multi-tasking -> Device: YES, App: YES
,2016-02-09 03:05:27.817 ThaliTest[1550:2882063] Unlimited access to network resources
,2016-02-09 03:05:27.830 ThaliTest[1550:2882063] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 03:05:37.658 ThaliTest[1550:2882063] Resetting plugins due to page load.
,2016-02-09 03:05:40.894 ThaliTest[1550:2882063] Finished load of: file:///var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app/www/index.html
,2016-02-09 03:05:41.072 ThaliTest[1550:2882063] JXcore Cordova plugin initializing
,2016-02-09 03:05:41.076 ThaliTest[1550:2882402] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F3176A9A-DB03-4340-8B1B-324DAE400574/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

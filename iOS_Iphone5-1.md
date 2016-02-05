#### Test 5838050069f842e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5838050069f842e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/675B4CAF-4422-4E9C-B753-C047EB6A6997/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/675B4CAF-4422-4E9C-B753-C047EB6A6997/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5838050069f842e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5838050069f842e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50840"
,(lldb)     command script import "/tmp/675B4CAF-4422-4E9C-B753-C047EB6A6997/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-05 20:36:39.695 ThaliTest[2620:8016028] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C944E8DF-65B4-44A5-8A6B-FEE725155F2B/Library/Cookies/Cookies.binarycookies
,2016-02-05 20:36:39.842 ThaliTest[2620:8016028] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-05 20:36:39.844 ThaliTest[2620:8016028] Multi-tasking -> Device: YES, App: YES
,2016-02-05 20:36:39.852 ThaliTest[2620:8016028] Unlimited access to network resources
,2016-02-05 20:36:39.866 ThaliTest[2620:8016028] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-05 20:36:50.623 ThaliTest[2620:8016028] Resetting plugins due to page load.
,2016-02-05 20:36:54.796 ThaliTest[2620:8016028] Finished load of: file:///var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app/www/index.html
,2016-02-05 20:36:55.011 ThaliTest[2620:8016028] JXcore Cordova plugin initializing
,2016-02-05 20:36:55.012 ThaliTest[2620:8016304] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D09B0B0C-9DE6-4DAA-BAB4-7465874D3B88/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal

,ok 2 should be equal

,ok 3 should be equal

,ok 4 should be equal

,# teardown

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,ok 5 should be equal

,ok 6 should be equal

,ok 7 should be equal

,ok 8 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 9 should throw

,# teardown

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 10 should throw

,# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 11 should be equal

,# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in beaconStreamWithPreAmble

,ok 12 should throw

,# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 13 should be equal

,# teardown

# setup

,# #parseBeacons addressBookCallback returns null for all

,ok 14 (unnamed assert)

,ok 15 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 16 (unnamed assert)

,ok 17 (unnamed assert)

,# teardown

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

#### Test 58380500fccea7e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500fccea7e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/9DD8B53D-10D1-4EC5-89C0-303AEDBD3D56/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/9DD8B53D-10D1-4EC5-89C0-303AEDBD3D56/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500fccea7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500fccea7e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51142"
,(lldb)     command script import "/tmp/9DD8B53D-10D1-4EC5-89C0-303AEDBD3D56/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-06 01:11:14.510 ThaliTest[2665:8051807] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7D4D7D0A-05A4-4218-BC73-F4D269A66CC9/Library/Cookies/Cookies.binarycookies
,2016-02-06 01:11:15.088 ThaliTest[2665:8051807] Apache Cordova native platform version 3.9.2 is starting.
2016-02-06 01:11:15.090 ThaliTest[2665:8051807] Multi-tasking -> Device: YES, App: YES
,2016-02-06 01:11:15.095 ThaliTest[2665:8051807] Unlimited access to network resources
,2016-02-06 01:11:15.107 ThaliTest[2665:8051807] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-06 01:11:26.114 ThaliTest[2665:8051807] Resetting plugins due to page load.
,2016-02-06 01:11:29.951 ThaliTest[2665:8051807] Finished load of: file:///var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app/www/index.html
,2016-02-06 01:11:30.160 ThaliTest[2665:8051807] JXcore Cordova plugin initializing
,2016-02-06 01:11:30.162 ThaliTest[2665:8052101] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5D9CAAEE-C4D4-4DC7-AD94-A3318772AE95/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,2016-02-06 01:11:56.484 ThaliTest[2665:8051807] THREAD WARNING: ['JXcore'] took '10.178955' ms. Plugin should use a background thread.
,# setup

# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal
,
ok 2 should be equal

ok 3 should be equal

ok 4 should be equal

# teardown

# setup

,# #generatePreambleAndBeacons multiple keys to notify

,ok 5 should be equal

,ok 6 should be equal

,ok 7 should be equal

,ok 8 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 9 should throw

# teardown

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 10 should throw

,# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 11 should be equal

# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 12 should throw

# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 13 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns null for all

,ok 14 (unnamed assert)

,ok 15 should be equal

# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 16 (unnamed assert)

,ok 17 (unnamed assert)

,# teardown

,# setup

,# #parseBeacons with beacons both for and not for the user

,ok 18 (unnamed assert)

# teardown

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

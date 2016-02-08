#### Test 58380500962e22b_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500962e22b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4B784BD7-0CE1-423A-B289-1D2CDDEC3255/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4B784BD7-0CE1-423A-B289-1D2CDDEC3255/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500962e22b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500962e22b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52260"
,(lldb)     command script import "/tmp/4B784BD7-0CE1-423A-B289-1D2CDDEC3255/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 00:13:40.854 ThaliTest[2756:8538032] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D05D5C82-818E-4E09-BFE6-9A1710148362/Library/Cookies/Cookies.binarycookies
,2016-02-09 00:13:40.983 ThaliTest[2756:8538032] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 00:13:40.985 ThaliTest[2756:8538032] Multi-tasking -> Device: YES, App: YES
,2016-02-09 00:13:40.990 ThaliTest[2756:8538032] Unlimited access to network resources
,2016-02-09 00:13:41.006 ThaliTest[2756:8538032] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 00:13:51.203 ThaliTest[2756:8538032] Resetting plugins due to page load.
,2016-02-09 00:13:55.451 ThaliTest[2756:8538032] Finished load of: file:///var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app/www/index.html
,2016-02-09 00:13:55.664 ThaliTest[2756:8538032] JXcore Cordova plugin initializing
,2016-02-09 00:13:55.668 ThaliTest[2756:8538382] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0290D86E-1C52-4935-93D7-1FA033AC76E6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal

,# teardown

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,ok 2 should be equal

,ok 3 should be equal

,ok 4 should be equal

,ok 5 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 6 should throw

,# teardown

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 7 should throw

,# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 8 should be equal

,# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 9 should throw

,# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 10 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns no matches

,ok 11 should be equal

,ok 12 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 13 should be equal

,ok 14 (unnamed assert)

,# teardown

,# setup

,# #parseBeacons with beacons both for and not for the user

,ok 15 (unnamed assert)

,# teardown


```

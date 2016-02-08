#### Test 58380500055030c_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500055030c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4C6C9C09-7DC5-4DA7-839B-11CE112C5233/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4C6C9C09-7DC5-4DA7-839B-11CE112C5233/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500055030c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500055030c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52127"
,(lldb)     command script import "/tmp/4C6C9C09-7DC5-4DA7-839B-11CE112C5233/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-08 23:30:23.801 ThaliTest[2751:8531384] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/05F9B379-F4B7-420B-BC57-B755DA871CB2/Library/Cookies/Cookies.binarycookies
,2016-02-08 23:30:23.919 ThaliTest[2751:8531384] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-08 23:30:23.921 ThaliTest[2751:8531384] Multi-tasking -> Device: YES, App: YES
,2016-02-08 23:30:23.927 ThaliTest[2751:8531384] Unlimited access to network resources
,2016-02-08 23:30:23.941 ThaliTest[2751:8531384] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-08 23:30:34.692 ThaliTest[2751:8531384] Resetting plugins due to page load.
,2016-02-08 23:30:38.628 ThaliTest[2751:8531384] Finished load of: file:///var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app/www/index.html
,2016-02-08 23:30:38.844 ThaliTest[2751:8531384] JXcore Cordova plugin initializing
,2016-02-08 23:30:38.847 ThaliTest[2751:8531579] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/440DF3EA-9C87-486F-8697-EE8ED4749DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,2016-02-08 23:31:04.881 ThaliTest[2751:8531384] THREAD WARNING: ['JXcore'] took '10.952881' ms. Plugin should use a background thread.
,# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 1 should be equal

,# teardown

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,ok 2 should be equal

ok 3 should be equal

,ok 4 should be equal

,ok 5 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 6 should throw

# teardown

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 7 should throw

# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 8 should be equal

,# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 9 should throw

# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 10 should be equal

# teardown

,# setup

,# #parseBeacons addressBookCallback returns null for all

,ok 11 (unnamed assert)

,ok 12 should be equal

# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 13 (unnamed assert)

,ok 14 (unnamed assert)

,# teardown

,# setup

,# #parseBeacons with beacons both for and not for the user

,ok 15 (unnamed assert)

,# teardown


```

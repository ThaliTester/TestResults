#### Test 583805003a0697c_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/583805003a0697c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4F25A3E7-5980-4B6B-AEF6-9469870F4FE1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4F25A3E7-5980-4B6B-AEF6-9469870F4FE1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/583805003a0697c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/583805003a0697c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53844"
,(lldb)     command script import "/tmp/4F25A3E7-5980-4B6B-AEF6-9469870F4FE1/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 23:13:19.498 ThaliTest[2903:8710901] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/44886910-E2AE-42EB-BD80-F49C83A8E81D/Library/Cookies/Cookies.binarycookies
,2016-02-09 23:13:20.028 ThaliTest[2903:8710901] Apache Cordova native platform version 3.9.2 is starting.
2016-02-09 23:13:20.029 ThaliTest[2903:8710901] Multi-tasking -> Device: YES, App: YES
,2016-02-09 23:13:20.034 ThaliTest[2903:8710901] Unlimited access to network resources
,2016-02-09 23:13:20.047 ThaliTest[2903:8710901] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 23:13:30.817 ThaliTest[2903:8710901] Resetting plugins due to page load.
,2016-02-09 23:13:34.436 ThaliTest[2903:8710901] Finished load of: file:///var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/index.html
,2016-02-09 23:13:34.650 ThaliTest[2903:8710901] JXcore Cordova plugin initializing
,2016-02-09 23:13:34.654 ThaliTest[2903:8711458] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3197A0CA-B016-46C2-99E4-06D8F3405FF9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

# #generatePreambleAndBeacons null ECDH for local device

,ok 1 publicKeysToNotify cannot be null

,# teardown

,# setup

,# #generatePreambleAndBeacons null ECDH for local device

,ok 2 ecdhForLocalDevice cannot be null

,# teardown

,# setup

,# #generatePreambleAndBeacons expiration out of range lower

,ok 3 secondsUntilExpiration out of range.

,# teardown

,# setup

,# #generatePreambleAndBeacons expiration out of range upper

,ok 4 secondsUntilExpiration out of range.

,# teardown

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,ok 5 should be equal

,# teardown

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,ok 6 should be equal

,ok 7 should be equal

,ok 8 should be equal

,ok 9 should be equal

,# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 10 should throw

# teardown

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 11 Preamble expiration must be a 64 bit integer

,# teardown

,# setup

,# #parseBeacons expiration out of range lower

,ok 12 Expiration out of range

# teardown

,# setup

,# #parseBeacons expiration out of range lower

,ok 13 Expiration out of range

# teardown

,# setup

,# #parseBeacons no beacons returns null

,ok 14 should be equal

# teardown

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 15 Malformed encrypted beacon key ID

# teardown

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 16 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns no matches

,ok 17 should be equal

ok 18 should be equal

,# teardown

,# setup

,# #parseBeacons addressBookCallback returns public key

,ok 19 should be equal

,ok 20 (unnamed assert)

,# teardown

,# setup

,# #parseBeacons with beacons both for and not for the user

,ok 21 (unnamed assert)

,# teardown


```

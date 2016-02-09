#### Test 583805003a0697c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/583805003a0697c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/BFBB6312-8D3D-4584-A19D-6571EBBCEC97/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BFBB6312-8D3D-4584-A19D-6571EBBCEC97/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/583805003a0697c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/583805003a0697c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53883"
,(lldb)     command script import "/tmp/BFBB6312-8D3D-4584-A19D-6571EBBCEC97/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 23:14:37.950 ThaliTest[1214:1832028] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/29415C2B-CAD9-44FD-BB60-ADE91DCEFCC5/Library/Cookies/Cookies.binarycookies
,2016-02-09 23:14:38.414 ThaliTest[1214:1832028] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 23:14:38.415 ThaliTest[1214:1832028] Multi-tasking -> Device: YES, App: YES
,2016-02-09 23:14:38.424 ThaliTest[1214:1832028] Unlimited access to network resources
,2016-02-09 23:14:38.433 ThaliTest[1214:1832028] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 23:14:48.531 ThaliTest[1214:1832028] Resetting plugins due to page load.
,2016-02-09 23:14:52.731 ThaliTest[1214:1832028] Finished load of: file:///var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/index.html
,2016-02-09 23:14:52.891 ThaliTest[1214:1832028] JXcore Cordova plugin initializing
2016-02-09 23:14:52.891 ThaliTest[1214:1832271] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/644149B6-EE2E-4FD2-9124-2DF888126A54/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

# #generatePreambleAndBeacons null ECDH for local device

,ok 1 publicKeysToNotify cannot be null

# teardown

,# setup

,# #generatePreambleAndBeacons null ECDH for local device

,ok 2 ecdhForLocalDevice cannot be null

# teardown

,# setup

,# #generatePreambleAndBeacons expiration out of range lower

,ok 3 secondsUntilExpiration out of range.

,# teardown

,# setup

,# #generatePreambleAndBeacons expiration out of range upper

,ok 4 secondsUntilExpiration out of range.

# teardown

,# setup

# #generatePreambleAndBeacons empty keys to notify

,ok 5 should be equal

,# teardown

# setup

,# #generatePreambleAndBeacons multiple keys to notify

,ok 6 should be equal

ok 7 should be equal

,ok 8 should be equal

,ok 9 should be equal

# teardown

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,ok 10 should throw

,# teardown

# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,ok 11 Preamble expiration must be a 64 bit integer

# teardown

,# setup

,# #parseBeacons expiration out of range lower

,ok 12 Expiration out of range

# teardown

,# setup

# #parseBeacons expiration out of range lower

,ok 13 Expiration out of range

,# teardown

,# setup

# #parseBeacons no beacons returns null

,ok 14 should be equal

# teardown

# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,ok 15 Malformed encrypted beacon key ID

# teardown

# setup

,# #parseBeacons addressBookCallback fails decrypt

,ok 16 should be equal

# teardown

# setup

# #parseBeacons addressBookCallback returns no matches

,ok 17 should be equal

,ok 18 should be equal

,# teardown

# setup

,# #parseBeacons addressBookCallback returns public key

,ok 19 should be equal

,ok 20 (unnamed assert)

# teardown

,# setup

# #parseBeacons with beacons both for and not for the user

,ok 21 (unnamed assert)

# teardown

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered


```

#### Test 56672827039a409_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56672827039a409/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0E27B8EC-BC08-4EBE-B274-8F34E15EC27B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0E27B8EC-BC08-4EBE-B274-8F34E15EC27B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56672827039a409/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56672827039a409/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F71BAF12-359B-4650-AA52-B4093C75F416/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59874"
,(lldb)     command script import "/tmp/0E27B8EC-BC08-4EBE-B274-8F34E15EC27B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 18:14:52.613 ThaliTest[2427:6202881] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F93843A-093A-48E1-A663-F3695A5FAEC5/Library/Cookies/Cookies.binarycookies
,2016-01-21 18:14:52.909 ThaliTest[2427:6202881] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-21 18:14:52.910 ThaliTest[2427:6202881] Multi-tasking -> Device: YES, App: YES
,2016-01-21 18:14:52.920 ThaliTest[2427:6202881] Unlimited access to network resources
,2016-01-21 18:14:52.930 ThaliTest[2427:6202881] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 18:14:57.564 ThaliTest[2427:6202881] Resetting plugins due to page load.
,2016-01-21 18:14:59.065 ThaliTest[2427:6202881] Finished load of: file:///var/mobile/Containers/Bundle/Application/F71BAF12-359B-4650-AA52-B4093C75F416/ThaliTest.app/www/index.html
,2016-01-21 18:14:59.290 ThaliTest[2427:6202881] JXcore Cordova plugin initializing
2016-01-21 18:14:59.291 ThaliTest[2427:6203045] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F71BAF12-359B-4650-AA52-B4093C75F416/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F71BAF12-359B-4650-AA52-B4093C75F416/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F71BAF12-359B-4650-AA52-B4093C75F416/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F71BAF12-359B-4650-AA52-B4093C75F416/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F71BAF12-359B-4650-AA52-B4093C75F416/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F71BAF12-359B-4650-AA52-B4093C75F416/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F71BAF12-359B-4650-AA52-B4093C75F416/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F71BAF12-359B-4650-AA52-B4093C75F416/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown


```

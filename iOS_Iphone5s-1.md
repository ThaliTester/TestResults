#### Test 568182548138a64_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/568182548138a64/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/76565BDF-EE08-4B50-80F1-61B7D81CEB64/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/76565BDF-EE08-4B50-80F1-61B7D81CEB64/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/568182548138a64/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/568182548138a64/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C0251EA0-8BA0-4A03-91C1-E788AB318A87/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60024"
,(lldb)     command script import "/tmp/76565BDF-EE08-4B50-80F1-61B7D81CEB64/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 23:39:22.582 ThaliTest[2444:6260891] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1914A13F-1520-4E96-ACBE-324F5ACB468A/Library/Cookies/Cookies.binarycookies
,2016-01-21 23:39:22.885 ThaliTest[2444:6260891] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-21 23:39:22.886 ThaliTest[2444:6260891] Multi-tasking -> Device: YES, App: YES
,2016-01-21 23:39:22.894 ThaliTest[2444:6260891] Unlimited access to network resources
,2016-01-21 23:39:22.905 ThaliTest[2444:6260891] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 23:39:27.321 ThaliTest[2444:6260891] Resetting plugins due to page load.
,2016-01-21 23:39:28.827 ThaliTest[2444:6260891] Finished load of: file:///var/mobile/Containers/Bundle/Application/C0251EA0-8BA0-4A03-91C1-E788AB318A87/ThaliTest.app/www/index.html
,2016-01-21 23:39:29.046 ThaliTest[2444:6260891] JXcore Cordova plugin initializing
2016-01-21 23:39:29.047 ThaliTest[2444:6261062] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0251EA0-8BA0-4A03-91C1-E788AB318A87/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0251EA0-8BA0-4A03-91C1-E788AB318A87/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0251EA0-8BA0-4A03-91C1-E788AB318A87/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0251EA0-8BA0-4A03-91C1-E788AB318A87/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0251EA0-8BA0-4A03-91C1-E788AB318A87/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0251EA0-8BA0-4A03-91C1-E788AB318A87/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0251EA0-8BA0-4A03-91C1-E788AB318A87/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown


```

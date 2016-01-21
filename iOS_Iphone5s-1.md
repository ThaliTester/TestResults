#### Test 564496600f5d794_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/564496600f5d794/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/FBD41807-2EC5-4A7D-B2B2-625ABF44BE8F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FBD41807-2EC5-4A7D-B2B2-625ABF44BE8F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/564496600f5d794/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/564496600f5d794/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/66E40190-13D1-46B7-8041-6EF9466A9E31/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59428"
,(lldb)     command script import "/tmp/FBD41807-2EC5-4A7D-B2B2-625ABF44BE8F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 11:01:45.331 ThaliTest[2384:6121658] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9C4C9CC7-3BA2-41F3-8ACA-3A634FFE4B50/Library/Cookies/Cookies.binarycookies
,2016-01-21 11:01:45.617 ThaliTest[2384:6121658] Apache Cordova native platform version 3.9.2 is starting.
2016-01-21 11:01:45.618 ThaliTest[2384:6121658] Multi-tasking -> Device: YES, App: YES
,2016-01-21 11:01:45.625 ThaliTest[2384:6121658] Unlimited access to network resources
,2016-01-21 11:01:45.635 ThaliTest[2384:6121658] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 11:01:49.985 ThaliTest[2384:6121658] Resetting plugins due to page load.
,2016-01-21 11:01:51.539 ThaliTest[2384:6121658] Finished load of: file:///var/mobile/Containers/Bundle/Application/66E40190-13D1-46B7-8041-6EF9466A9E31/ThaliTest.app/www/index.html
,2016-01-21 11:01:51.755 ThaliTest[2384:6121658] JXcore Cordova plugin initializing
2016-01-21 11:01:51.756 ThaliTest[2384:6121828] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E40190-13D1-46B7-8041-6EF9466A9E31/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E40190-13D1-46B7-8041-6EF9466A9E31/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E40190-13D1-46B7-8041-6EF9466A9E31/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E40190-13D1-46B7-8041-6EF9466A9E31/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E40190-13D1-46B7-8041-6EF9466A9E31/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E40190-13D1-46B7-8041-6EF9466A9E31/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/66E40190-13D1-46B7-8041-6EF9466A9E31/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown


```

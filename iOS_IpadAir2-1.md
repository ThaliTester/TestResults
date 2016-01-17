#### Test 561510933390750_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/561510933390750/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BE4E0AA6-4262-459E-A5C4-E5564FD9CBD9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BE4E0AA6-4262-459E-A5C4-E5564FD9CBD9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/561510933390750/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/561510933390750/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7B55AA58-E575-4923-9768-CD0AE926A244/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57024"
,(lldb)     command script import "/tmp/BE4E0AA6-4262-459E-A5C4-E5564FD9CBD9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-17 13:11:24.788 ThaliTest[2179:4734274] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/381A751B-8A54-41C6-AC7E-4C4917C3BC12/Library/Cookies/Cookies.binarycookies
,2016-01-17 13:11:25.019 ThaliTest[2179:4734274] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-17 13:11:25.019 ThaliTest[2179:4734274] Multi-tasking -> Device: YES, App: YES
,2016-01-17 13:11:25.026 ThaliTest[2179:4734274] Unlimited access to network resources
,2016-01-17 13:11:25.031 ThaliTest[2179:4734274] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-17 13:11:29.199 ThaliTest[2179:4734274] Resetting plugins due to page load.
,2016-01-17 13:11:30.646 ThaliTest[2179:4734274] Finished load of: file:///var/mobile/Containers/Bundle/Application/7B55AA58-E575-4923-9768-CD0AE926A244/ThaliTest.app/www/index.html
,2016-01-17 13:11:30.786 ThaliTest[2179:4734274] JXcore Cordova plugin initializing
,2016-01-17 13:11:30.787 ThaliTest[2179:4734451] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B55AA58-E575-4923-9768-CD0AE926A244/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B55AA58-E575-4923-9768-CD0AE926A244/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B55AA58-E575-4923-9768-CD0AE926A244/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B55AA58-E575-4923-9768-CD0AE926A244/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B55AA58-E575-4923-9768-CD0AE926A244/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7B55AA58-E575-4923-9768-CD0AE926A244/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test app app.js loaded
,TAP version 13
,# setup
,# basic
,# teardown

```

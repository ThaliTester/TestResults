#### Test 57972094912017a_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57972094912017a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/DDBE3A6D-59C4-4192-B7D4-3054ECDB7D6A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/DDBE3A6D-59C4-4192-B7D4-3054ECDB7D6A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57972094912017a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57972094912017a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8D39A9C5-7CF0-4F6C-8415-2CBDAD5A3786/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64454"
,(lldb)     command script import "/tmp/DDBE3A6D-59C4-4192-B7D4-3054ECDB7D6A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 14:44:11.939 ThaliTest[2347:7460511] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/531B3F67-6D5C-4285-BE45-729F8E319B0F/Library/Cookies/Cookies.binarycookies
,2016-02-02 14:44:12.311 ThaliTest[2347:7460511] Apache Cordova native platform version 3.9.2 is starting.
2016-02-02 14:44:12.312 ThaliTest[2347:7460511] Multi-tasking -> Device: YES, App: YES
2016-02-02 14:44:12.316 ThaliTest[2347:7460511] Unlimited acc,ess to network resources
2016-02-02 14:44:12.326 ThaliTest[2347:7460511] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelin,es" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 14:44:18.670 ThaliTest[2347:7460511] Resetting plugins due to page load.
,2016-02-02 14:44:20.845 ThaliTest[2347:7460511] Finished load of: file:///var/mobile/Containers/Bundle/Application/8D39A9C5-7CF0-4F6C-8415-2CBDAD5A3786/ThaliTest.app/www/index.html
,2016-02-02 14:44:21.105 ThaliTest[2347:7460511] JXcore Cordova plugin initializing
2016-02-02 14:44:21.106 ThaliTest[2347:7460727] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D39A9C5-7CF0-4F6C-8415-2CBDAD5A3786/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D39A9C5-7CF0-4F6C-8415-2CBDAD5A3786/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D39A9C5-7CF0-4F6C-8415-2CBDAD5A3786/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D39A9C5-7CF0-4F6C-8415-2CBDAD5A3786/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D39A9C5-7CF0-4F6C-8415-2CBDAD5A3786/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D39A9C5-7CF0-4F6C-8415-2CBDAD5A3786/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D39A9C5-7CF0-4F6C-8415-2CBDAD5A3786/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8D39A9C5-7CF0-4F6C-8415-2CBDAD5A3786/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown


```

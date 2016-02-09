#### Test 587523534d3a10e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/587523534d3a10e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A828A714-1055-4B2A-AD61-FFAAB5E83E37/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/A828A714-1055-4B2A-AD61-FFAAB5E83E37/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/587523534d3a10e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/587523534d3a10e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53380"
,(lldb)     command script import "/tmp/A828A714-1055-4B2A-AD61-FFAAB5E83E37/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-02-09 15:47:33.552 ThaliTest[2868:8656612] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/60092F4E-5920-416A-BE6C-7A689A35E97D/Library/Cookies/Cookies.binarycookies
,2016-02-09 15:47:33.707 ThaliTest[2868:8656612] Apache Cordova native platform version 3.9.2 is starting.
2016-02-09 15:47:33.708 ThaliTest[2868:8656612] Multi-tasking -> Device: YES, App: YES
2016-02-09 15:47:33.713 ThaliTest[2868:8656612] Unlimited access to network resources
,2016-02-09 15:47:33.725 ThaliTest[2868:8656612] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 15:47:44.456 ThaliTest[2868:8656612] Resetting plugins due to page load.
,2016-02-09 15:47:48.605 ThaliTest[2868:8656612] Finished load of: file:///var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app/www/index.html
,2016-02-09 15:47:48.820 ThaliTest[2868:8656612] JXcore Cordova plugin initializing
2016-02-09 15:47:48.822 ThaliTest[2868:8656941] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/418A79F5-B13E-4BD7-AD6C-ABE23819C6D7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded


```

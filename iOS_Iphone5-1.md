#### Test 58135655812b57f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655812b57f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/645A0FC5-9796-4C83-A654-C618AF513C92/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/645A0FC5-9796-4C83-A654-C618AF513C92/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655812b57f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655812b57f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4C11C470-C3FD-4911-8F67-5C7AF164E5C2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51842"
,(lldb)     command script import "/tmp/645A0FC5-9796-4C83-A654-C618AF513C92/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-08 17:21:57.684 ThaliTest[2738:8487859] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/14392063-CAC1-454E-B234-326E4B0EE286/Library/Cookies/Cookies.binarycookies
,2016-02-08 17:21:57.807 ThaliTest[2738:8487859] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-08 17:21:57.810 ThaliTest[2738:8487859] Multi-tasking -> Device: YES, App: YES
,2016-02-08 17:21:57.816 ThaliTest[2738:8487859] Unlimited access to network resources
,2016-02-08 17:21:57.828 ThaliTest[2738:8487859] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-08 17:22:08.036 ThaliTest[2738:8487859] Resetting plugins due to page load.
,2016-02-08 17:22:11.467 ThaliTest[2738:8487859] Finished load of: file:///var/mobile/Containers/Bundle/Application/4C11C470-C3FD-4911-8F67-5C7AF164E5C2/ThaliTest.app/www/index.html
,2016-02-08 17:22:11.674 ThaliTest[2738:8487859] JXcore Cordova plugin initializing
,2016-02-08 17:22:11.680 ThaliTest[2738:8488077] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C11C470-C3FD-4911-8F67-5C7AF164E5C2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C11C470-C3FD-4911-8F67-5C7AF164E5C2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C11C470-C3FD-4911-8F67-5C7AF164E5C2/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C11C470-C3FD-4911-8F67-5C7AF164E5C2/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C11C470-C3FD-4911-8F67-5C7AF164E5C2/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C11C470-C3FD-4911-8F67-5C7AF164E5C2/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C11C470-C3FD-4911-8F67-5C7AF164E5C2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C11C470-C3FD-4911-8F67-5C7AF164E5C2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded


```

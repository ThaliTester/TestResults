#### Test 58918757c0fcaf3_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58918757c0fcaf3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8DC6B551-0D07-4D7A-9D8D-CA17EA247D17/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/8DC6B551-0D07-4D7A-9D8D-CA17EA247D17/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58918757c0fcaf3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58918757c0fcaf3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54497"
,(lldb)     command script import "/tmp/8DC6B551-0D07-4D7A-9D8D-CA17EA247D17/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-10 18:04:39.156 ThaliTest[2970:8840667] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8CF19FB3-F475-4D7E-9F75-279A3060E213/Library/Cookies/Cookies.binarycookies
,2016-02-10 18:04:39.712 ThaliTest[2970:8840667] Apache Cordova native platform version 4.0.1 is starting.
,2016-02-10 18:04:39.713 ThaliTest[2970:8840667] Multi-tasking -> Device: YES, App: YES
,2016-02-10 18:04:39.736 ThaliTest[2970:8840667] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-10 18:04:41.984 ThaliTest[2970:8840667] Using UIWebView
,2016-02-10 18:04:41.989 ThaliTest[2970:8840667] [CDVTimer][handleopenurl] 0.333965ms
,2016-02-10 18:04:41.995 ThaliTest[2970:8840667] [CDVTimer][intentandnavigationfilter] 5.150020ms
2016-02-10 18:04:41.996 ThaliTest[2970:8840667] [CDVTimer][gesturehandler] 0.258982ms
2016-02-10 18:04:41.996 ThaliTest[2970:8840667] [CDVTimer][TotalPluginStartup] 6.935000ms
,2016-02-10 18:04:50.588 ThaliTest[2970:8840667] Resetting plugins due to page load.
,2016-02-10 18:04:54.185 ThaliTest[2970:8840667] Finished load of: file:///var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/index.html
,2016-02-10 18:04:54.398 ThaliTest[2970:8840667] JXcore Cordova plugin initializing
,2016-02-10 18:04:54.402 ThaliTest[2970:8840871] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E0CE5B62-0891-408C-BB8D-68B4F4372205/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded


```

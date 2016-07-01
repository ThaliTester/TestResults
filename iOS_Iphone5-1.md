#### Test 757892686fd65a6_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/84F5EC9F-7CBD-42B0-AC54-984D216F9D4D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/84F5EC9F-7CBD-42B0-AC54-984D216F9D4D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892686fd65a6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65187"
,(lldb)     command script import "/tmp/84F5EC9F-7CBD-42B0-AC54-984D216F9D4D/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-01 08:54:55.668 ThaliTest[4501:19831863] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9182E72E-B6BF-452B-AABC-506EEDD8B26B/Library/Cookies/Cookies.binarycookies
,2016-07-01 08:54:55.777 ThaliTest[4501:19831863] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-01 08:54:55.779 ThaliTest[4501:19831863] Multi-tasking -> Device: YES, App: YES
,2016-07-01 08:54:55.796 ThaliTest[4501:19831863] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-01 08:54:56.937 ThaliTest[4501:19831863] Using UIWebView
2016-07-01 08:54:56.941 ThaliTest[4501:19831863] [CDVTimer][handleopenurl] 0.313997ms
,2016-07-01 08:54:56.948 ThaliTest[4501:19831863] [CDVTimer][intentandnavigationfilter] 6.774008ms
2016-07-01 08:54:56.949 ThaliTest[4501:19831863] [CDVTimer][gesturehandler] 0.226974ms
2016-07-01 08:54:56.949 ThaliTest[4501:19831863] [CDVTimer][TotalPluginStartup] 8.143008ms
,2016-07-01 08:55:02.048 ThaliTest[4501:19831863] Resetting plugins due to page load.
,2016-07-01 08:55:03.896 ThaliTest[4501:19831863] Finished load of: file:///var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/index.html
,2016-07-01 08:55:04.092 ThaliTest[4501:19831863] JXcore Cordova plugin initializing
,2016-07-01 08:55:04.212 ThaliTest[4501:19832003] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2016-07-01 08:55:18.622 ThaliTest[4501:19832003] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-01 08:55:18.623 ThaliTest[4501:19832003] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-01 08:55:18.624 ThaliTest[4501,:19832003] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-07-01 08:55:18.626 ThaliTest[4501:19832003] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,2016-07-01 08:55:19.254 ThaliTest[4501:19831863] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-07-01 08:55:19.254 ThaliTest[4501:19831863] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore1641301841","JXcore","Test",[]]
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71BF9547-3C86-4E0B-91CD-F01B7AB15263/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

```

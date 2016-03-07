#### Test 613623665d5a4d6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/613623665d5a4d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/086FB5C9-AA9F-4C92-A789-F4CF5B3907FD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/086FB5C9-AA9F-4C92-A789-F4CF5B3907FD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/613623665d5a4d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/613623665d5a4d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50762"
,(lldb)     command script import "/tmp/086FB5C9-AA9F-4C92-A789-F4CF5B3907FD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 10:50:08.213 ThaliTest[816:1175751] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EFEB75D4-7991-4EFD-BDD7-61B0406C0E63/Library/Cookies/Cookies.binarycookies
,2016-03-07 10:50:08.661 ThaliTest[816:1175751] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 10:50:08.663 ThaliTest[816:1175751] Multi-tasking -> Device: YES, App: YES
,2016-03-07 10:50:08.686 ThaliTest[816:1175751] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 10:50:10.466 ThaliTest[816:1175751] Using UIWebView
,2016-03-07 10:50:10.474 ThaliTest[816:1175751] [CDVTimer][handleopenurl] 0.424981ms
,2016-03-07 10:50:10.482 ThaliTest[816:1175751] [CDVTimer][intentandnavigationfilter] 8.056998ms
2016-03-07 10:50:10.483 ThaliTest[816:1175751] [CDVTimer][gesturehandler] 0.415027ms
2016-03-07 10:50:10.484 ThaliTest[816:1175751] [CDVTimer][TotalPluginStartup] 10.812998ms
,2016-03-07 10:50:17.934 ThaliTest[816:1175751] Resetting plugins due to page load.
,2016-03-07 10:50:21.783 ThaliTest[816:1175751] Finished load of: file:///var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/index.html
,2016-03-07 10:50:22.032 ThaliTest[816:1175751] JXcore Cordova plugin initializing
,2016-03-07 10:50:22.034 ThaliTest[816:1175973] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 10:50:35.819 ThaliTest[816:1175973] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-07 10:50:35.820 ThaliTest[816:1175973] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-07 10:50:35.820 ThaliTest[816:1175,973] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

2016-03-07 10:50:35.821 ThaliTest[816:1175973] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B7764780-C267-424E-8191-4B64FD0884D3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


```

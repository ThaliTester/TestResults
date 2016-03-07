#### Test 61362366345141a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366345141a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/1F206B60-942F-4FD8-85EF-FFB260EB80E9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1F206B60-942F-4FD8-85EF-FFB260EB80E9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366345141a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366345141a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51563"
,(lldb)     command script import "/tmp/1F206B60-942F-4FD8-85EF-FFB260EB80E9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 15:36:39.052 ThaliTest[843:1207286] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8BA47937-E366-4E7C-A9BC-46DBA18E5BE4/Library/Cookies/Cookies.binarycookies
,2016-03-07 15:36:39.449 ThaliTest[843:1207286] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 15:36:39.450 ThaliTest[843:1207286] Multi-tasking -> Device: YES, App: YES
,2016-03-07 15:36:39.475 ThaliTest[843:1207286] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 15:36:41.596 ThaliTest[843:1207286] Using UIWebView
,2016-03-07 15:36:41.604 ThaliTest[843:1207286] [CDVTimer][handleopenurl] 0.441015ms
,2016-03-07 15:36:41.612 ThaliTest[843:1207286] [CDVTimer][intentandnavigationfilter] 8.042991ms
2016-03-07 15:36:41.613 ThaliTest[843:1207286] [CDVTimer][gesturehandler] 0.436962ms
2016-03-07 15:36:41.614 ThaliTest[843:1207286] [CDVTimer][TotalPluginStartup] 10.806978ms
,2016-03-07 15:36:48.647 ThaliTest[843:1207286] Resetting plugins due to page load.
,2016-03-07 15:36:52.512 ThaliTest[843:1207286] Finished load of: file:///var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/index.html
,2016-03-07 15:36:52.752 ThaliTest[843:1207286] JXcore Cordova plugin initializing
2016-03-07 15:36:52.754 ThaliTest[843:1207517] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 15:37:06.699 ThaliTest[843:1207517] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-07 15:37:06.700 ThaliTest[843:1207517] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-07 15:37:06.700 ThaliTest[843:1207517] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-07 15:37:06.701 ThaliTest[843:1207517] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/37000E3A-B028-4C72-8C9B-44F79D53C01A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


```

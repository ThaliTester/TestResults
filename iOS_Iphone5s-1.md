#### Test 625481247d7767b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A3D32631-E9CE-434B-96B8-57493A7A8437/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A3D32631-E9CE-434B-96B8-57493A7A8437/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49707"
,(lldb)     command script import "/tmp/A3D32631-E9CE-434B-96B8-57493A7A8437/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 15:00:49.678 ThaliTest[1481:2372065] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B21BB122-2362-4361-AA78-2D309FF82CD3/Library/Cookies/Cookies.binarycookies
,2016-03-15 15:00:49.998 ThaliTest[1481:2372065] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 15:00:49.999 ThaliTest[1481:2372065] Multi-tasking -> Device: YES, App: YES
,2016-03-15 15:00:50.020 ThaliTest[1481:2372065] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 15:00:51.879 ThaliTest[1481:2372065] Using UIWebView
,2016-03-15 15:00:51.887 ThaliTest[1481:2372065] [CDVTimer][handleopenurl] 0.468016ms
,2016-03-15 15:00:51.896 ThaliTest[1481:2372065] [CDVTimer][intentandnavigationfilter] 7.915974ms
2016-03-15 15:00:51.897 ThaliTest[1481:2372065] [CDVTimer][gesturehandler] 0.384986ms
2016-03-15 15:00:51.897 ThaliTest[1481:2372065] [CDVTimer][TotalPluginS,tartup] 10.664999ms
,2016-03-15 15:00:58.707 ThaliTest[1481:2372065] Resetting plugins due to page load.
,2016-03-15 15:01:02.646 ThaliTest[1481:2372065] Finished load of: file:///var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/index.html
,2016-03-15 15:01:02.834 ThaliTest[1481:2372065] JXcore Cordova plugin initializing
,2016-03-15 15:01:02.835 ThaliTest[1481:2372280] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 15:01:18.712 ThaliTest[1481:2372280] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-15 15:01:18.714 ThaliTest[1481:2372280] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 15:01:18.714 ThaliTest[1481:2372280] jxcore: didRegisterToNative networkChanged
,2016-03-15 15:01:18.715 ThaliTest[1481:2372280] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4C41840B-5255-43E3-BEEA-6C263DB46153/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

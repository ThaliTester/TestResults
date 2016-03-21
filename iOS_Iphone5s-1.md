#### Test 625481246a7d362_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246a7d362/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7C066FD5-1616-4F8B-B027-F45A7AC58385/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7C066FD5-1616-4F8B-B027-F45A7AC58385/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246a7d362/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246a7d362/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54373"
,(lldb)     command script import "/tmp/7C066FD5-1616-4F8B-B027-F45A7AC58385/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 15:48:34.366 ThaliTest[1928:3287971] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CF76BABC-B343-49A1-A48D-252571673377/Library/Cookies/Cookies.binarycookies
,2016-03-21 15:48:34.776 ThaliTest[1928:3287971] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 15:48:34.778 ThaliTest[1928:3287971] Multi-tasking -> Device: YES, App: YES
,2016-03-21 15:48:34.800 ThaliTest[1928:3287971] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 15:48:36.824 ThaliTest[1928:3287971] Using UIWebView
,2016-03-21 15:48:36.831 ThaliTest[1928:3287971] [CDVTimer][handleopenurl] 0.455976ms
,2016-03-21 15:48:36.840 ThaliTest[1928:3287971] [CDVTimer][intentandnavigationfilter] 7.930040ms
2016-03-21 15:48:36.840 ThaliTest[1928:3287971] [CDVTimer][gesturehandler] 0.361979ms
2016-03-21 15:48:36.841 ThaliTest[1928:3287971] [CDVTimer][TotalPluginS,tartup] 10.668039ms
,2016-03-21 15:48:44.117 ThaliTest[1928:3287971] Resetting plugins due to page load.
,2016-03-21 15:48:47.617 ThaliTest[1928:3287971] Finished load of: file:///var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/index.html
,2016-03-21 15:48:47.847 ThaliTest[1928:3287971] JXcore Cordova plugin initializing
2016-03-21 15:48:47.848 ThaliTest[1928:3288196] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 15:48:56.487 ThaliTest[1928:3288196] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 15:48:56.487 ThaliTest[1928:3288196] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 15:48:56.488 ThaliTest[1928:3,288196] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 15:48:56.490 ThaliTest[1928:3288196] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/69F2635B-0859-4E90-BDDF-B466D5096F4A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 15:49:03.502 ThaliTest[1928:3287971] THREAD WARNING: ['JXcore'] took '6642.699951' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

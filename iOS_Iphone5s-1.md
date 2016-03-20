#### Test 625481245382a4d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/63EC1586-CE2D-454A-9033-2BFD0C5AACF0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/63EC1586-CE2D-454A-9033-2BFD0C5AACF0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53227"
,(lldb)     command script import "/tmp/63EC1586-CE2D-454A-9033-2BFD0C5AACF0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-20 12:39:06.688 ThaliTest[1840:3113627] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ACD9B4DC-2D5C-4827-9FCF-D459596A8AD0/Library/Cookies/Cookies.binarycookies
,2016-03-20 12:39:07.083 ThaliTest[1840:3113627] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-20 12:39:07.084 ThaliTest[1840:3113627] Multi-tasking -> Device: YES, App: YES
,2016-03-20 12:39:07.106 ThaliTest[1840:3113627] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-20 12:39:08.771 ThaliTest[1840:3113627] Using UIWebView
,2016-03-20 12:39:08.779 ThaliTest[1840:3113627] [CDVTimer][handleopenurl] 0.505984ms
,2016-03-20 12:39:08.788 ThaliTest[1840:3113627] [CDVTimer][intentandnavigationfilter] 8.255005ms
2016-03-20 12:39:08.789 ThaliTest[1840:3113627] [CDVTimer][gesturehandler] 0.413001ms
2016-03-20 12:39:08.789 ThaliTest[1840:3113627] [CDVTimer][TotalPluginS,tartup] 11.099994ms
,2016-03-20 12:39:15.995 ThaliTest[1840:3113627] Resetting plugins due to page load.
,2016-03-20 12:39:20.082 ThaliTest[1840:3113627] Finished load of: file:///var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/index.html
,2016-03-20 12:39:20.332 ThaliTest[1840:3113627] JXcore Cordova plugin initializing
2016-03-20 12:39:20.333 ThaliTest[1840:3113847] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-20 12:39:28.945 ThaliTest[1840:3113847] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:39:28.945 ThaliTest[1840:3113847] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:39:28.946 ThaliTest[1840:3113847] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:39:28.949 ThaliTest[1840:3113847] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D2CDB0A-9D2E-4C3D-A5A3-507CC374F136/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-20 12:39:35.921 ThaliTest[1840:3113627] THREAD WARNING: ['JXcore'] took '6604.573975' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

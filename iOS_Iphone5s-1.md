#### Test 63680118f1433de_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63680118f1433de/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6798F39C-B5D8-4EB5-8A19-13AB2F1D42D3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6798F39C-B5D8-4EB5-8A19-13AB2F1D42D3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63680118f1433de/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63680118f1433de/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54866"
,(lldb)     command script import "/tmp/6798F39C-B5D8-4EB5-8A19-13AB2F1D42D3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-22 15:38:07.669 ThaliTest[2004:3439687] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A00E4F15-5CE3-4429-8045-03283693A7FE/Library/Cookies/Cookies.binarycookies
,2016-03-22 15:38:08.054 ThaliTest[2004:3439687] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-22 15:38:08.055 ThaliTest[2004:3439687] Multi-tasking -> Device: YES, App: YES
,2016-03-22 15:38:08.078 ThaliTest[2004:3439687] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-22 15:38:10.209 ThaliTest[2004:3439687] Using UIWebView
,2016-03-22 15:38:10.217 ThaliTest[2004:3439687] [CDVTimer][handleopenurl] 0.415981ms
,2016-03-22 15:38:10.226 ThaliTest[2004:3439687] [CDVTimer][intentandnavigationfilter] 7.973015ms
2016-03-22 15:38:10.227 ThaliTest[2004:3439687] [CDVTimer][gesturehandler] 0.449002ms
2016-03-22 15:38:10.227 ThaliTest[2004:3439687] [CDVTimer][TotalPluginStartup] 10.894001ms
,2016-03-22 15:38:17.854 ThaliTest[2004:3439687] Resetting plugins due to page load.
,2016-03-22 15:38:21.646 ThaliTest[2004:3439687] Finished load of: file:///var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/index.html
,2016-03-22 15:38:21.898 ThaliTest[2004:3439687] JXcore Cordova plugin initializing
,2016-03-22 15:38:22.073 ThaliTest[2004:3439908] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-22 15:38:30.583 ThaliTest[2004:3439908] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 15:38:30.584 ThaliTest[2004:3439908] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 15:38:30.584 ThaliTest[2004:3439908] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 15:38:30.587 ThaliTest[2004:3439908] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A5ABC4F0-81CD-42E1-99F9-88E2C1591796/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-22 15:38:37.562 ThaliTest[2004:3439687] THREAD WARNING: ['JXcore'] took '6602.962158' ms. Plugin should use a background thread.
,Reconnected to the test server
,Disconnected from the test server

```

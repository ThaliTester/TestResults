#### Test 639107046bb5f66_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639107046bb5f66/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BA66FE48-0987-4DB2-9372-54B07419CE61/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BA66FE48-0987-4DB2-9372-54B07419CE61/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639107046bb5f66/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639107046bb5f66/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55317"
,(lldb)     command script import "/tmp/BA66FE48-0987-4DB2-9372-54B07419CE61/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-23 17:54:09.712 ThaliTest[2108:3595516] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F62E00BA-EAAE-485E-81BE-64F068F01213/Library/Cookies/Cookies.binarycookies
,2016-03-23 17:54:10.122 ThaliTest[2108:3595516] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-23 17:54:10.123 ThaliTest[2108:3595516] Multi-tasking -> Device: YES, App: YES
,2016-03-23 17:54:10.142 ThaliTest[2108:3595516] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-23 17:54:12.227 ThaliTest[2108:3595516] Using UIWebView
,2016-03-23 17:54:12.237 ThaliTest[2108:3595516] [CDVTimer][handleopenurl] 0.373006ms
,2016-03-23 17:54:12.244 ThaliTest[2108:3595516] [CDVTimer][intentandnavigationfilter] 7.085979ms
,2016-03-23 17:54:12.245 ThaliTest[2108:3595516] [CDVTimer][gesturehandler] 0.343025ms
,2016-03-23 17:54:12.246 ThaliTest[2108:3595516] [CDVTimer][TotalPluginStartup] 9.404004ms
,2016-03-23 17:54:19.706 ThaliTest[2108:3595516] Resetting plugins due to page load.
,2016-03-23 17:54:23.416 ThaliTest[2108:3595516] Finished load of: file:///var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/index.html
,2016-03-23 17:54:23.633 ThaliTest[2108:3595516] JXcore Cordova plugin initializing
,2016-03-23 17:54:23.634 ThaliTest[2108:3595731] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-23 17:54:30.056 ThaliTest[2108:3595731] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 17:54:30.056 ThaliTest[2108:3595731] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 17:54:30.056 ThaliTest[2108:3595731] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 17:54:30.058 ThaliTest[2108:3595731] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A798C2F2-DA8A-430B-A0CB-DB1C69A129F4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-23 17:54:35.251 ThaliTest[2108:3595516] THREAD WARNING: ['JXcore'] took '4920.019043' ms. Plugin should use a background thread.

```

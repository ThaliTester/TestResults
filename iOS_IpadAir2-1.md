#### Test 6391070405f2a33_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B10F30C1-0DA8-4325-B125-B7AF36D723E5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B10F30C1-0DA8-4325-B125-B7AF36D723E5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55612"
,(lldb)     command script import "/tmp/B10F30C1-0DA8-4325-B125-B7AF36D723E5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 15:26:57.882 ThaliTest[2154:3735826] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FFE8C525-16CD-4D7F-8098-4913D4E305CD/Library/Cookies/Cookies.binarycookies
,2016-03-24 15:26:58.241 ThaliTest[2154:3735826] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 15:26:58.242 ThaliTest[2154:3735826] Multi-tasking -> Device: YES, App: YES
,2016-03-24 15:26:58.257 ThaliTest[2154:3735826] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 15:27:00.414 ThaliTest[2154:3735826] Using UIWebView
,2016-03-24 15:27:00.420 ThaliTest[2154:3735826] [CDVTimer][handleopenurl] 0.419974ms
,2016-03-24 15:27:00.428 ThaliTest[2154:3735826] [CDVTimer][intentandnavigationfilter] 7.314026ms
,2016-03-24 15:27:00.429 ThaliTest[2154:3735826] [CDVTimer][gesturehandler] 0.492990ms
,2016-03-24 15:27:00.429 ThaliTest[2154:3735826] [CDVTimer][TotalPluginStartup] 10.040045ms
,2016-03-24 15:27:08.748 ThaliTest[2154:3735826] Resetting plugins due to page load.
,2016-03-24 15:27:12.861 ThaliTest[2154:3735826] Finished load of: file:///var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/index.html
,2016-03-24 15:27:13.082 ThaliTest[2154:3735826] JXcore Cordova plugin initializing
,2016-03-24 15:27:13.083 ThaliTest[2154:3736067] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-24 15:27:19.577 ThaliTest[2154:3736067] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 15:27:19.577 ThaliTest[2154:3736067] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-24 15:27:19.578 ThaliTest[2154:3736067] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 15:27:19.579 ThaliTest[2154:3736067] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B4D25BF-BBC2-4EDA-88B5-78ED73051707/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-24 15:27:24.799 ThaliTest[2154:3735826] THREAD WARNING: ['JXcore'] took '4943.145020' ms. Plugin should use a background thread.

```

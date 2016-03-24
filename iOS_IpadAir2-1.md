#### Test 639107046ed3de5_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1342CD5A-5867-47A0-9D88-6AB5E55AC959/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1342CD5A-5867-47A0-9D88-6AB5E55AC959/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639107046ed3de5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55678"
,(lldb)     command script import "/tmp/1342CD5A-5867-47A0-9D88-6AB5E55AC959/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 16:43:46.108 ThaliTest[2163:3744764] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/87B7DAA3-70DB-4780-B4E2-9C70EF0FA4B2/Library/Cookies/Cookies.binarycookies
,2016-03-24 16:43:46.527 ThaliTest[2163:3744764] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 16:43:46.528 ThaliTest[2163:3744764] Multi-tasking -> Device: YES, App: YES
,2016-03-24 16:43:46.547 ThaliTest[2163:3744764] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 16:43:48.949 ThaliTest[2163:3744764] Using UIWebView
,2016-03-24 16:43:48.955 ThaliTest[2163:3744764] [CDVTimer][handleopenurl] 0.409007ms
,2016-03-24 16:43:48.962 ThaliTest[2163:3744764] [CDVTimer][intentandnavigationfilter] 6.588995ms
,2016-03-24 16:43:48.963 ThaliTest[2163:3744764] [CDVTimer][gesturehandler] 0.315011ms
,2016-03-24 16:43:48.964 ThaliTest[2163:3744764] [CDVTimer][TotalPluginStartup] 8.949041ms
,2016-03-24 16:43:57.273 ThaliTest[2163:3744764] Resetting plugins due to page load.
,2016-03-24 16:44:01.536 ThaliTest[2163:3744764] Finished load of: file:///var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/index.html
,2016-03-24 16:44:01.691 ThaliTest[2163:3744764] JXcore Cordova plugin initializing
,2016-03-24 16:44:01.692 ThaliTest[2163:3744987] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 16:44:08.119 ThaliTest[2163:3744987] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 16:44:08.120 ThaliTest[2163:3744987] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 16:44:08.120 ThaliTest[2163:3744987] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 16:44:08.121 ThaliTest[2163:3744987] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7AEC705F-6571-4E8E-B02C-92DCEFE8A0CF/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-24 16:44:13.338 ThaliTest[2163:3744764] THREAD WARNING: ['JXcore'] took '4942.773926' ms. Plugin should use a background thread.

```

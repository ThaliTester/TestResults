#### Test 639808773799dbd_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639808773799dbd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A947B002-6771-4356-BE6C-FE6777355DFE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A947B002-6771-4356-BE6C-FE6777355DFE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639808773799dbd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639808773799dbd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56026"
,(lldb)     command script import "/tmp/A947B002-6771-4356-BE6C-FE6777355DFE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 22:48:22.912 ThaliTest[2207:3790119] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F7474E10-238C-4325-8A1D-16E88ED35FF2/Library/Cookies/Cookies.binarycookies
,2016-03-24 22:48:23.257 ThaliTest[2207:3790119] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 22:48:23.258 ThaliTest[2207:3790119] Multi-tasking -> Device: YES, App: YES
,2016-03-24 22:48:23.273 ThaliTest[2207:3790119] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 22:48:25.377 ThaliTest[2207:3790119] Using UIWebView
,2016-03-24 22:48:25.386 ThaliTest[2207:3790119] [CDVTimer][handleopenurl] 0.361025ms
,2016-03-24 22:48:25.394 ThaliTest[2207:3790119] [CDVTimer][intentandnavigationfilter] 7.178009ms
,2016-03-24 22:48:25.395 ThaliTest[2207:3790119] [CDVTimer][gesturehandler] 0.328004ms
2016-03-24 22:48:25.395 ThaliTest[2207:3790119] [CDVTimer][TotalPluginStartup] 9.474993ms
,2016-03-24 22:48:33.652 ThaliTest[2207:3790119] Resetting plugins due to page load.
,2016-03-24 22:48:37.788 ThaliTest[2207:3790119] Finished load of: file:///var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/index.html
,2016-03-24 22:48:38.012 ThaliTest[2207:3790119] JXcore Cordova plugin initializing
,2016-03-24 22:48:38.013 ThaliTest[2207:3790371] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 22:48:44.545 ThaliTest[2207:3790371] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 22:48:44.545 ThaliTest[2207:3790371] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 22:48:44.545 ThaliTest[2207:3790371] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 22:48:44.547 ThaliTest[2207:3790371] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DCC8B940-0518-4F2A-8730-42AFA9DBF630/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-24 22:48:49.771 ThaliTest[2207:3790119] THREAD WARNING: ['JXcore'] took '4949.766113' ms. Plugin should use a background thread.

```

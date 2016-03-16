#### Test 62509094c147163_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094c147163/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F58D545E-4C91-479B-8534-9CB183488E0B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F58D545E-4C91-479B-8534-9CB183488E0B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094c147163/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094c147163/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50224"
,(lldb)     command script import "/tmp/F58D545E-4C91-479B-8534-9CB183488E0B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 08:33:59.927 ThaliTest[1565:2477560] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/05125BC8-FB25-41E5-9A0D-17FAE122C286/Library/Cookies/Cookies.binarycookies
,2016-03-16 08:34:00.255 ThaliTest[1565:2477560] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 08:34:00.256 ThaliTest[1565:2477560] Multi-tasking -> Device: YES, App: YES
,2016-03-16 08:34:00.273 ThaliTest[1565:2477560] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 08:34:01.949 ThaliTest[1565:2477560] Using UIWebView
,2016-03-16 08:34:01.956 ThaliTest[1565:2477560] [CDVTimer][handleopenurl] 0.537992ms
,2016-03-16 08:34:01.964 ThaliTest[1565:2477560] [CDVTimer][intentandnavigationfilter] 7.453024ms
,2016-03-16 08:34:01.965 ThaliTest[1565:2477560] [CDVTimer][gesturehandler] 0.352025ms
,2016-03-16 08:34:01.965 ThaliTest[1565:2477560] [CDVTimer][TotalPluginStartup] 10.351002ms
,2016-03-16 08:34:08.823 ThaliTest[1565:2477560] Resetting plugins due to page load.
,2016-03-16 08:34:12.100 ThaliTest[1565:2477560] Finished load of: file:///var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/index.html
,2016-03-16 08:34:12.303 ThaliTest[1565:2477560] JXcore Cordova plugin initializing
,2016-03-16 08:34:12.304 ThaliTest[1565:2477779] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-16 08:34:15.721 ThaliTest[1565:2477779] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-16 08:34:15.721 ThaliTest[1565:2477779] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-16 08:34:15.722 ThaliTest[1565:2477779] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-16 08:34:15.724 ThaliTest[1565:2477779] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2322A3B3-4397-4374-BA7C-DA2036337909/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-16 08:34:23.044 ThaliTest[1565:2477560] THREAD WARNING: ['JXcore'] took '5605.361084' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

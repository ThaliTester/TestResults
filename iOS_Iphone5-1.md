#### Test 62509094b685d58_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/522FD1A1-392C-40AC-841B-D503C609FA30/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/522FD1A1-392C-40AC-841B-D503C609FA30/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51977"
,(lldb)     command script import "/tmp/522FD1A1-392C-40AC-841B-D503C609FA30/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 12:27:10.689 ThaliTest[1266:2797914] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/21B7D478-418F-4ED4-B600-5B45780634AD/Library/Cookies/Cookies.binarycookies
,2016-03-17 12:27:11.156 ThaliTest[1266:2797914] Apache Cordova native platform version 4.0.1 is starting.
2016-03-17 12:27:11.157 ThaliTest[1266:2797914] Multi-tasking -> Device: YES, App: YES
,2016-03-17 12:27:11.177 ThaliTest[1266:2797914] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 12:27:13.086 ThaliTest[1266:2797914] Using UIWebView
,2016-03-17 12:27:13.091 ThaliTest[1266:2797914] [CDVTimer][handleopenurl] 0.306010ms
,2016-03-17 12:27:13.096 ThaliTest[1266:2797914] [CDVTimer][intentandnavigationfilter] 5.169988ms
2016-03-17 12:27:13.097 ThaliTest[1266:2797914] [CDVTimer][gesturehandler] 0.258982ms
2016-03-17 12:27:13.097 ThaliTest[1266:2797914] [CDVTimer][TotalPluginStartup] 6.790996ms
,2016-03-17 12:27:21.039 ThaliTest[1266:2797914] Resetting plugins due to page load.
,2016-03-17 12:27:24.294 ThaliTest[1266:2797914] Finished load of: file:///var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/index.html
,2016-03-17 12:27:24.513 ThaliTest[1266:2797914] JXcore Cordova plugin initializing
,2016-03-17 12:27:24.515 ThaliTest[1266:2798095] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 12:27:34.380 ThaliTest[1266:2798095] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 12:27:34.381 ThaliTest[1266:2798095] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-17 12:27:34.381 ThaliTest[1266:2798095] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 12:27:34.387 ThaliTest[1266:2798095] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8947C8BD-6744-4DDA-9074-0D766FF6F18A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 12:27:54.698 ThaliTest[1266:2797914] THREAD WARNING: ['JXcore'] took '14687.327637' ms. Plugin should use a background thread.
,2016-03-17 12:27:54.699 ThaliTest[1266:2798054] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

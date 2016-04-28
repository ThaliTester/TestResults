#### Test 68102130b92179b_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/68102130b92179b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/E565197C-C9A8-4E32-9931-916524751BF9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/E565197C-C9A8-4E32-9931-916524751BF9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/68102130b92179b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/68102130b92179b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54937"
,(lldb)     command script import "/tmp/E565197C-C9A8-4E32-9931-916524751BF9/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-28 10:51:09.037 ThaliTest[2789:9261905] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BF074861-C7B0-419C-87C5-4E9075B94F47/Library/Cookies/Cookies.binarycookies
,2016-04-28 10:51:09.592 ThaliTest[2789:9261905] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-28 10:51:09.594 ThaliTest[2789:9261905] Multi-tasking -> Device: YES, App: YES
,2016-04-28 10:51:09.615 ThaliTest[2789:9261905] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-28 10:51:11.933 ThaliTest[2789:9261905] Using UIWebView
,2016-04-28 10:51:11.938 ThaliTest[2789:9261905] [CDVTimer][handleopenurl] 0.340998ms
,2016-04-28 10:51:11.944 ThaliTest[2789:9261905] [CDVTimer][intentandnavigationfilter] 5.223989ms
2016-04-28 10:51:11.944 ThaliTest[2789:9261905] [CDVTimer][gesturehandler] 0.275016ms
2016-04-28 10:51:11.944 ThaliTest[2789:9261905] [CDVTimer][TotalPluginStartup] 6.987035ms
,2016-04-28 10:51:21.057 ThaliTest[2789:9261905] Resetting plugins due to page load.
,2016-04-28 10:51:24.737 ThaliTest[2789:9261905] Finished load of: file:///var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/index.html
,2016-04-28 10:51:24.942 ThaliTest[2789:9261905] JXcore Cordova plugin initializing
,2016-04-28 10:51:24.946 ThaliTest[2789:9262096] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-28 10:51:41.706 ThaliTest[2789:9262096] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-28 10:51:41.708 ThaliTest[2789:9262096] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-28 10:51:41.709 ThaliTest[2789:9262096] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-28 10:51:41.712 ThaliTest[2789:9262096] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1407EBD4-CB49-43B2-8381-56D33AFB2FBA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-28 10:51:55.396 ThaliTest[2789:9261905] THREAD WARNING: ['JXcore'] took '12984.394043' ms. Plugin should use a background thread.
,2016-04-28 10:51:55.398 ThaliTest[2789:9262047] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode

```

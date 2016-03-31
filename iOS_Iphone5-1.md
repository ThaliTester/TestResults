#### Test 646138038d447f5_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/D10072D1-0358-48DF-812A-85A95B1D27F5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D10072D1-0358-48DF-812A-85A95B1D27F5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646138038d447f5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49571"
,(lldb)     command script import "/tmp/D10072D1-0358-48DF-812A-85A95B1D27F5/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 09:40:48.729 ThaliTest[1913:4908300] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1A586FC4-87CE-488B-8BC4-EBAF6EAFBC05/Library/Cookies/Cookies.binarycookies
,2016-03-31 09:40:49.044 ThaliTest[1913:4908300] Apache Cordova native platform version 4.1.0 is starting.
2016-03-31 09:40:49.045 ThaliTest[1913:4908300] Multi-tasking -> Device: YES, App: YES
,2016-03-31 09:40:49.063 ThaliTest[1913:4908300] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 09:40:50.167 ThaliTest[1913:4908300] Using UIWebView
,2016-03-31 09:40:50.174 ThaliTest[1913:4908300] [CDVTimer][handleopenurl] 0.245988ms
,2016-03-31 09:40:50.178 ThaliTest[1913:4908300] [CDVTimer][intentandnavigationfilter] 4.525006ms
2016-03-31 09:40:50.179 ThaliTest[1913:4908300] [CDVTimer][gesturehandler] 0.204027ms
2016-03-31 09:40:50.179 ThaliTest[1913:4908300] [CDVTimer][TotalPluginStartup] 5.807042ms
,2016-03-31 09:40:54.811 ThaliTest[1913:4908300] Resetting plugins due to page load.
,2016-03-31 09:40:56.836 ThaliTest[1913:4908300] Finished load of: file:///var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/index.html
,2016-03-31 09:40:57.023 ThaliTest[1913:4908300] JXcore Cordova plugin initializing
2016-03-31 09:40:57.025 ThaliTest[1913:4908427] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 09:41:11.224 ThaliTest[1913:4908427] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 09:41:11.225 ThaliTest[1913:4908427] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 09:41:11.225 ThaliTest[1913:4,908427] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 09:41:11.228 ThaliTest[1913:4908427] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2B5DD29A-6D68-440F-B3E5-B29BDC820A15/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-31 09:41:22.950 ThaliTest[1913:4908300] THREAD WARNING: ['JXcore'] took '11099.683838' ms. Plugin should use a background thread.
2016-03-31 09:41:22.951 ThaliTest[1913:4908395] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePol,icyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,Connected to the test server

```

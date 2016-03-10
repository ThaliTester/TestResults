#### Test 62328822054c831_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62328822054c831/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/F7409BA5-7570-4744-BC3A-31BF47468FB6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F7409BA5-7570-4744-BC3A-31BF47468FB6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62328822054c831/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62328822054c831/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51221"
,(lldb)     command script import "/tmp/F7409BA5-7570-4744-BC3A-31BF47468FB6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 21:36:57.811 ThaliTest[1113:1698843] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DC8FFDA8-85EE-43B0-AC34-27F1E08AF6E8/Library/Cookies/Cookies.binarycookies
,2016-03-10 21:36:58.248 ThaliTest[1113:1698843] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 21:36:58.249 ThaliTest[1113:1698843] Multi-tasking -> Device: YES, App: YES
,2016-03-10 21:36:58.275 ThaliTest[1113:1698843] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 21:37:00.079 ThaliTest[1113:1698843] Using UIWebView
,2016-03-10 21:37:00.085 ThaliTest[1113:1698843] [CDVTimer][handleopenurl] 0.279009ms
,2016-03-10 21:37:00.089 ThaliTest[1113:1698843] [CDVTimer][intentandnavigationfilter] 4.001021ms
2016-03-10 21:37:00.089 ThaliTest[1113:1698843] [CDVTimer][gesturehandler] 0.192046ms
2016-03-10 21:37:00.090 ThaliTest[1113:1698843] [CDVTimer][TotalPluginS,tartup] 5.631983ms
,2016-03-10 21:37:06.727 ThaliTest[1113:1698843] Resetting plugins due to page load.
,2016-03-10 21:37:10.430 ThaliTest[1113:1698843] Finished load of: file:///var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/index.html
,2016-03-10 21:37:10.675 ThaliTest[1113:1698843] JXcore Cordova plugin initializing
,2016-03-10 21:37:10.677 ThaliTest[1113:1699063] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 21:37:19.459 ThaliTest[1113:1699063] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 21:37:19.460 ThaliTest[1113:1699063] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 21:37:19.460 ThaliTest[1113:1699063] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 21:37:19.463 ThaliTest[1113:1699063] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/67C0CB48-0B03-4A14-B6B6-18EB5086BAEB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```

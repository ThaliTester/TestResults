#### Test 896247969cd5996_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247969cd5996/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A997F2BE-7A79-4B23-AC7D-A11D5B18DC97/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A997F2BE-7A79-4B23-AC7D-A11D5B18DC97/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247969cd5996/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247969cd5996/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/80FFC9AB-8115-4BD3-8440-CD8C1EFF70D7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55122"
,(lldb)     command script import "/tmp/A997F2BE-7A79-4B23-AC7D-A11D5B18DC97/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-10 12:15:54.251 ThaliTest[5478:13801012] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D9A3DEAE-9B5C-4498-8922-F6A1B6A2B35A/Library/Cookies/Cookies.binarycookies
,2016-11-10 12:15:54.312 ThaliTest[5478:13801012] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-10 12:15:54.313 ThaliTest[5478:13801012] Multi-tasking -> Device: YES, App: YES
,2016-11-10 12:15:54.334 ThaliTest[5478:13801012] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 12:15:55.122 ThaliTest[5478:13801012] Using UIWebView
2016-11-10 12:15:55.125 ThaliTest[5478:13801012] [CDVTimer][handleopenurl] 0.161052ms
,2016-11-10 12:15:55.130 ThaliTest[5478:13801012] [CDVTimer][intentandnavigationfilter] 3.282011ms
2016-11-10 12:15:55.130 ThaliTest[5478:13801012] [CDVTimer][gesturehandler] 0.132978ms
2016-11-10 12:15:55.130 ThaliTest[5478:13801012] [CDVTimer][TotalPluginStartup] 5.432010ms
,2016-11-10 12:15:58.160 ThaliTest[5478:13801012] Resetting plugins due to page load.
,2016-11-10 12:15:59.793 ThaliTest[5478:13801012] Finished load of: file:///var/mobile/Containers/Bundle/Application/80FFC9AB-8115-4BD3-8440-CD8C1EFF70D7/ThaliTest.app/www/index.html
,2016-11-10 12:15:59.802 ThaliTest[5478:13801012] JXcore Cordova plugin initializing
,2016-11-10 12:15:59.803 ThaliTest[5478:13801160] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 11:16:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-10 11:16:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-10 11:16:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-10 11:16:12 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2016-11-10 11:16:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,failed - Unexpected connect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 40
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-10 11:16:36 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
,Total duration:  24.00018399953842
,Failed to execute UT.
,2016-11-10 11:16:36 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

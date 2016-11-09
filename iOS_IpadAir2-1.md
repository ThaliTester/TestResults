#### Test 8962479676fe425_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8962479676fe425/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/FD5AEA28-F615-4E6E-B921-CF92A4FDF637/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/FD5AEA28-F615-4E6E-B921-CF92A4FDF637/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8962479676fe425/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8962479676fe425/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0AF4E75A-AE0F-443A-94CD-2361CE41D626/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57532"
,(lldb)     command script import "/tmp/FD5AEA28-F615-4E6E-B921-CF92A4FDF637/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-09 10:33:17.855 ThaliTest[5286:11365615] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2DE111DA-CC44-4F1E-B231-676C6D08BDFF/Library/Cookies/Cookies.binarycookies
,2016-11-09 10:33:18.245 ThaliTest[5286:11365615] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-09 10:33:18.247 ThaliTest[5286:11365615] Multi-tasking -> Device: YES, App: YES
,2016-11-09 10:33:18.269 ThaliTest[5286:11365615] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 10:33:20.387 ThaliTest[5286:11365615] Using UIWebView
,2016-11-09 10:33:20.396 ThaliTest[5286:11365615] [CDVTimer][handleopenurl] 0.369012ms
,2016-11-09 10:33:20.404 ThaliTest[5286:11365615] [CDVTimer][intentandnavigationfilter] 7.330000ms
,2016-11-09 10:33:20.405 ThaliTest[5286:11365615] [CDVTimer][gesturehandler] 0.365973ms
2016-11-09 10:33:20.405 ThaliTest[5286:11365615] [CDVTimer][TotalPluginStartup] 9.689033ms
,2016-11-09 10:33:27.763 ThaliTest[5286:11365615] Resetting plugins due to page load.
,2016-11-09 10:33:31.430 ThaliTest[5286:11365615] Finished load of: file:///var/mobile/Containers/Bundle/Application/0AF4E75A-AE0F-443A-94CD-2361CE41D626/ThaliTest.app/www/index.html
,2016-11-09 10:33:31.708 ThaliTest[5286:11365615] JXcore Cordova plugin initializing
,2016-11-09 10:33:31.708 ThaliTest[5286:11365914] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 09:33:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-09 09:33:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 09:33:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-09 09:33:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-09 09:33:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x129ee0710> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-09 09:34:16 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  35.45959001779556
,Failed to execute UT.
,2016-11-09 09:34:16 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

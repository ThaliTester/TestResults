#### Test 8617437951c5913_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CC08D8CF-2A7B-4F81-902A-513D4A110038/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CC08D8CF-2A7B-4F81-902A-513D4A110038/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DEBC9007-02BA-4B8A-8A07-6CEFB563EA02/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60381"
,(lldb)     command script import "/tmp/CC08D8CF-2A7B-4F81-902A-513D4A110038/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 16:52:41.296 ThaliTest[2953:6000914] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/01BB9674-43A9-41A1-95D6-3BDDAE95AD52/Library/Cookies/Cookies.binarycookies
,2016-09-22 16:52:41.419 ThaliTest[2953:6000914] Apache Cordova native platform version 4.2.1 is starting.
2016-09-22 16:52:41.420 ThaliTest[2953:6000914] Multi-tasking -> Device: YES, App: YES
,2016-09-22 16:52:41.442 ThaliTest[2953:6000914] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 16:52:42.966 ThaliTest[2953:6000914] Using UIWebView
,2016-09-22 16:52:42.974 ThaliTest[2953:6000914] [CDVTimer][handleopenurl] 0.450015ms
,2016-09-22 16:52:42.983 ThaliTest[2953:6000914] [CDVTimer][intentandnavigationfilter] 8.244991ms
2016-09-22 16:52:42.984 ThaliTest[2953:6000914] [CDVTimer][gesturehandler] 0.361025ms
2016-09-22 16:52:42.984 ThaliTest[2953:6000914] [CDVTimer][TotalPluginS,tartup] 10.863960ms
,2016-09-22 16:52:48.545 ThaliTest[2953:6000914] Resetting plugins due to page load.
,2016-09-22 16:52:51.918 ThaliTest[2953:6000914] Finished load of: file:///var/mobile/Containers/Bundle/Application/DEBC9007-02BA-4B8A-8A07-6CEFB563EA02/ThaliTest.app/www/index.html
,2016-09-22 16:52:52.215 ThaliTest[2953:6000914] JXcore Cordova plugin initializing
,2016-09-22 16:52:52.216 ThaliTest[2953:6001160] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x1588164c0>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
XCTAssertNotEqual failed: ("Optional(1)") is equal to (,"Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugi,ns/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("30779DA6-3D20-4E7B-940C-008583CFC7F2")
,nil
,nil
,Optional("F8842AF8-62B3-4854-88BC-A921638568A3")
,Optional("003D1163-48F1-4218-8F3B-7C81B17E2682")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-22 16:53:15.855 ThaliTest[2953:6000914] BTM: attaching to BTServer
,2016-09-22 16:53:16.545 ThaliTest[2953:6000914] BTM: local device power state changed
2016-09-22 16:53:16.563 ThaliTest[2953:6000914] BTM: power is now on
,2016-09-22 16:53:21.303 ThaliTest[2953:6000914] BTM: local device power state changed
2016-09-22 16:53:21.304 ThaliTest[2953:6000914] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  53
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  20.22837001085281
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

#### Test 861743796628be0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B74EE414-BDD6-40CF-9CC4-896359BA8FB3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B74EE414-BDD6-40CF-9CC4-896359BA8FB3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/69F52AFA-9892-4FE8-9AEA-A2E68B56D346/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58210"
,(lldb)     command script import "/tmp/B74EE414-BDD6-40CF-9CC4-896359BA8FB3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 12:39:31.000 ThaliTest[3056:6139767] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E7A7AC00-22CD-4ECA-8FB3-77620E107062/Library/Cookies/Cookies.binarycookies
,2016-09-23 12:39:31.107 ThaliTest[3056:6139767] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 12:39:31.109 ThaliTest[3056:6139767] Multi-tasking -> Device: YES, App: YES
,2016-09-23 12:39:31.130 ThaliTest[3056:6139767] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 12:39:32.667 ThaliTest[3056:6139767] Using UIWebView
,2016-09-23 12:39:32.678 ThaliTest[3056:6139767] [CDVTimer][handleopenurl] 0.465989ms
,2016-09-23 12:39:32.687 ThaliTest[3056:6139767] [CDVTimer][intentandnavigationfilter] 8.202970ms
2016-09-23 12:39:32.688 ThaliTest[3056:6139767] [CDVTimer][gesturehandler] 0.383019ms
2016-09-23 12:39:32.689 ThaliTest[3056:6139767] [CDVTimer][TotalPluginStartup] 11.084020ms
,2016-09-23 12:39:38.433 ThaliTest[3056:6139767] Resetting plugins due to page load.
,2016-09-23 12:39:41.929 ThaliTest[3056:6139767] Finished load of: file:///var/mobile/Containers/Bundle/Application/69F52AFA-9892-4FE8-9AEA-A2E68B56D346/ThaliTest.app/www/index.html
,2016-09-23 12:39:42.202 ThaliTest[3056:6139767] JXcore Cordova plugin initializing
,2016-09-23 12:39:42.203 ThaliTest[3056:6140002] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1602327c0>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("DF9EB8CB-2979-436D-8766-22D0279A9FB8")
,nil
,nil
,Optional("C73A20ED-EF9F-4A70-A994-6DE8D1E6E54E")
,Optional("1935B757-5F7B-40B2-AFEE-45EA37587E2E")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 12:40:06.163 ThaliTest[3056:6139767] BTM: attaching to BTServer
,2016-09-23 12:40:06.848 ThaliTest[3056:6139767] BTM: local device power state changed
2016-09-23 12:40:06.849 ThaliTest[3056:6139767] BTM: power is now on
,2016-09-23 12:40:11.570 ThaliTest[3056:6139767] BTM: local device power state changed
2016-09-23 12:40:11.570 ThaliTest[3056:6139767] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  53
Number of failed tests:  3
Number of ignored tests:  0
,Total duration:  20.54693496227264
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```

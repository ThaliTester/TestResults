#### Test 829140738877506_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E0B9AC19-1A0B-46EE-86D3-EFCA21D8BB0E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E0B9AC19-1A0B-46EE-86D3-EFCA21D8BB0E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1FF5C98D-8E0A-4259-9F2C-0211EBEEB2AA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52904"
,(lldb)     command script import "/tmp/E0B9AC19-1A0B-46EE-86D3-EFCA21D8BB0E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 14:02:44.472 ThaliTest[2363:4892566] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/745819FF-0C09-42DA-A63E-E2D26F99DCB3/Library/Cookies/Cookies.binarycookies
,2016-09-15 14:02:44.592 ThaliTest[2363:4892566] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 14:02:44.594 ThaliTest[2363:4892566] Multi-tasking -> Device: YES, App: YES
,2016-09-15 14:02:44.619 ThaliTest[2363:4892566] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 14:02:46.142 ThaliTest[2363:4892566] Using UIWebView
,2016-09-15 14:02:46.153 ThaliTest[2363:4892566] [CDVTimer][handleopenurl] 0.515044ms
,2016-09-15 14:02:46.162 ThaliTest[2363:4892566] [CDVTimer][intentandnavigationfilter] 8.307993ms
2016-09-15 14:02:46.163 ThaliTest[2363:4892566] [CDVTimer][gesturehandler] 0.363946ms
2016-09-15 14:02:46.163 ThaliTest[2363:4892566] [CDVTimer][TotalPluginS,tartup] 11.052012ms
,2016-09-15 14:02:51.999 ThaliTest[2363:4892566] Resetting plugins due to page load.
,2016-09-15 14:02:55.322 ThaliTest[2363:4892566] Finished load of: file:///var/mobile/Containers/Bundle/Application/1FF5C98D-8E0A-4259-9F2C-0211EBEEB2AA/ThaliTest.app/www/index.html
,2016-09-15 14:02:55.623 ThaliTest[2363:4892566] JXcore Cordova plugin initializing
,2016-09-15 14:02:55.625 ThaliTest[2363:4892770] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x139870430>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-15 14:03:16.019 ThaliTest[2363:4892566] BTM: attaching to BTServer
,2016-09-15 14:03:17.121 ThaliTest[2363:4892566] BTM: local device power state changed
2016-09-15 14:03:17.121 ThaliTest[2363:4892566] BTM: power is now off
,2016-09-15 14:03:17.809 ThaliTest[2363:4892566] BTM: local device power state changed
2016-09-15 14:03:17.810 ThaliTest[2363:4892566] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  13.20662403106689
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```

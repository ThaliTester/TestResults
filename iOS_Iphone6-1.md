#### Test 8326889373d8814_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889373d8814/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/61E04649-6276-46BB-AC17-86A82B99DD67/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/61E04649-6276-46BB-AC17-86A82B99DD67/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889373d8814/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889373d8814/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2478EE21-CDB3-4692-AEDB-396E633063BD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61469"
,(lldb)     command script import "/tmp/61E04649-6276-46BB-AC17-86A82B99DD67/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 16:42:20.898 ThaliTest[1344:1898390] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FD8DB0AF-B71F-4254-B281-53A2FB83DAD2/Library/Cookies/Cookies.binarycookies
,2016-09-23 16:42:20.971 ThaliTest[1344:1898390] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 16:42:20.974 ThaliTest[1344:1898390] Multi-tasking -> Device: YES, App: YES
,2016-09-23 16:42:20.992 ThaliTest[1344:1898390] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 16:42:21.464 ThaliTest[1344:1898390] Using UIWebView
,2016-09-23 16:42:21.474 ThaliTest[1344:1898390] [CDVTimer][handleopenurl] 0.378966ms
,2016-09-23 16:42:21.482 ThaliTest[1344:1898390] [CDVTimer][intentandnavigationfilter] 7.638037ms
2016-09-23 16:42:21.483 ThaliTest[1344:1898390] [CDVTimer][gesturehandler] 0.291049ms
2016-09-23 16:42:21.484 ThaliTest[1344:1898390] [CDVTimer][TotalPluginS,tartup] 9.988010ms
,2016-09-23 16:42:27.242 ThaliTest[1344:1898390] Resetting plugins due to page load.
,2016-09-23 16:42:27.610 ThaliTest[1344:1898390] Finished load of: file:///var/containers/Bundle/Application/2478EE21-CDB3-4692-AEDB-396E633063BD/ThaliTest.app/www/index.html
,2016-09-23 16:42:27.940 ThaliTest[1344:1898390] JXcore Cordova plugin initializing
,2016-09-23 16:42:27.942 ThaliTest[1344:1898564] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x14934f030>
,Optional("D9D9A9F7-8CDC-438F-95CB-850DFDBEFC7B")
,nil
,nil
,Optional("F696B1F1-FDA3-45C6-A116-EDB0F78163F3")
,Optional("28F1EDA8-5083-4D7B-A2EC-B318CEF9D02C")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
,Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.34010499715805
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

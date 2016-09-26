#### Test 865221020889ce9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/42FD58BB-A5F5-457D-A4ED-B64B8B8521F5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/42FD58BB-A5F5-457D-A4ED-B64B8B8521F5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D92BE563-E433-498B-953C-BA9570DC7414/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59274"
,(lldb)     command script import "/tmp/42FD58BB-A5F5-457D-A4ED-B64B8B8521F5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 16:31:36.003 ThaliTest[3263:6642808] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/347BFD2B-2842-4313-A1A4-6BEB059819B5/Library/Cookies/Cookies.binarycookies
,2016-09-26 16:31:36.122 ThaliTest[3263:6642808] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 16:31:36.124 ThaliTest[3263:6642808] Multi-tasking -> Device: YES, App: YES
,2016-09-26 16:31:36.149 ThaliTest[3263:6642808] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 16:31:37.722 ThaliTest[3263:6642808] Using UIWebView
,2016-09-26 16:31:37.730 ThaliTest[3263:6642808] [CDVTimer][handleopenurl] 0.478983ms
,2016-09-26 16:31:37.741 ThaliTest[3263:6642808] [CDVTimer][intentandnavigationfilter] 9.913981ms
2016-09-26 16:31:37.742 ThaliTest[3263:6642808] [CDVTimer][gesturehandler] 0.375986ms
2016-09-26 16:31:37.742 ThaliTest[3263:6642808] [CDVTimer][TotalPluginStartup] 12.763023ms
,2016-09-26 16:31:43.682 ThaliTest[3263:6642808] Resetting plugins due to page load.
,2016-09-26 16:31:47.038 ThaliTest[3263:6642808] Finished load of: file:///var/mobile/Containers/Bundle/Application/D92BE563-E433-498B-953C-BA9570DC7414/ThaliTest.app/www/index.html
,2016-09-26 16:31:47.344 ThaliTest[3263:6642808] JXcore Cordova plugin initializing
,2016-09-26 16:31:47.345 ThaliTest[3263:6643026] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x15e4cfaa0>
,Optional("2B675178-02EF-484C-BFB0-76E7F82B99A0")
,nil
,nil
,Optional("D2E1F6BF-72FB-4E8F-8F3D-734C48C4373A")
,Optional("89CEAC8F-53E2-42A4-BED0-9487A50BEFFC")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.41742396354675
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

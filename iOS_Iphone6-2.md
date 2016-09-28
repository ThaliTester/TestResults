#### Test 85046911920cb66_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FD787B52-5B66-4605-B92B-5A1C4A467016/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/FD787B52-5B66-4605-B92B-5A1C4A467016/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/424215AD-F74F-433E-83DC-444A3B98B5C5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61279"
,(lldb)     command script import "/tmp/FD787B52-5B66-4605-B92B-5A1C4A467016/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 01:04:37.537 ThaliTest[1776:2324038] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/13B76222-48E0-4373-8ABD-D35D6EA9A608/Library/Cookies/Cookies.binarycookies
,2016-09-28 01:04:37.575 ThaliTest[1776:2324038] Apache Cordova native platform version 4.2.1 is starting.
2016-09-28 01:04:37.576 ThaliTest[1776:2324038] Multi-tasking -> Device: YES, App: YES
,2016-09-28 01:04:37.589 ThaliTest[1776:2324038] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 01:04:37.902 ThaliTest[1776:2324038] Using UIWebView
2016-09-28 01:04:37.905 ThaliTest[1776:2324038] [CDVTimer][handleopenurl] 0.186980ms
,2016-09-28 01:04:37.909 ThaliTest[1776:2324038] [CDVTimer][intentandnavigationfilter] 3.493011ms
2016-09-28 01:04:37.909 ThaliTest[1776:2324038] [CDVTimer][gesturehandler] 0.137985ms
2016-09-28 01:04:37.910 ThaliTest[1776:2324038] [CDVTimer][TotalPluginS,tartup] 4.581034ms
,2016-09-28 01:04:43.380 ThaliTest[1776:2324038] Resetting plugins due to page load.
,2016-09-28 01:04:43.785 ThaliTest[1776:2324038] Finished load of: file:///var/containers/Bundle/Application/424215AD-F74F-433E-83DC-444A3B98B5C5/ThaliTest.app/www/index.html
,2016-09-28 01:04:44.106 ThaliTest[1776:2324038] JXcore Cordova plugin initializing
,2016-09-28 01:04:44.106 ThaliTest[1776:2324215] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12dbeb8b0>
,Optional("F6E641B2-D0C8-4E35-8750-0073E27C6BEA")
nil
,nil
,Optional("54BECBEB-5837-48A4-A9FA-365C90206992")
,Optional("DB9F85D1-BC7E-4D42-9ED3-A4C901D16F43")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
Number of passed tests:  55
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  13.72100800275803
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

#### Test 8670851855de81a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8670851855de81a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DA393226-4C93-4F1B-9CDE-E0E5E26ECACC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DA393226-4C93-4F1B-9CDE-E0E5E26ECACC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8670851855de81a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8670851855de81a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/97F224B5-F0A7-4022-A68A-77917CA47E9F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60439"
,(lldb)     command script import "/tmp/DA393226-4C93-4F1B-9CDE-E0E5E26ECACC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 11:46:03.189 ThaliTest[1432:2239541] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3C9C4E2A-F546-4B89-B364-DD3925832D47/Library/Cookies/Cookies.binarycookies
,2016-09-26 11:46:03.232 ThaliTest[1432:2239541] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 11:46:03.233 ThaliTest[1432:2239541] Multi-tasking -> Device: YES, App: YES
,2016-09-26 11:46:03.246 ThaliTest[1432:2239541] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 11:46:03.550 ThaliTest[1432:2239541] Using UIWebView
,2016-09-26 11:46:03.553 ThaliTest[1432:2239541] [CDVTimer][handleopenurl] 0.182986ms
,2016-09-26 11:46:03.557 ThaliTest[1432:2239541] [CDVTimer][intentandnavigationfilter] 3.454030ms
2016-09-26 11:46:03.557 ThaliTest[1432:2239541] [CDVTimer][gesturehandler] 0.135958ms
2016-09-26 11:46:03.557 ThaliTest[1432:2239541] [CDVTimer][TotalPluginStartup] 4.572034ms
,2016-09-26 11:46:08.743 ThaliTest[1432:2239541] Resetting plugins due to page load.
,2016-09-26 11:46:09.071 ThaliTest[1432:2239541] Finished load of: file:///var/containers/Bundle/Application/97F224B5-F0A7-4022-A68A-77917CA47E9F/ThaliTest.app/www/index.html
,2016-09-26 11:46:09.405 ThaliTest[1432:2239541] JXcore Cordova plugin initializing
,2016-09-26 11:46:09.406 ThaliTest[1432:2239708] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-26 11:46:17.144 ThaliTest[1432:2239541] BTM: attaching to BTServer
,2016-09-26 11:46:17.880 ThaliTest[1432:2239541] BTM: local device power state changed
2016-09-26 11:46:17.880 ThaliTest[1432:2239541] BTM: power is now on
,2016-09-26 11:46:22.603 ThaliTest[1432:2239541] BTM: local device power state changed
2016-09-26 11:46:22.604 ThaliTest[1432:2239541] BTM: power is now off
,received session: <ThaliCore.Session: 0x156828e30>
,Optional("0E554B10-A59A-446A-B463-0D1A69BAE47B")
,nil
,nil
,Optional("C4FC53B7-0416-4599-AE06-DD17673CD8EB")
,Optional("DEF298EA-E3C8-4841-B116-41BFAB7BEC6E")
,*Native tests were executed*
Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  20.38085401058197
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

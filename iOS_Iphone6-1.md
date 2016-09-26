#### Test 864825826cfc86f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864825826cfc86f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3AA38FDF-27B2-41A5-BDC5-0DC59B2454B8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3AA38FDF-27B2-41A5-BDC5-0DC59B2454B8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864825826cfc86f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864825826cfc86f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F22CD2BC-FBFB-47AF-BFC9-3AF9841BF380/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62088"
,(lldb)     command script import "/tmp/3AA38FDF-27B2-41A5-BDC5-0DC59B2454B8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 16:58:37.827 ThaliTest[1464:2270074] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/04DB1BC0-A8DE-4AEA-8CC7-7B277EBD1E49/Library/Cookies/Cookies.binarycookies
,2016-09-26 16:58:37.912 ThaliTest[1464:2270074] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 16:58:37.915 ThaliTest[1464:2270074] Multi-tasking -> Device: YES, App: YES
,2016-09-26 16:58:37.937 ThaliTest[1464:2270074] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 16:58:38.386 ThaliTest[1464:2270074] Using UIWebView
,2016-09-26 16:58:38.393 ThaliTest[1464:2270074] [CDVTimer][handleopenurl] 0.437021ms
,2016-09-26 16:58:38.400 ThaliTest[1464:2270074] [CDVTimer][intentandnavigationfilter] 6.766021ms
2016-09-26 16:58:38.401 ThaliTest[1464:2270074] [CDVTimer][gesturehandler] 0.286996ms
2016-09-26 16:58:38.402 ThaliTest[1464:2270074] [CDVTimer][TotalPluginStartup] 9.185016ms
,2016-09-26 16:58:43.463 ThaliTest[1464:2270074] Resetting plugins due to page load.
,2016-09-26 16:58:43.830 ThaliTest[1464:2270074] Finished load of: file:///var/containers/Bundle/Application/F22CD2BC-FBFB-47AF-BFC9-3AF9841BF380/ThaliTest.app/www/index.html
,2016-09-26 16:58:44.161 ThaliTest[1464:2270074] JXcore Cordova plugin initializing
2016-09-26 16:58:44.162 ThaliTest[1464:2270233] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1466a2720>
,Optional("DC1174F6-7445-44C9-88EA-7BCAC6401348")
,nil
,nil
,Optional("499D0EA3-2946-42C2-B48E-72A4730934F8")
,Optional("084A4C63-187A-4C76-9667-0C7853AFE5D2")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  14.96109300851822
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

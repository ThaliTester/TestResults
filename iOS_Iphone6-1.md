#### Test 8326889394d960a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/04D601F5-EFDC-4EF1-B20C-AA17C911ED6F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/04D601F5-EFDC-4EF1-B20C-AA17C911ED6F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/BB99602D-A641-49C3-83F3-90F1FA288926/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53757"
,(lldb)     command script import "/tmp/04D601F5-EFDC-4EF1-B20C-AA17C911ED6F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-16 15:06:30.036 ThaliTest[808:998226] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E42850C3-342F-4D67-8B2B-DB23389419BD/Library/Cookies/Cookies.binarycookies
,2016-09-16 15:06:30.074 ThaliTest[808:998226] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 15:06:30.075 ThaliTest[808:998226] Multi-tasking -> Device: YES, App: YES
,2016-09-16 15:06:30.088 ThaliTest[808:998226] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 15:06:30.406 ThaliTest[808:998226] Using UIWebView
,2016-09-16 15:06:30.410 ThaliTest[808:998226] [CDVTimer][handleopenurl] 0.171006ms
,2016-09-16 15:06:30.414 ThaliTest[808:998226] [CDVTimer][intentandnavigationfilter] 3.477037ms
2016-09-16 15:06:30.414 ThaliTest[808:998226] [CDVTimer][gesturehandler] 0.173986ms
2016-09-16 15:06:30.414 ThaliTest[808:998226] [CDVTimer][TotalPluginStartup] 4.657984ms
,2016-09-16 15:06:35.583 ThaliTest[808:998226] Resetting plugins due to page load.
,2016-09-16 15:06:35.952 ThaliTest[808:998226] Finished load of: file:///var/containers/Bundle/Application/BB99602D-A641-49C3-83F3-90F1FA288926/ThaliTest.app/www/index.html
,2016-09-16 15:06:36.322 ThaliTest[808:998226] JXcore Cordova plugin initializing
2016-09-16 15:06:36.322 ThaliTest[808:998400] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-16 15:06:43.909 ThaliTest[808:998226] BTM: attaching to BTServer
,2016-09-16 15:06:49.380 ThaliTest[808:998226] BTM: local device power state changed
2016-09-16 15:06:49.381 ThaliTest[808:998226] BTM: power is now off
,2016-09-16 15:06:50.140 ThaliTest[808:998226] BTM: local device power state changed
2016-09-16 15:06:50.159 ThaliTest[808:998226] BTM: power is now on
,received session: <ThaliCore.Session: 0x12fada840>
,182AA951-CEC0-47E7-9241-D91E55B0C3F5
Optional("182AA951-CEC0-47E7-9241-D91E55B0C3F5")
nil
,nil

BFE09EAA-53B2-4BBF-99BD-4B991A7B4F47
Optional("BFE09EAA-53B2-4BBF-99BD-4B991A7B4F47")
BD879D44-553E-4C1D-82B3-6F89B2AE2348
Optional("BD879D44-553E-4C1D-82B3-6F89B2AE2348")
,*Native tests were executed*
Total number of executed tests:  52
,Number of passed tests:  52
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  17.57836496829987
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

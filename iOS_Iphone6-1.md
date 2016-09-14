#### Test 8526390230c731c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6027AD4F-3321-4FE9-87DC-E3ABE58F8797/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6027AD4F-3321-4FE9-87DC-E3ABE58F8797/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/996A2D7A-89D4-4DA7-A163-46BF61C8F7BB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50165"
,(lldb)     command script import "/tmp/6027AD4F-3321-4FE9-87DC-E3ABE58F8797/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 22:57:37.277 ThaliTest[630:779557] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7D147B82-E091-4CCB-BC6C-E7476EE5B6C2/Library/Cookies/Cookies.binarycookies
,2016-09-14 22:57:37.349 ThaliTest[630:779557] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 22:57:37.351 ThaliTest[630:779557] Multi-tasking -> Device: YES, App: YES
,2016-09-14 22:57:37.370 ThaliTest[630:779557] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 22:57:37.796 ThaliTest[630:779557] Using UIWebView
,2016-09-14 22:57:37.803 ThaliTest[630:779557] [CDVTimer][handleopenurl] 0.364006ms
,2016-09-14 22:57:37.810 ThaliTest[630:779557] [CDVTimer][intentandnavigationfilter] 7.014990ms
2016-09-14 22:57:37.811 ThaliTest[630:779557] [CDVTimer][gesturehandler] 0.292957ms
2016-09-14 22:57:37.812 ThaliTest[630:779557] [CDVTimer][TotalPluginStartup,] 9.293020ms
,2016-09-14 22:57:42.897 ThaliTest[630:779557] Resetting plugins due to page load.
,2016-09-14 22:57:43.281 ThaliTest[630:779557] Finished load of: file:///var/containers/Bundle/Application/996A2D7A-89D4-4DA7-A163-46BF61C8F7BB/ThaliTest.app/www/index.html
,2016-09-14 22:57:43.656 ThaliTest[630:779557] JXcore Cordova plugin initializing
2016-09-14 22:57:43.657 ThaliTest[630:779729] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1346bda10>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-14 22:58:05.669 ThaliTest[630:779557] BTM: attaching to BTServer
,2016-09-14 22:58:07.929 ThaliTest[630:779557] BTM: local device power state changed
2016-09-14 22:58:07.929 ThaliTest[630:779557] BTM: power is now off
,2016-09-14 22:58:08.658 ThaliTest[630:779557] BTM: local device power state changed
2016-09-14 22:58:08.659 ThaliTest[630:779557] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  51
Number of passed tests:  51
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  17.65635800361633
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```

#### Test 829140738877506_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F0F22931-D242-4BF3-86F6-CDFE6BE562B9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/F0F22931-D242-4BF3-86F6-CDFE6BE562B9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140738877506/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/EF94EA55-03D0-405A-84A0-053D0DBF8392/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52899"
,(lldb)     command script import "/tmp/F0F22931-D242-4BF3-86F6-CDFE6BE562B9/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 05:02:40.215 ThaliTest[843:880110] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/95B5F702-03C2-4503-84E9-ED2E08D2827B/Library/Cookies/Cookies.binarycookies
,2016-09-15 05:02:40.299 ThaliTest[843:880110] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 05:02:40.301 ThaliTest[843:880110] Multi-tasking -> Device: YES, App: YES
,2016-09-15 05:02:40.328 ThaliTest[843:880110] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 05:02:40.805 ThaliTest[843:880110] Using UIWebView
,2016-09-15 05:02:40.816 ThaliTest[843:880110] [CDVTimer][handleopenurl] 0.389040ms
,2016-09-15 05:02:40.823 ThaliTest[843:880110] [CDVTimer][intentandnavigationfilter] 6.915987ms
2016-09-15 05:02:40.824 ThaliTest[843:880110] [CDVTimer][gesturehandler] 0.320017ms
2016-09-15 05:02:40.824 ThaliTest[843:880110] [CDVTimer][TotalPluginStartup] 9.258032ms
,2016-09-15 05:02:46.167 ThaliTest[843:880110] Resetting plugins due to page load.
,2016-09-15 05:02:46.664 ThaliTest[843:880110] Finished load of: file:///var/containers/Bundle/Application/EF94EA55-03D0-405A-84A0-053D0DBF8392/ThaliTest.app/www/index.html
,2016-09-15 05:02:47.058 ThaliTest[843:880110] JXcore Cordova plugin initializing
,2016-09-15 05:02:47.059 ThaliTest[843:880278] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x10b039ad0>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-15 05:03:05.817 ThaliTest[843:880110] BTM: attaching to BTServer
,2016-09-15 05:03:06.947 ThaliTest[843:880110] BTM: local device power state changed
,2016-09-15 05:03:06.948 ThaliTest[843:880110] BTM: power is now off
,2016-09-15 05:03:07.738 ThaliTest[843:880110] BTM: local device power state changed
2016-09-15 05:03:07.743 ThaliTest[843:880110] BTM: power is now on
,*Native tests were executed*
,Total number of executed tests:  48
,Number of passed tests:  48
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  13.22220402956009
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

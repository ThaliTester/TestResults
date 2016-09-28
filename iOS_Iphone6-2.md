#### Test 871169230429d0a_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/871169230429d0a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C1AEA428-1A67-49EF-B93A-3826D3B99D4C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/C1AEA428-1A67-49EF-B93A-3826D3B99D4C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/871169230429d0a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/871169230429d0a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/ED2F27C6-3FDD-4FC1-9C27-F8A7C33890D3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55590"
,(lldb)     command script import "/tmp/C1AEA428-1A67-49EF-B93A-3826D3B99D4C/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 07:41:13.754 ThaliTest[1816:2357200] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/483EC01C-BB5B-43A5-B07A-3E9F7C3A9F51/Library/Cookies/Cookies.binarycookies
,2016-09-28 07:41:13.794 ThaliTest[1816:2357200] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 07:41:13.795 ThaliTest[1816:2357200] Multi-tasking -> Device: YES, App: YES
,2016-09-28 07:41:13.806 ThaliTest[1816:2357200] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 07:41:14.131 ThaliTest[1816:2357200] Using UIWebView
,2016-09-28 07:41:14.135 ThaliTest[1816:2357200] [CDVTimer][handleopenurl] 0.230014ms
,2016-09-28 07:41:14.139 ThaliTest[1816:2357200] [CDVTimer][intentandnavigationfilter] 3.508985ms
2016-09-28 07:41:14.139 ThaliTest[1816:2357200] [CDVTimer][gesturehandler] 0.149012ms
2016-09-28 07:41:14.140 ThaliTest[1816:2357200] [CDVTimer][TotalPluginStartup] 4.743993ms
,2016-09-28 07:41:19.800 ThaliTest[1816:2357200] Resetting plugins due to page load.
,2016-09-28 07:41:20.231 ThaliTest[1816:2357200] Finished load of: file:///var/containers/Bundle/Application/ED2F27C6-3FDD-4FC1-9C27-F8A7C33890D3/ThaliTest.app/www/index.html
,2016-09-28 07:41:20.655 ThaliTest[1816:2357200] JXcore Cordova plugin initializing
,2016-09-28 07:41:20.657 ThaliTest[1816:2357383] JXcore instance initializing
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
,*Native tests were executed*
,Total number of executed tests:  54
Number of passed tests:  54
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  16.42546200752258
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

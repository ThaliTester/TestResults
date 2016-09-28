#### Test 87126746a66927d_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/14F9C5D9-F293-44C3-9BBB-EAF94F0D402B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/14F9C5D9-F293-44C3-9BBB-EAF94F0D402B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DFCAEED9-593F-495B-927E-A7421D247C4C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54533"
,(lldb)     command script import "/tmp/14F9C5D9-F293-44C3-9BBB-EAF94F0D402B/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 07:30:20.502 ThaliTest[1809:2355544] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/09206FDB-D032-4BD0-B47A-D2B6DAA41532/Library/Cookies/Cookies.binarycookies
,2016-09-28 07:30:20.550 ThaliTest[1809:2355544] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 07:30:20.551 ThaliTest[1809:2355544] Multi-tasking -> Device: YES, App: YES
,2016-09-28 07:30:20.563 ThaliTest[1809:2355544] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 07:30:20.937 ThaliTest[1809:2355544] Using UIWebView
2016-09-28 07:30:20.941 ThaliTest[1809:2355544] [CDVTimer][handleopenurl] 0.235021ms
,2016-09-28 07:30:20.947 ThaliTest[1809:2355544] [CDVTimer][intentandnavigationfilter] 5.815029ms
2016-09-28 07:30:20.947 ThaliTest[1809:2355544] [CDVTimer][gesturehandler] 0.194013ms
2016-09-28 07:30:20.948 ThaliTest[1809:2355544] [CDVTimer][TotalPluginStartup] 7.242024ms
,2016-09-28 07:30:26.717 ThaliTest[1809:2355544] Resetting plugins due to page load.
,2016-09-28 07:30:27.186 ThaliTest[1809:2355544] Finished load of: file:///var/containers/Bundle/Application/DFCAEED9-593F-495B-927E-A7421D247C4C/ThaliTest.app/www/index.html
,2016-09-28 07:30:27.541 ThaliTest[1809:2355544] JXcore Cordova plugin initializing
,2016-09-28 07:30:27.541 ThaliTest[1809:2355724] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x13e7cadd0>
,Optional("B47EFAE2-0804-4D67-ADE1-FA5DF3ECDAF7")
,nil
,nil
,Optional("73448844-72F8-4D9D-AD21-B723D386A866")
,Optional("9F4F167C-B7FC-4AEE-BC5C-14232F66BFAE")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.39983701705933
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

#### Test 850469114943827_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469114943827/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F5695318-8A21-417E-A68A-9B3204872F30/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/F5695318-8A21-417E-A68A-9B3204872F30/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469114943827/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469114943827/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6728D6D8-20B8-460E-8936-C85EC47DFEBB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63265"
,(lldb)     command script import "/tmp/F5695318-8A21-417E-A68A-9B3204872F30/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 00:10:21.710 ThaliTest[1425:1758585] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AAA1497E-537C-4AF9-8914-3A1087B7FAA2/Library/Cookies/Cookies.binarycookies
,2016-09-23 00:10:21.773 ThaliTest[1425:1758585] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 00:10:21.774 ThaliTest[1425:1758585] Multi-tasking -> Device: YES, App: YES
,2016-09-23 00:10:21.787 ThaliTest[1425:1758585] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 00:10:22.114 ThaliTest[1425:1758585] Using UIWebView
,2016-09-23 00:10:22.120 ThaliTest[1425:1758585] [CDVTimer][handleopenurl] 0.194013ms
,2016-09-23 00:10:22.124 ThaliTest[1425:1758585] [CDVTimer][intentandnavigationfilter] 3.458023ms
2016-09-23 00:10:22.124 ThaliTest[1425:1758585] [CDVTimer][gesturehandler] 0.163972ms
2016-09-23 00:10:22.124 ThaliTest[1425:1758585] [CDVTimer][TotalPluginStartup] 4.658997ms
,2016-09-23 00:10:28.866 ThaliTest[1425:1758585] Resetting plugins due to page load.
,2016-09-23 00:10:29.319 ThaliTest[1425:1758585] Finished load of: file:///var/containers/Bundle/Application/6728D6D8-20B8-460E-8936-C85EC47DFEBB/ThaliTest.app/www/index.html
,2016-09-23 00:10:29.662 ThaliTest[1425:1758585] JXcore Cordova plugin initializing
,2016-09-23 00:10:29.663 ThaliTest[1425:1758772] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 00:10:37.116 ThaliTest[1425:1758585] BTM: attaching to BTServer
,2016-09-23 00:10:37.874 ThaliTest[1425:1758585] BTM: local device power state changed
2016-09-23 00:10:37.886 ThaliTest[1425:1758585] BTM: power is now on
,2016-09-23 00:10:42.615 ThaliTest[1425:1758585] BTM: local device power state changed
2016-09-23 00:10:42.617 ThaliTest[1425:1758585] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  7
Number of passed tests:  7
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  5.662656962871552
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

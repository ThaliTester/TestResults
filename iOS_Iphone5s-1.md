#### Test 850469114456a2a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469114456a2a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6D543E5A-9BCF-4501-89EC-EE6C25310DCA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6D543E5A-9BCF-4501-89EC-EE6C25310DCA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469114456a2a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469114456a2a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CE537F10-2A8F-4B35-AF7D-644ABF6566D9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62758"
,(lldb)     command script import "/tmp/6D543E5A-9BCF-4501-89EC-EE6C25310DCA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 10:49:47.538 ThaliTest[3429:6932247] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E33BE078-9F7D-4A2C-8B57-D85B3DB9E958/Library/Cookies/Cookies.binarycookies
,2016-09-28 10:49:47.659 ThaliTest[3429:6932247] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 10:49:47.661 ThaliTest[3429:6932247] Multi-tasking -> Device: YES, App: YES
,2016-09-28 10:49:47.681 ThaliTest[3429:6932247] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 10:49:49.351 ThaliTest[3429:6932247] Using UIWebView
,2016-09-28 10:49:49.359 ThaliTest[3429:6932247] [CDVTimer][handleopenurl] 0.507951ms
,2016-09-28 10:49:49.367 ThaliTest[3429:6932247] [CDVTimer][intentandnavigationfilter] 8.102000ms
2016-09-28 10:49:49.368 ThaliTest[3429:6932247] [CDVTimer][gesturehandler] 0.414968ms
2016-09-28 10:49:49.369 ThaliTest[3429:6932247] [CDVTimer][TotalPluginStartup] 10.876000ms
,2016-09-28 10:49:57.074 ThaliTest[3429:6932247] Resetting plugins due to page load.
,2016-09-28 10:50:01.335 ThaliTest[3429:6932247] Finished load of: file:///var/mobile/Containers/Bundle/Application/CE537F10-2A8F-4B35-AF7D-644ABF6566D9/ThaliTest.app/www/index.html
,2016-09-28 10:50:01.525 ThaliTest[3429:6932247] JXcore Cordova plugin initializing
,2016-09-28 10:50:01.526 ThaliTest[3429:6932465] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x157ccb320>
,Optional("0E5CF763-8A5B-41C7-8920-1BC845F24F62")
,nil
,nil
,Optional("5FAD8496-6D53-44CF-9BD5-812AC7C5FBB7")
,Optional("36D14894-D216-43ED-9B49-70C6479472F9")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.04974001646042
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

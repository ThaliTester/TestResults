#### Test 83268893919c9ad_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/166F70B2-F8C6-414C-BCBD-9BD66FCB8B9F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/166F70B2-F8C6-414C-BCBD-9BD66FCB8B9F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893919c9ad/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/434A205E-D4FB-4699-A48F-F85C14C649E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57918"
,(lldb)     command script import "/tmp/166F70B2-F8C6-414C-BCBD-9BD66FCB8B9F/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-22 01:31:50.614 ThaliTest[1308:1645820] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AEBEBC19-F2D6-4B6D-8AE4-6018FCCF4E22/Library/Cookies/Cookies.binarycookies
,2016-09-22 01:31:50.681 ThaliTest[1308:1645820] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 01:31:50.682 ThaliTest[1308:1645820] Multi-tasking -> Device: YES, App: YES
,2016-09-22 01:31:50.698 ThaliTest[1308:1645820] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 01:31:51.155 ThaliTest[1308:1645820] Using UIWebView
,2016-09-22 01:31:51.162 ThaliTest[1308:1645820] [CDVTimer][handleopenurl] 0.474989ms
,2016-09-22 01:31:51.169 ThaliTest[1308:1645820] [CDVTimer][intentandnavigationfilter] 7.167041ms
2016-09-22 01:31:51.170 ThaliTest[1308:1645820] [CDVTimer][gesturehandler] 0.301003ms
2016-09-22 01:31:51.170 ThaliTest[1308:1645820] [CDVTimer][TotalPluginStartup] 9.452045ms
,2016-09-22 01:31:56.952 ThaliTest[1308:1645820] Resetting plugins due to page load.
,2016-09-22 01:31:57.352 ThaliTest[1308:1645820] Finished load of: file:///var/containers/Bundle/Application/434A205E-D4FB-4699-A48F-F85C14C649E2/ThaliTest.app/www/index.html
,2016-09-22 01:31:57.673 ThaliTest[1308:1645820] JXcore Cordova plugin initializing
,2016-09-22 01:31:57.674 ThaliTest[1308:1645995] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x128ee66b0>
,Optional("367973CE-E3D0-47A5-9FD0-52C3AF7A06C2")
nil
,nil
,Optional("6513EB97-09E5-4B1D-B324-45F20DB7C881")
,Optional("8CE840F3-8A7E-4198-9D98-7FF51D944114")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 01:32:19.503 ThaliTest[1308:1645820] BTM: attaching to BTServer
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  50
Number of failed tests:  6
Number of ignored tests:  0
,Total duration:  34.5480529665947
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't r
```

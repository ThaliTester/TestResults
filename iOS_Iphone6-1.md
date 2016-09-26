#### Test 865221020889ce9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6AD8C551-85D7-4ADF-8362-140CFF2BFE00/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6AD8C551-85D7-4ADF-8362-140CFF2BFE00/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/865221020889ce9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C8D4013F-2945-4376-8850-FF42E7297E45/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59237"
,(lldb)     command script import "/tmp/6AD8C551-85D7-4ADF-8362-140CFF2BFE00/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 16:31:31.136 ThaliTest[1457:2266559] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6E90393C-6612-4776-9FE3-277ACF09837D/Library/Cookies/Cookies.binarycookies
,2016-09-26 16:31:31.216 ThaliTest[1457:2266559] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 16:31:31.218 ThaliTest[1457:2266559] Multi-tasking -> Device: YES, App: YES
,2016-09-26 16:31:31.237 ThaliTest[1457:2266559] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 16:31:31.705 ThaliTest[1457:2266559] Using UIWebView
,2016-09-26 16:31:31.712 ThaliTest[1457:2266559] [CDVTimer][handleopenurl] 0.586033ms
,2016-09-26 16:31:31.720 ThaliTest[1457:2266559] [CDVTimer][intentandnavigationfilter] 7.520974ms
2016-09-26 16:31:31.721 ThaliTest[1457:2266559] [CDVTimer][gesturehandler] 0.326037ms
2016-09-26 16:31:31.721 ThaliTest[1457:2266559] [CDVTimer][TotalPluginS,tartup] 10.011971ms
,2016-09-26 16:31:37.008 ThaliTest[1457:2266559] Resetting plugins due to page load.
,2016-09-26 16:31:37.380 ThaliTest[1457:2266559] Finished load of: file:///var/containers/Bundle/Application/C8D4013F-2945-4376-8850-FF42E7297E45/ThaliTest.app/www/index.html
,2016-09-26 16:31:37.711 ThaliTest[1457:2266559] JXcore Cordova plugin initializing
,2016-09-26 16:31:37.711 ThaliTest[1457:2266732] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x13f3443d0>
,Optional("B8192971-FE0A-4AF0-B695-53B90D4E672A")
nil
,nil
,Optional("1531325C-F02C-401D-B98E-DE9759F3E177")
,Optional("D984A167-2F5D-4566-9506-90C83214251B")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  15.32888996601105
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

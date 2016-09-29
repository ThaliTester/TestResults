#### Test 8712674671a25ec_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6CB063FE-DEA0-4AC9-87F1-82C056A885C6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6CB063FE-DEA0-4AC9-87F1-82C056A885C6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/979468AC-E25A-4301-8FD0-553DB0FFAA40/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64214"
,(lldb)     command script import "/tmp/6CB063FE-DEA0-4AC9-87F1-82C056A885C6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 09:40:46.447 ThaliTest[3500:7086671] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DCC6D12A-79F4-498B-A7B7-D5B2FC19FC49/Library/Cookies/Cookies.binarycookies
,2016-09-29 09:40:46.567 ThaliTest[3500:7086671] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 09:40:46.569 ThaliTest[3500:7086671] Multi-tasking -> Device: YES, App: YES
,2016-09-29 09:40:46.594 ThaliTest[3500:7086671] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 09:40:48.082 ThaliTest[3500:7086671] Using UIWebView
,2016-09-29 09:40:48.090 ThaliTest[3500:7086671] [CDVTimer][handleopenurl] 0.633001ms
,2016-09-29 09:40:48.099 ThaliTest[3500:7086671] [CDVTimer][intentandnavigationfilter] 8.211017ms
2016-09-29 09:40:48.100 ThaliTest[3500:7086671] [CDVTimer][gesturehandler] 0.379026ms
2016-09-29 09:40:48.100 ThaliTest[3500:7086671] [CDVTimer][TotalPluginStartup] 11.079013ms
,2016-09-29 09:40:54.764 ThaliTest[3500:7086671] Resetting plugins due to page load.
,2016-09-29 09:40:58.320 ThaliTest[3500:7086671] Finished load of: file:///var/mobile/Containers/Bundle/Application/979468AC-E25A-4301-8FD0-553DB0FFAA40/ThaliTest.app/www/index.html
,2016-09-29 09:40:58.636 ThaliTest[3500:7086671] JXcore Cordova plugin initializing
,2016-09-29 09:40:58.637 ThaliTest[3500:7086891] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x130756c00>
,Optional("1BE50720-E276-4600-A7FE-51CFE1609B92")
,nil
,nil
,Optional("1CFB302D-55CE-470C-A7A7-8793334A8793")
,Optional("DFF59D7C-CFD1-42CB-9A74-7B0BBCDD886D")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  56
Number of passed tests:  56
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  14.39854800701141
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

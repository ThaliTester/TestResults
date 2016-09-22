#### Test 861743790af7a74_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/93ACA6C4-29D5-42CF-BFA0-0A794D13A3B6/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/93ACA6C4-29D5-42CF-BFA0-0A794D13A3B6/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743790af7a74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C188FA86-330D-4ACF-B3FC-E47F56E35106/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63451"
,(lldb)     command script import "/tmp/93ACA6C4-29D5-42CF-BFA0-0A794D13A3B6/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-22 03:39:47.788 ThaliTest[1336:1658450] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D174C8A6-6AF1-4572-A758-E2AA389F9CCA/Library/Cookies/Cookies.binarycookies
,2016-09-22 03:39:47.854 ThaliTest[1336:1658450] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 03:39:47.855 ThaliTest[1336:1658450] Multi-tasking -> Device: YES, App: YES
,2016-09-22 03:39:47.871 ThaliTest[1336:1658450] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 03:39:48.213 ThaliTest[1336:1658450] Using UIWebView
,2016-09-22 03:39:48.217 ThaliTest[1336:1658450] [CDVTimer][handleopenurl] 0.164032ms
,2016-09-22 03:39:48.220 ThaliTest[1336:1658450] [CDVTimer][intentandnavigationfilter] 3.545046ms
2016-09-22 03:39:48.221 ThaliTest[1336:1658450] [CDVTimer][gesturehandler] 0.141978ms
2016-09-22 03:39:48.221 ThaliTest[1336:1658450] [CDVTimer][TotalPluginStartup] 4.649997ms
,2016-09-22 03:39:54.147 ThaliTest[1336:1658450] Resetting plugins due to page load.
,2016-09-22 03:39:54.572 ThaliTest[1336:1658450] Finished load of: file:///var/containers/Bundle/Application/C188FA86-330D-4ACF-B3FC-E47F56E35106/ThaliTest.app/www/index.html
,2016-09-22 03:39:54.918 ThaliTest[1336:1658450] JXcore Cordova plugin initializing
,2016-09-22 03:39:54.919 ThaliTest[1336:1658633] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x124e40950>
,Optional("D7F21428-51FE-4BF8-9D3B-2005EFF3AAD9")
nil
,nil
,Optional("B511BF6C-5CBC-4A04-80D3-4042D5254922")
,Optional("C554F1C6-DE58-425C-918B-88BEA1E9977C")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 03:40:17.726 ThaliTest[1336:1658450] BTM: attaching to BTServer
,2016-09-22 03:40:18.503 ThaliTest[1336:1658450] BTM: local device power state changed
2016-09-22 03:40:18.504 ThaliTest[1336:1658450] BTM: power is now on
,2016-09-22 03:40:23.204 ThaliTest[1336:1658450] BTM: local device power state changed
2016-09-22 03:40:23.205 ThaliTest[1336:1658450] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.90284597873688
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```

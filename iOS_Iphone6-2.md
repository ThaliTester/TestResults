#### Test 855258874296799_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8230E6DE-2D46-4BAA-8E82-8CC472367B51/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/8230E6DE-2D46-4BAA-8E82-8CC472367B51/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/855258874296799/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/51E8703D-D121-4E99-A702-109F2441C68B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51620"
,(lldb)     command script import "/tmp/8230E6DE-2D46-4BAA-8E82-8CC472367B51/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-22 05:06:23.774 ThaliTest[1353:1666633] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D2AB5BB0-4E0D-4B0C-9C94-95580F2F4115/Library/Cookies/Cookies.binarycookies
,2016-09-22 05:06:23.849 ThaliTest[1353:1666633] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 05:06:23.851 ThaliTest[1353:1666633] Multi-tasking -> Device: YES, App: YES
,2016-09-22 05:06:23.872 ThaliTest[1353:1666633] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 05:06:24.359 ThaliTest[1353:1666633] Using UIWebView
,2016-09-22 05:06:24.366 ThaliTest[1353:1666633] [CDVTimer][handleopenurl] 0.503957ms
,2016-09-22 05:06:24.373 ThaliTest[1353:1666633] [CDVTimer][intentandnavigationfilter] 6.799996ms
2016-09-22 05:06:24.374 ThaliTest[1353:1666633] [CDVTimer][gesturehandler] 0.298977ms
2016-09-22 05:06:24.375 ThaliTest[1353:1666633] [CDVTimer][TotalPluginStartup] 9.173989ms
,2016-09-22 05:06:30.070 ThaliTest[1353:1666633] Resetting plugins due to page load.
,2016-09-22 05:06:30.508 ThaliTest[1353:1666633] Finished load of: file:///var/containers/Bundle/Application/51E8703D-D121-4E99-A702-109F2441C68B/ThaliTest.app/www/index.html
,2016-09-22 05:06:30.850 ThaliTest[1353:1666633] JXcore Cordova plugin initializing
,2016-09-22 05:06:30.851 ThaliTest[1353:1666797] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x128d547d0>
,Optional("968C15C7-4A33-44F7-BA80-64167FF7E349")
,nil
,nil
,Optional("84BD2A10-5AB1-4711-9624-1B894C3338F5")
,Optional("0BE902C9-8221-4C88-B177-03A882A454DE")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 05:06:52.200 ThaliTest[1353:1666633] BTM: attaching to BTServer
,2016-09-22 05:06:52.991 ThaliTest[1353:1666633] BTM: local device power state changed
2016-09-22 05:06:53.004 ThaliTest[1353:1666633] BTM: power is now on
,2016-09-22 05:06:57.691 ThaliTest[1353:1666633] BTM: local device power state changed
2016-09-22 05:06:57.691 ThaliTest[1353:1666633] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  19.634496986866
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```

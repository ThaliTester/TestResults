#### Test 85046911aaecdb3_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911aaecdb3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8D7CB596-483A-4E14-86AD-2848F95CECA7/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/8D7CB596-483A-4E14-86AD-2848F95CECA7/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911aaecdb3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911aaecdb3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/992E1A3B-31E7-43D4-B25D-FFCFFDE3C15B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57834"
,(lldb)     command script import "/tmp/8D7CB596-483A-4E14-86AD-2848F95CECA7/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 00:23:46.333 ThaliTest[1671:2208694] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/37AEA42E-4CEB-4F55-A026-0601CCE4927B/Library/Cookies/Cookies.binarycookies
,2016-09-27 00:23:46.374 ThaliTest[1671:2208694] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 00:23:46.375 ThaliTest[1671:2208694] Multi-tasking -> Device: YES, App: YES
,2016-09-27 00:23:46.387 ThaliTest[1671:2208694] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 00:23:46.702 ThaliTest[1671:2208694] Using UIWebView
,2016-09-27 00:23:46.706 ThaliTest[1671:2208694] [CDVTimer][handleopenurl] 0.221014ms
2016-09-27 00:23:46.710 ThaliTest[1671:2208694] [CDVTimer][intentandnavigationfilter] 4.173994ms
2016-09-27 00:23:46.711 ThaliTest[1671:2208694] [CDVTimer][gesturehandler] 0.150979ms
2016-09-27 00:23:46.711 ThaliTest[1671:2208694] [CDVTimer][TotalPluginStartup] 5.496979ms
,2016-09-27 00:23:53.735 ThaliTest[1671:2208694] Resetting plugins due to page load.
,2016-09-27 00:23:54.208 ThaliTest[1671:2208694] Finished load of: file:///var/containers/Bundle/Application/992E1A3B-31E7-43D4-B25D-FFCFFDE3C15B/ThaliTest.app/www/index.html
,2016-09-27 00:23:54.609 ThaliTest[1671:2208694] JXcore Cordova plugin initializing
,2016-09-27 00:23:54.610 ThaliTest[1671:2208879] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
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
,Total number of executed tests:  12
,Number of passed tests:  12
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.03468900918960571
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

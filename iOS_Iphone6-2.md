#### Test 85046911d6c2afe_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9C8C1A96-B5E8-4EA1-AF3E-91A720218D2C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/9C8C1A96-B5E8-4EA1-AF3E-91A720218D2C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911d6c2afe/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DEBFE349-7430-4D89-8EE6-57087A9C0390/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49271"
,(lldb)     command script import "/tmp/9C8C1A96-B5E8-4EA1-AF3E-91A720218D2C/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 02:01:51.585 ThaliTest[1157:1523163] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/157333A3-1422-44B7-873A-7FD7136E60D4/Library/Cookies/Cookies.binarycookies
,2016-09-21 02:01:51.916 ThaliTest[1157:1523163] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 02:01:51.918 ThaliTest[1157:1523163] Multi-tasking -> Device: YES, App: YES
,2016-09-21 02:01:51.943 ThaliTest[1157:1523163] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 02:01:52.506 ThaliTest[1157:1523163] Using UIWebView
,2016-09-21 02:01:52.513 ThaliTest[1157:1523163] [CDVTimer][handleopenurl] 0.512004ms
,2016-09-21 02:01:52.520 ThaliTest[1157:1523163] [CDVTimer][intentandnavigationfilter] 7.076979ms
2016-09-21 02:01:52.521 ThaliTest[1157:1523163] [CDVTimer][gesturehandler] 0.298977ms
2016-09-21 02:01:52.521 ThaliTest[1157:1523163] [CDVTimer][TotalPluginStartup] 9.388983ms
,2016-09-21 02:01:58.685 ThaliTest[1157:1523163] Resetting plugins due to page load.
,2016-09-21 02:01:59.220 ThaliTest[1157:1523163] Finished load of: file:///var/containers/Bundle/Application/DEBFE349-7430-4D89-8EE6-57087A9C0390/ThaliTest.app/www/index.html
,2016-09-21 02:01:59.625 ThaliTest[1157:1523163] JXcore Cordova plugin initializing
,2016-09-21 02:01:59.625 ThaliTest[1157:1523352] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 02:02:06.331 ThaliTest[1157:1523352] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 02:02:06.331 ThaliTest[1157:1523352] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 02:02:06.331 ThaliTest[1157:1523352] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 02:02:06.334 ThaliTest[1157:1523352] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 02:02:06.738 ThaliTest[1157:1523352] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005662024021148682
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

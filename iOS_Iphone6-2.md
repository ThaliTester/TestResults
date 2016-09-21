#### Test 850469111b8590e_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469111b8590e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3391732A-2EF7-463F-91A3-3AC1CF4D069A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/3391732A-2EF7-463F-91A3-3AC1CF4D069A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469111b8590e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469111b8590e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/223F6FFC-5F10-4954-881C-79249D690B9F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51559"
,(lldb)     command script import "/tmp/3391732A-2EF7-463F-91A3-3AC1CF4D069A/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 02:56:18.409 ThaliTest[1167:1528374] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BCE9A0ED-B076-4F20-AEAA-C556422C9462/Library/Cookies/Cookies.binarycookies
,2016-09-21 02:56:18.736 ThaliTest[1167:1528374] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 02:56:18.738 ThaliTest[1167:1528374] Multi-tasking -> Device: YES, App: YES
,2016-09-21 02:56:18.762 ThaliTest[1167:1528374] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 02:56:19.291 ThaliTest[1167:1528374] Using UIWebView
,2016-09-21 02:56:19.299 ThaliTest[1167:1528374] [CDVTimer][handleopenurl] 0.734985ms
,2016-09-21 02:56:19.307 ThaliTest[1167:1528374] [CDVTimer][intentandnavigationfilter] 7.192016ms
2016-09-21 02:56:19.308 ThaliTest[1167:1528374] [CDVTimer][gesturehandler] 0.307024ms
2016-09-21 02:56:19.308 ThaliTest[1167:1528374] [CDVTimer][TotalPluginStartup] 9.809017ms
,2016-09-21 02:56:25.084 ThaliTest[1167:1528374] Resetting plugins due to page load.
,2016-09-21 02:56:25.486 ThaliTest[1167:1528374] Finished load of: file:///var/containers/Bundle/Application/223F6FFC-5F10-4954-881C-79249D690B9F/ThaliTest.app/www/index.html
,2016-09-21 02:56:25.885 ThaliTest[1167:1528374] JXcore Cordova plugin initializing
,2016-09-21 02:56:25.886 ThaliTest[1167:1528570] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 02:56:32.828 ThaliTest[1167:1528570] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 02:56:32.829 ThaliTest[1167:1528570] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 02:56:32.829 ThaliTest[1167:1528570] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 02:56:32.831 ThaliTest[1167:1528570] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 02:56:33.241 ThaliTest[1167:1528570] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004058957099914551
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

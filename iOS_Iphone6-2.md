#### Test 850469116350bd7_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469116350bd7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/156CAED5-4D3E-4A7C-9F61-7F1AD1529A7A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/156CAED5-4D3E-4A7C-9F61-7F1AD1529A7A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469116350bd7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469116350bd7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/52BED1F4-AD50-403E-9BFD-9E5D36B8534B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53886"
,(lldb)     command script import "/tmp/156CAED5-4D3E-4A7C-9F61-7F1AD1529A7A/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-20 00:35:24.074 ThaliTest[1095:1404767] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F4B07010-0B53-4EDA-8CF3-7BEE093D1672/Library/Cookies/Cookies.binarycookies
,2016-09-20 00:35:24.394 ThaliTest[1095:1404767] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 00:35:24.396 ThaliTest[1095:1404767] Multi-tasking -> Device: YES, App: YES
,2016-09-20 00:35:24.420 ThaliTest[1095:1404767] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 00:35:24.967 ThaliTest[1095:1404767] Using UIWebView
,2016-09-20 00:35:24.974 ThaliTest[1095:1404767] [CDVTimer][handleopenurl] 0.392020ms
,2016-09-20 00:35:24.982 ThaliTest[1095:1404767] [CDVTimer][intentandnavigationfilter] 7.265031ms
2016-09-20 00:35:24.983 ThaliTest[1095:1404767] [CDVTimer][gesturehandler] 0.299037ms
2016-09-20 00:35:24.983 ThaliTest[1095:1404767] [CDVTimer][TotalPluginStartup] 9.618998ms
,2016-09-20 00:35:30.768 ThaliTest[1095:1404767] Resetting plugins due to page load.
,2016-09-20 00:35:31.275 ThaliTest[1095:1404767] Finished load of: file:///var/containers/Bundle/Application/52BED1F4-AD50-403E-9BFD-9E5D36B8534B/ThaliTest.app/www/index.html
,2016-09-20 00:35:31.678 ThaliTest[1095:1404767] JXcore Cordova plugin initializing
,2016-09-20 00:35:31.679 ThaliTest[1095:1404954] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 00:35:38.351 ThaliTest[1095:1404954] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 00:35:38.351 ThaliTest[1095:1404954] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-20 00:35:38.351 ThaliTest[1095:1,404954] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-20 00:35:38.353 ThaliTest[1095:1404954] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 00:35:38.758 ThaliTest[1095:1404954] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.002559006214141846
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

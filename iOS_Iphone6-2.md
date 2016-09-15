#### Test 8504691174f7534_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8BBCBC41-C23B-435C-B47A-04445CE29EF6/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/8BBCBC41-C23B-435C-B47A-04445CE29EF6/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1CD5A90C-F962-4C5C-8964-486717BC6170/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58589"
,(lldb)     command script import "/tmp/8BBCBC41-C23B-435C-B47A-04445CE29EF6/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 03:00:37.425 ThaliTest[815:867848] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7E892A06-3134-4762-AF91-EB198BE8715B/Library/Cookies/Cookies.binarycookies
,2016-09-15 03:00:37.757 ThaliTest[815:867848] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 03:00:37.759 ThaliTest[815:867848] Multi-tasking -> Device: YES, App: YES
,2016-09-15 03:00:37.784 ThaliTest[815:867848] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 03:00:38.307 ThaliTest[815:867848] Using UIWebView
,2016-09-15 03:00:38.317 ThaliTest[815:867848] [CDVTimer][handleopenurl] 0.383019ms
,2016-09-15 03:00:38.325 ThaliTest[815:867848] [CDVTimer][intentandnavigationfilter] 7.239044ms
2016-09-15 03:00:38.325 ThaliTest[815:867848] [CDVTimer][gesturehandler] 0.338018ms
2016-09-15 03:00:38.326 ThaliTest[815:867848] [CDVTimer][TotalPluginStartup,] 9.513974ms
,2016-09-15 03:00:44.077 ThaliTest[815:867848] Resetting plugins due to page load.
,2016-09-15 03:00:44.558 ThaliTest[815:867848] Finished load of: file:///var/containers/Bundle/Application/1CD5A90C-F962-4C5C-8964-486717BC6170/ThaliTest.app/www/index.html
,2016-09-15 03:00:44.959 ThaliTest[815:867848] JXcore Cordova plugin initializing
,2016-09-15 03:00:44.960 ThaliTest[815:868044] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 03:00:51.463 ThaliTest[815:868044] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 03:00:51.463 ThaliTest[815:868044] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 03:00:51.463 ThaliTest[815:868044] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 03:00:51.465 ThaliTest[815:868044] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-15 03:00:51.843 ThaliTest[815:868044] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004256963729858398
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

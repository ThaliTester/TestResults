#### Test 85960304e9d96a8_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CEF1D867-A59A-4B70-9F06-DFD50504091E/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/CEF1D867-A59A-4B70-9F06-DFD50504091E/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8208F81D-9EA4-468F-9CDF-0CBC8B44E8CD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55138"
,(lldb)     command script import "/tmp/CEF1D867-A59A-4B70-9F06-DFD50504091E/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 04:04:37.720 ThaliTest[1189:1536338] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F44506B2-C4F6-4D67-A08C-CB921C4A172C/Library/Cookies/Cookies.binarycookies
,2016-09-21 04:04:37.915 ThaliTest[1189:1536338] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 04:04:37.915 ThaliTest[1189:1536338] Multi-tasking -> Device: YES, App: YES
,2016-09-21 04:04:37.934 ThaliTest[1189:1536338] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 04:04:38.329 ThaliTest[1189:1536338] Using UIWebView
,2016-09-21 04:04:38.335 ThaliTest[1189:1536338] [CDVTimer][handleopenurl] 0.366986ms
,2016-09-21 04:04:38.342 ThaliTest[1189:1536338] [CDVTimer][intentandnavigationfilter] 6.982982ms
2016-09-21 04:04:38.343 ThaliTest[1189:1536338] [CDVTimer][gesturehandler] 0.329018ms
2016-09-21 04:04:38.344 ThaliTest[1189:1536338] [CDVTimer][TotalPluginS,tartup] 9.243011ms
,2016-09-21 04:04:44.219 ThaliTest[1189:1536338] Resetting plugins due to page load.
,2016-09-21 04:04:44.761 ThaliTest[1189:1536338] Finished load of: file:///var/containers/Bundle/Application/8208F81D-9EA4-468F-9CDF-0CBC8B44E8CD/ThaliTest.app/www/index.html
,2016-09-21 04:04:45.162 ThaliTest[1189:1536338] JXcore Cordova plugin initializing
,2016-09-21 04:04:45.162 ThaliTest[1189:1536528] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 04:04:51.669 ThaliTest[1189:1536528] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 04:04:51.669 ThaliTest[1189:1536528] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 04:04:51.669 ThaliTest[1189:1536528] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-21 04:04:51.671 ThaliTest[1189:1536528] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 04:04:52.052 ThaliTest[1189:1536528] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.002632021903991699
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

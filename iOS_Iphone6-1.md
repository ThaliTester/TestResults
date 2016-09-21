#### Test 85960304e9d96a8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/BCF9F97C-A8C4-4EBB-B997-BB9F225E98A4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BCF9F97C-A8C4-4EBB-B997-BB9F225E98A4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7D1A5D3F-C632-45C9-A346-A4E9143B3C9C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55139"
,(lldb)     command script import "/tmp/BCF9F97C-A8C4-4EBB-B997-BB9F225E98A4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 13:04:36.434 ThaliTest[1025:1602346] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/88FB8C7D-3789-4468-B1CF-B680A941888D/Library/Cookies/Cookies.binarycookies
,2016-09-21 13:04:36.744 ThaliTest[1025:1602346] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 13:04:36.746 ThaliTest[1025:1602346] Multi-tasking -> Device: YES, App: YES
,2016-09-21 13:04:36.770 ThaliTest[1025:1602346] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 13:04:37.292 ThaliTest[1025:1602346] Using UIWebView
,2016-09-21 13:04:37.303 ThaliTest[1025:1602346] [CDVTimer][handleopenurl] 0.497997ms
,2016-09-21 13:04:37.310 ThaliTest[1025:1602346] [CDVTimer][intentandnavigationfilter] 7.174015ms
2016-09-21 13:04:37.311 ThaliTest[1025:1602346] [CDVTimer][gesturehandler] 0.322998ms
2016-09-21 13:04:37.312 ThaliTest[1025:1602346] [CDVTimer][TotalPluginStartup] 9.813964ms
,2016-09-21 13:04:42.864 ThaliTest[1025:1602346] Resetting plugins due to page load.
,2016-09-21 13:04:43.186 ThaliTest[1025:1602346] Finished load of: file:///var/containers/Bundle/Application/7D1A5D3F-C632-45C9-A346-A4E9143B3C9C/ThaliTest.app/www/index.html
,2016-09-21 13:04:43.517 ThaliTest[1025:1602346] JXcore Cordova plugin initializing
,2016-09-21 13:04:43.518 ThaliTest[1025:1602547] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 13:04:50.275 ThaliTest[1025:1602547] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 13:04:50.275 ThaliTest[1025:1602547] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 13:04:50.275 ThaliTest[1025:1602547] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 13:04:50.277 ThaliTest[1025:1602547] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 13:04:50.660 ThaliTest[1025:1602547] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003696024417877197
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

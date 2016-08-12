#### Test 81095569d4ae196_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81095569d4ae196/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/61082285-9612-499D-8112-34F8B545291B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/61082285-9612-499D-8112-34F8B545291B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81095569d4ae196/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81095569d4ae196/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0DAE0B5F-BC17-4688-9534-24DF6D49362A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61458"
,(lldb)     command script import "/tmp/61082285-9612-499D-8112-34F8B545291B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,error: libarclite_iphoneos.a(arclite.o) failed to load objfile for /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/libarclite_iphoneos.a
,2016-08-12 12:47:56.312 ThaliTest[212:16570] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/511E95E9-B010-4E57-A541-F5EF6159DE95/Library/Cookies/Cookies.binarycookies
,2016-08-12 12:47:56.885 ThaliTest[212:16570] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-12 12:47:56.886 ThaliTest[212:16570] Multi-tasking -> Device: YES, App: YES
,2016-08-12 12:47:56.912 ThaliTest[212:16570] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-12 12:47:58.951 ThaliTest[212:16570] Using UIWebView
,2016-08-12 12:47:58.958 ThaliTest[212:16570] [CDVTimer][handleopenurl] 0.376046ms
,2016-08-12 12:47:58.966 ThaliTest[212:16570] [CDVTimer][intentandnavigationfilter] 7.502019ms
,2016-08-12 12:47:58.967 ThaliTest[212:16570] [CDVTimer][gesturehandler] 0.329971ms
,2016-08-12 12:47:58.967 ThaliTest[212:16570] [CDVTimer][TotalPluginStartup] 9.746015ms
,2016-08-12 12:48:05.935 ThaliTest[212:16570] Resetting plugins due to page load.
,2016-08-12 12:48:09.356 ThaliTest[212:16570] Finished load of: file:///var/mobile/Containers/Bundle/Application/0DAE0B5F-BC17-4688-9534-24DF6D49362A/ThaliTest.app/www/index.html
,2016-08-12 12:48:09.595 ThaliTest[212:16570] JXcore Cordova plugin initializing
,2016-08-12 12:48:09.596 ThaliTest[212:16829] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-12 12:48:16.031 ThaliTest[212:16829] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-12 12:48:16.031 ThaliTest[212:16829] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-12 12:48:16.032 ThaliTest[212:16829] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-12 12:48:16.033 ThaliTest[212:16829] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-12 12:48:16.289 ThaliTest[212:16829] Native method ExecuteNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```

#### Test 81095569d4ae196_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81095569d4ae196/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/AC416CFC-311A-459B-82AC-F7A81A129563/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AC416CFC-311A-459B-82AC-F7A81A129563/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81095569d4ae196/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81095569d4ae196/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0095B0A1-EFBA-4CCA-B54C-D54E8CF986FE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61462"
,(lldb)     command script import "/tmp/AC416CFC-311A-459B-82AC-F7A81A129563/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,error: libarclite_iphoneos.a(arclite.o) failed to load objfile for /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/libarclite_iphoneos.a
,2016-08-12 12:47:55.679 ThaliTest[205:17435] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3F9C5053-757E-4C7F-8524-3F3C7AB24271/Library/Cookies/Cookies.binarycookies
,2016-08-12 12:47:56.219 ThaliTest[205:17435] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-12 12:47:56.221 ThaliTest[205:17435] Multi-tasking -> Device: YES, App: YES
,2016-08-12 12:47:56.256 ThaliTest[205:17435] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-12 12:47:58.045 ThaliTest[205:17435] Using UIWebView
,2016-08-12 12:47:58.053 ThaliTest[205:17435] [CDVTimer][handleopenurl] 0.328958ms
,2016-08-12 12:47:58.060 ThaliTest[205:17435] [CDVTimer][intentandnavigationfilter] 6.896973ms
2016-08-12 12:47:58.061 ThaliTest[205:17435] [CDVTimer][gesturehandler] 0.302017ms
2016-08-12 12:47:58.061 ThaliTest[205:17435] [CDVTimer][TotalPluginStartup] 8,.983016ms
,2016-08-12 12:48:04.533 ThaliTest[205:17435] Resetting plugins due to page load.
,2016-08-12 12:48:07.623 ThaliTest[205:17435] Finished load of: file:///var/mobile/Containers/Bundle/Application/0095B0A1-EFBA-4CCA-B54C-D54E8CF986FE/ThaliTest.app/www/index.html
,2016-08-12 12:48:07.921 ThaliTest[205:17435] JXcore Cordova plugin initializing
2016-08-12 12:48:07.922 ThaliTest[205:17656] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-12 12:48:16.541 ThaliTest[205:17656] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-12 12:48:16.541 ThaliTest[205:17656] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-12 12:48:16.542 ThaliTest[205:17656] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-12 12:48:16.544 ThaliTest[205:17656] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-12 12:48:16.885 ThaliTest[205:17656] Native method ExecuteNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```

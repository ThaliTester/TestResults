#### Test 850469118f5d139_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469118f5d139/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/81F602C2-E871-4239-9C50-50CD514C7E7C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/81F602C2-E871-4239-9C50-50CD514C7E7C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469118f5d139/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469118f5d139/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E33F75B0-7A75-4643-AB09-183A00737B88/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58029"
,(lldb)     command script import "/tmp/81F602C2-E871-4239-9C50-50CD514C7E7C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 14:01:42.602 ThaliTest[3373:6793554] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/44DBEE85-F26B-4F52-A2A7-40320E2A4AF4/Library/Cookies/Cookies.binarycookies
,2016-09-27 14:01:42.723 ThaliTest[3373:6793554] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 14:01:42.724 ThaliTest[3373:6793554] Multi-tasking -> Device: YES, App: YES
,2016-09-27 14:01:42.745 ThaliTest[3373:6793554] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 14:01:44.300 ThaliTest[3373:6793554] Using UIWebView
,2016-09-27 14:01:44.312 ThaliTest[3373:6793554] [CDVTimer][handleopenurl] 0.533998ms
,2016-09-27 14:01:44.320 ThaliTest[3373:6793554] [CDVTimer][intentandnavigationfilter] 8.337021ms
2016-09-27 14:01:44.321 ThaliTest[3373:6793554] [CDVTimer][gesturehandler] 0.397027ms
2016-09-27 14:01:44.322 ThaliTest[3373:6793554] [CDVTimer][TotalPluginS,tartup] 11.119008ms
,2016-09-27 14:01:50.309 ThaliTest[3373:6793554] Resetting plugins due to page load.
,2016-09-27 14:01:54.158 ThaliTest[3373:6793554] Finished load of: file:///var/mobile/Containers/Bundle/Application/E33F75B0-7A75-4643-AB09-183A00737B88/ThaliTest.app/www/index.html
,2016-09-27 14:01:54.459 ThaliTest[3373:6793554] JXcore Cordova plugin initializing
,2016-09-27 14:01:54.461 ThaliTest[3373:6793800] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x1285e0040>
,Optional("9C5EBCC6-FAB2-46EB-B8EF-618D02B6036D")
,nil
,nil
,Optional("079ED8BC-2CF3-4E0B-9B14-7F4C221AA86C")
,Optional("58C9FB97-3A0D-4B2E-B786-592ECC5CE79E")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  15.38380700349808
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

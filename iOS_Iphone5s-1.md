#### Test 81095569cb9dee4_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81095569cb9dee4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B3968850-F2EE-4342-9CF2-B6B794682905/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B3968850-F2EE-4342-9CF2-B6B794682905/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81095569cb9dee4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81095569cb9dee4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/84EF905A-68E4-4247-8A57-1575AC5419E3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60392"
,(lldb)     command script import "/tmp/B3968850-F2EE-4342-9CF2-B6B794682905/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-23 18:33:43.639 ThaliTest[722:1539660] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3039F182-81CF-473A-92EB-B7504B3BEA34/Library/Cookies/Cookies.binarycookies
,2016-08-23 18:33:44.038 ThaliTest[722:1539660] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-23 18:33:44.039 ThaliTest[722:1539660] Multi-tasking -> Device: YES, App: YES
,2016-08-23 18:33:44.059 ThaliTest[722:1539660] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-23 18:33:45.939 ThaliTest[722:1539660] Using UIWebView
,2016-08-23 18:33:45.946 ThaliTest[722:1539660] [CDVTimer][handleopenurl] 0.438988ms
,2016-08-23 18:33:45.956 ThaliTest[722:1539660] [CDVTimer][intentandnavigationfilter] 8.574009ms
2016-08-23 18:33:45.957 ThaliTest[722:1539660] [CDVTimer][gesturehandler] 0.406981ms
2016-08-23 18:33:45.957 ThaliTest[722:1539660] [CDVTimer][TotalPluginStar,tup] 11.601985ms
,2016-08-23 18:33:53.032 ThaliTest[722:1539660] Resetting plugins due to page load.
,2016-08-23 18:33:56.738 ThaliTest[722:1539660] Finished load of: file:///var/mobile/Containers/Bundle/Application/84EF905A-68E4-4247-8A57-1575AC5419E3/ThaliTest.app/www/index.html
,2016-08-23 18:33:56.998 ThaliTest[722:1539660] JXcore Cordova plugin initializing
,2016-08-23 18:33:57.000 ThaliTest[722:1539878] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-23 18:34:05.160 ThaliTest[722:1539878] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-23 18:34:05.161 ThaliTest[722:1539878] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-23 18:34:05.161 ThaliTest[722:1539878] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-23 18:34:05.163 ThaliTest[722:1539878] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-23 18:34:05.494 ThaliTest[722:1539878] Native method ExecuteNativeTests not found.
Is Android:  false
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```

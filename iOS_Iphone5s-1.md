#### Test 8362733700cd7fa_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8362733700cd7fa/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E6DD352F-B092-4816-AC44-CEC3FEA43711/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E6DD352F-B092-4816-AC44-CEC3FEA43711/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8362733700cd7fa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8362733700cd7fa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5A3D938E-4C1F-4A55-94F2-252983C59783/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54106"
,(lldb)     command script import "/tmp/E6DD352F-B092-4816-AC44-CEC3FEA43711/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 12:55:22.497 ThaliTest[2129:4567983] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CC561C22-19D3-45E2-9671-A046CADE4353/Library/Cookies/Cookies.binarycookies
,2016-09-13 12:55:22.751 ThaliTest[2129:4567983] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 12:55:22.752 ThaliTest[2129:4567983] Multi-tasking -> Device: YES, App: YES
,2016-09-13 12:55:22.772 ThaliTest[2129:4567983] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 12:55:23.591 ThaliTest[2129:4567983] Using UIWebView
,2016-09-13 12:55:23.594 ThaliTest[2129:4567983] [CDVTimer][handleopenurl] 0.262022ms
,2016-09-13 12:55:23.597 ThaliTest[2129:4567983] [CDVTimer][intentandnavigationfilter] 2.789021ms
2016-09-13 12:55:23.597 ThaliTest[2129:4567983] [CDVTimer][gesturehandler] 0.140965ms
2016-09-13 12:55:23.597 ThaliTest[2129:4567983] [CDVTimer][TotalPluginStartup] 3.877997ms
,2016-09-13 12:55:26.708 ThaliTest[2129:4567983] Resetting plugins due to page load.
,2016-09-13 12:55:28.019 ThaliTest[2129:4567983] Finished load of: file:///var/mobile/Containers/Bundle/Application/5A3D938E-4C1F-4A55-94F2-252983C59783/ThaliTest.app/www/index.html
,2016-09-13 12:55:28.223 ThaliTest[2129:4567983] JXcore Cordova plugin initializing
2016-09-13 12:55:28.224 ThaliTest[2129:4568170] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 12:55:36.029 ThaliTest[2129:4568170] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 12:55:36.029 ThaliTest[2129:4568170] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 12:55:36.030 ThaliTest[2129:4,568170] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 12:55:36.032 ThaliTest[2129:4568170] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```

#### Test 8362733795b1a33_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8362733795b1a33/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/96F0F39E-7482-44E4-BC06-2F21F167D1A3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/96F0F39E-7482-44E4-BC06-2F21F167D1A3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8362733795b1a33/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8362733795b1a33/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/286BBEA4-D496-4961-B345-640E37DC3BCB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64774"
,(lldb)     command script import "/tmp/96F0F39E-7482-44E4-BC06-2F21F167D1A3/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 07:07:48.378 ThaliTest[619:648728] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A81D7527-3F3B-46FD-A51B-07795FEB6218/Library/Cookies/Cookies.binarycookies
,2016-09-13 07:07:48.709 ThaliTest[619:648728] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 07:07:48.711 ThaliTest[619:648728] Multi-tasking -> Device: YES, App: YES
,2016-09-13 07:07:48.736 ThaliTest[619:648728] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 07:07:49.276 ThaliTest[619:648728] Using UIWebView
,2016-09-13 07:07:49.283 ThaliTest[619:648728] [CDVTimer][handleopenurl] 0.482976ms
,2016-09-13 07:07:49.291 ThaliTest[619:648728] [CDVTimer][intentandnavigationfilter] 7.332027ms
2016-09-13 07:07:49.291 ThaliTest[619:648728] [CDVTimer][gesturehandler] 0.319958ms
2016-09-13 07:07:49.292 ThaliTest[619:648728] [CDVTimer][TotalPluginStartup] 9.773016ms
,2016-09-13 07:07:54.670 ThaliTest[619:648728] Resetting plugins due to page load.
,2016-09-13 07:07:55.054 ThaliTest[619:648728] Finished load of: file:///var/containers/Bundle/Application/286BBEA4-D496-4961-B345-640E37DC3BCB/ThaliTest.app/www/index.html
,2016-09-13 07:07:55.422 ThaliTest[619:648728] JXcore Cordova plugin initializing
,2016-09-13 07:07:55.423 ThaliTest[619:648922] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 07:08:02.016 ThaliTest[619:648922] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 07:08:02.016 ThaliTest[619:648922] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 07:08:02.016 ThaliTest[619:648922] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 07:08:02.018 ThaliTest[619:648922] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```

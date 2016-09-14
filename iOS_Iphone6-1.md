#### Test 83627337b783869_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/68A48DD7-A0DE-4393-A054-CA2A99547FA5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/68A48DD7-A0DE-4393-A054-CA2A99547FA5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/CAFC4562-3DCB-4976-BA76-BFA97E477C27/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60995"
,(lldb)     command script import "/tmp/68A48DD7-A0DE-4393-A054-CA2A99547FA5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 14:43:38.553 ThaliTest[577:733066] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/36DAF5DF-D0D5-47F8-8406-F5AA3874753D/Library/Cookies/Cookies.binarycookies
,2016-09-14 14:43:38.889 ThaliTest[577:733066] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 14:43:38.891 ThaliTest[577:733066] Multi-tasking -> Device: YES, App: YES
,2016-09-14 14:43:38.910 ThaliTest[577:733066] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 14:43:39.288 ThaliTest[577:733066] Using UIWebView
,2016-09-14 14:43:39.295 ThaliTest[577:733066] [CDVTimer][handleopenurl] 0.501990ms
,2016-09-14 14:43:39.302 ThaliTest[577:733066] [CDVTimer][intentandnavigationfilter] 6.421983ms
2016-09-14 14:43:39.303 ThaliTest[577:733066] [CDVTimer][gesturehandler] 0.231028ms
2016-09-14 14:43:39.303 ThaliTest[577:733066] [CDVTimer][TotalPluginStartup] 8.473992ms
,2016-09-14 14:43:45.375 ThaliTest[577:733066] Resetting plugins due to page load.
,2016-09-14 14:43:45.662 ThaliTest[577:733066] Finished load of: file:///var/containers/Bundle/Application/CAFC4562-3DCB-4976-BA76-BFA97E477C27/ThaliTest.app/www/index.html
,2016-09-14 14:43:45.998 ThaliTest[577:733066] JXcore Cordova plugin initializing
,2016-09-14 14:43:45.999 ThaliTest[577:733266] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 14:43:52.652 ThaliTest[577:733266] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 14:43:52.652 ThaliTest[577:733266] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 14:43:52.652 ThaliTest[577:733266] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 14:43:52.655 ThaliTest[577:733266] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```

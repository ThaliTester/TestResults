#### Test 83627337a1c904e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337a1c904e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5108DD68-3A03-43B6-842A-5E95C6AF324F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5108DD68-3A03-43B6-842A-5E95C6AF324F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337a1c904e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337a1c904e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/764298B3-E7B5-498A-AD12-A53C6ABBA569/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61435"
,(lldb)     command script import "/tmp/5108DD68-3A03-43B6-842A-5E95C6AF324F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 09:32:59.966 ThaliTest[1855:3477391] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9813C178-BAB8-45ED-A057-AE5478C6D17F/Library/Cookies/Cookies.binarycookies
,2016-09-07 09:33:00.204 ThaliTest[1855:3477391] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 09:33:00.205 ThaliTest[1855:3477391] Multi-tasking -> Device: YES, App: YES
,2016-09-07 09:33:00.218 ThaliTest[1855:3477391] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 09:33:01.022 ThaliTest[1855:3477391] Using UIWebView
,2016-09-07 09:33:01.024 ThaliTest[1855:3477391] [CDVTimer][handleopenurl] 0.110984ms
,2016-09-07 09:33:01.026 ThaliTest[1855:3477391] [CDVTimer][intentandnavigationfilter] 1.887977ms
2016-09-07 09:33:01.027 ThaliTest[1855:3477391] [CDVTimer][gesturehandler] 0.083983ms
2016-09-07 09:33:01.027 ThaliTest[1855:3477391] [CDVTimer][TotalPluginStartup] 2.520978ms
,2016-09-07 09:33:04.053 ThaliTest[1855:3477391] Resetting plugins due to page load.
,2016-09-07 09:33:05.302 ThaliTest[1855:3477391] Finished load of: file:///var/mobile/Containers/Bundle/Application/764298B3-E7B5-498A-AD12-A53C6ABBA569/ThaliTest.app/www/index.html
,2016-09-07 09:33:05.437 ThaliTest[1855:3477391] JXcore Cordova plugin initializing
,2016-09-07 09:33:05.438 ThaliTest[1855:3477560] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 09:33:11.272 ThaliTest[1855:3477560] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-07 09:33:11.273 ThaliTest[1855:3477560] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-07 09:33:11.273 ThaliTest[1855:3477560] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-07 09:33:11.275 ThaliTest[1855:3477560] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```

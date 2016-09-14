#### Test 836273373ce2df7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273373ce2df7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8577D2E9-5C50-4681-8382-F0397E9CDF37/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8577D2E9-5C50-4681-8382-F0397E9CDF37/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273373ce2df7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273373ce2df7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/57F06626-6F15-4CEC-9194-DBEFCB33BA11/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51015"
,(lldb)     command script import "/tmp/8577D2E9-5C50-4681-8382-F0397E9CDF37/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 12:08:29.400 ThaliTest[2290:4394419] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0A094479-2C6E-4C9A-AD2B-3161E1466075/Library/Cookies/Cookies.binarycookies
,2016-09-14 12:08:29.836 ThaliTest[2290:4394419] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 12:08:29.838 ThaliTest[2290:4394419] Multi-tasking -> Device: YES, App: YES
,2016-09-14 12:08:29.856 ThaliTest[2290:4394419] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 12:08:31.711 ThaliTest[2290:4394419] Using UIWebView
,2016-09-14 12:08:31.718 ThaliTest[2290:4394419] [CDVTimer][handleopenurl] 0.388980ms
,2016-09-14 12:08:31.725 ThaliTest[2290:4394419] [CDVTimer][intentandnavigationfilter] 6.898999ms
,2016-09-14 12:08:31.726 ThaliTest[2290:4394419] [CDVTimer][gesturehandler] 0.351012ms
,2016-09-14 12:08:31.727 ThaliTest[2290:4394419] [CDVTimer][TotalPluginStartup] 9.239018ms
,2016-09-14 12:08:38.446 ThaliTest[2290:4394419] Resetting plugins due to page load.
,2016-09-14 12:08:42.719 ThaliTest[2290:4394419] Finished load of: file:///var/mobile/Containers/Bundle/Application/57F06626-6F15-4CEC-9194-DBEFCB33BA11/ThaliTest.app/www/index.html
,2016-09-14 12:08:42.925 ThaliTest[2290:4394419] JXcore Cordova plugin initializing
,2016-09-14 12:08:42.926 ThaliTest[2290:4394672] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 12:08:49.118 ThaliTest[2290:4394672] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 12:08:49.118 ThaliTest[2290:4394672] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-14 12:08:49.119 ThaliTest[2290:4394672] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 12:08:49.120 ThaliTest[2290:4394672] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```

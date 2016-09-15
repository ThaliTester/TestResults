#### Test 83276082be030e3_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83276082be030e3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9DBD5E62-A394-4F1C-B922-AAA3FAF2990D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9DBD5E62-A394-4F1C-B922-AAA3FAF2990D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83276082be030e3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83276082be030e3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E9FDBBFC-A5A7-4164-8CFF-7D4E24558C86/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55432"
,(lldb)     command script import "/tmp/9DBD5E62-A394-4F1C-B922-AAA3FAF2990D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 10:02:40.372 ThaliTest[2405:4520259] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E8716F2A-8119-40A6-A4A0-DE2B229AE32E/Library/Cookies/Cookies.binarycookies
,2016-09-15 10:02:40.762 ThaliTest[2405:4520259] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 10:02:40.764 ThaliTest[2405:4520259] Multi-tasking -> Device: YES, App: YES
,2016-09-15 10:02:40.783 ThaliTest[2405:4520259] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 10:02:42.624 ThaliTest[2405:4520259] Using UIWebView
,2016-09-15 10:02:42.631 ThaliTest[2405:4520259] [CDVTimer][handleopenurl] 0.398993ms
,2016-09-15 10:02:42.638 ThaliTest[2405:4520259] [CDVTimer][intentandnavigationfilter] 6.652951ms
,2016-09-15 10:02:42.639 ThaliTest[2405:4520259] [CDVTimer][gesturehandler] 0.440001ms
2016-09-15 10:02:42.640 ThaliTest[2405:4520259] [CDVTimer][TotalPluginStartup] 9.223044ms
,2016-09-15 10:02:49.074 ThaliTest[2405:4520259] Resetting plugins due to page load.
,2016-09-15 10:02:52.688 ThaliTest[2405:4520259] Finished load of: file:///var/mobile/Containers/Bundle/Application/E9FDBBFC-A5A7-4164-8CFF-7D4E24558C86/ThaliTest.app/www/index.html
,2016-09-15 10:02:52.900 ThaliTest[2405:4520259] JXcore Cordova plugin initializing
,2016-09-15 10:02:52.901 ThaliTest[2405:4520521] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 10:02:59.038 ThaliTest[2405:4520521] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 10:02:59.038 ThaliTest[2405:4520521] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-15 10:02:59.039 ThaliTest[2405:4520521] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-15 10:02:59.040 ThaliTest[2405:4520521] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```

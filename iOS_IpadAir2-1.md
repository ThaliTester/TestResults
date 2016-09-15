#### Test 83276082d331142_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/CE8A73F1-2AD4-48B5-A486-9D4AEB6B625A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CE8A73F1-2AD4-48B5-A486-9D4AEB6B625A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/381E66E0-CC10-449B-9C69-59BFFB63691B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49931"
,(lldb)     command script import "/tmp/CE8A73F1-2AD4-48B5-A486-9D4AEB6B625A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 13:29:38.369 ThaliTest[2436:4540718] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4C36958D-6536-4503-82B3-B802A22E06D8/Library/Cookies/Cookies.binarycookies
,2016-09-15 13:29:38.772 ThaliTest[2436:4540718] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 13:29:38.773 ThaliTest[2436:4540718] Multi-tasking -> Device: YES, App: YES
,2016-09-15 13:29:38.792 ThaliTest[2436:4540718] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 13:29:40.653 ThaliTest[2436:4540718] Using UIWebView
,2016-09-15 13:29:40.661 ThaliTest[2436:4540718] [CDVTimer][handleopenurl] 0.791013ms
,2016-09-15 13:29:40.669 ThaliTest[2436:4540718] [CDVTimer][intentandnavigationfilter] 7.472992ms
,2016-09-15 13:29:40.670 ThaliTest[2436:4540718] [CDVTimer][gesturehandler] 0.382960ms
2016-09-15 13:29:40.670 ThaliTest[2436:4540718] [CDVTimer][TotalPluginStartup] 10.715008ms
,2016-09-15 13:29:47.391 ThaliTest[2436:4540718] Resetting plugins due to page load.
,2016-09-15 13:29:50.927 ThaliTest[2436:4540718] Finished load of: file:///var/mobile/Containers/Bundle/Application/381E66E0-CC10-449B-9C69-59BFFB63691B/ThaliTest.app/www/index.html
,2016-09-15 13:29:51.121 ThaliTest[2436:4540718] JXcore Cordova plugin initializing
,2016-09-15 13:29:51.122 ThaliTest[2436:4540980] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 13:29:57.286 ThaliTest[2436:4540980] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-15 13:29:57.286 ThaliTest[2436:4540980] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-15 13:29:57.286 ThaliTest[2436:4540980] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-15 13:29:57.288 ThaliTest[2436:4540980] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```

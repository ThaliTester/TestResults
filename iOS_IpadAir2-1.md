#### Test 83627337b783869_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7DADB1A1-70B6-4264-9D6F-EC881FF4E767/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7DADB1A1-70B6-4264-9D6F-EC881FF4E767/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337b783869/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E7243D56-9546-4337-A8C0-44F4A787210C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60994"
,(lldb)     command script import "/tmp/7DADB1A1-70B6-4264-9D6F-EC881FF4E767/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 14:43:42.706 ThaliTest[2300:4408438] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/75C4B76B-05B1-4FEE-AF44-4D5798C0DFC5/Library/Cookies/Cookies.binarycookies
,2016-09-14 14:43:43.100 ThaliTest[2300:4408438] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 14:43:43.101 ThaliTest[2300:4408438] Multi-tasking -> Device: YES, App: YES
,2016-09-14 14:43:43.120 ThaliTest[2300:4408438] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 14:43:45.173 ThaliTest[2300:4408438] Using UIWebView
,2016-09-14 14:43:45.183 ThaliTest[2300:4408438] [CDVTimer][handleopenurl] 0.384986ms
,2016-09-14 14:43:45.190 ThaliTest[2300:4408438] [CDVTimer][intentandnavigationfilter] 6.715953ms
,2016-09-14 14:43:45.191 ThaliTest[2300:4408438] [CDVTimer][gesturehandler] 0.306964ms
,2016-09-14 14:43:45.191 ThaliTest[2300:4408438] [CDVTimer][TotalPluginStartup] 8.935988ms
,2016-09-14 14:43:52.139 ThaliTest[2300:4408438] Resetting plugins due to page load.
,2016-09-14 14:43:56.208 ThaliTest[2300:4408438] Finished load of: file:///var/mobile/Containers/Bundle/Application/E7243D56-9546-4337-A8C0-44F4A787210C/ThaliTest.app/www/index.html
,2016-09-14 14:43:56.417 ThaliTest[2300:4408438] JXcore Cordova plugin initializing
,2016-09-14 14:43:56.418 ThaliTest[2300:4408683] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 14:44:02.591 ThaliTest[2300:4408683] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-14 14:44:02.591 ThaliTest[2300:4408683] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-14 14:44:02.591 ThaliTest[2300:4408683] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 14:44:02.593 ThaliTest[2300:4408683] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```

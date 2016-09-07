#### Test 83627337941f206_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337941f206/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E175A8FF-B943-4B1E-A82B-49B108A874B7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E175A8FF-B943-4B1E-A82B-49B108A874B7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337941f206/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337941f206/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/15A41A7A-7176-4CC0-BC23-79CF62974A1E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51043"
,(lldb)     command script import "/tmp/E175A8FF-B943-4B1E-A82B-49B108A874B7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 12:31:34.203 ThaliTest[1893:3498627] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8252DE33-C863-4874-8651-4929BA081DFB/Library/Cookies/Cookies.binarycookies
,2016-09-07 12:31:34.453 ThaliTest[1893:3498627] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 12:31:34.454 ThaliTest[1893:3498627] Multi-tasking -> Device: YES, App: YES
,2016-09-07 12:31:34.467 ThaliTest[1893:3498627] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 12:31:35.274 ThaliTest[1893:3498627] Using UIWebView
,2016-09-07 12:31:35.276 ThaliTest[1893:3498627] [CDVTimer][handleopenurl] 0.117004ms
,2016-09-07 12:31:35.278 ThaliTest[1893:3498627] [CDVTimer][intentandnavigationfilter] 1.847982ms
2016-09-07 12:31:35.278 ThaliTest[1893:3498627] [CDVTimer][gesturehandler] 0.083029ms
2016-09-07 12:31:35.278 ThaliTest[1893:3498627] [CDVTimer][TotalPluginStartup] 2.497017ms
,2016-09-07 12:31:38.326 ThaliTest[1893:3498627] Resetting plugins due to page load.
,2016-09-07 12:31:39.729 ThaliTest[1893:3498627] Finished load of: file:///var/mobile/Containers/Bundle/Application/15A41A7A-7176-4CC0-BC23-79CF62974A1E/ThaliTest.app/www/index.html
,2016-09-07 12:31:39.863 ThaliTest[1893:3498627] JXcore Cordova plugin initializing
2016-09-07 12:31:39.864 ThaliTest[1893:3498801] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 12:31:45.697 ThaliTest[1893:3498801] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-07 12:31:45.698 ThaliTest[1893:3498801] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-07 12:31:45.698 ThaliTest[1893:3498801] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-07 12:31:45.700 ThaliTest[1893:3498801] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```

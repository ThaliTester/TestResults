#### Test 83627337381d561_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337381d561/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6290FE01-56E9-4841-8967-B01D341F2343/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6290FE01-56E9-4841-8967-B01D341F2343/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337381d561/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337381d561/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/09A223EC-160A-485D-8A48-36329DC75765/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64525"
,(lldb)     command script import "/tmp/6290FE01-56E9-4841-8967-B01D341F2343/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 11:35:30.583 ThaliTest[1876:3491459] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D6F6DFF1-F418-4489-81F4-0F69D36B109A/Library/Cookies/Cookies.binarycookies
,2016-09-07 11:35:30.839 ThaliTest[1876:3491459] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 11:35:30.840 ThaliTest[1876:3491459] Multi-tasking -> Device: YES, App: YES
,2016-09-07 11:35:30.853 ThaliTest[1876:3491459] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 11:35:31.704 ThaliTest[1876:3491459] Using UIWebView
,2016-09-07 11:35:31.706 ThaliTest[1876:3491459] [CDVTimer][handleopenurl] 0.117958ms
,2016-09-07 11:35:31.708 ThaliTest[1876:3491459] [CDVTimer][intentandnavigationfilter] 1.931965ms
2016-09-07 11:35:31.708 ThaliTest[1876:3491459] [CDVTimer][gesturehandler] 0.083029ms
2016-09-07 11:35:31.708 ThaliTest[1876:3491459] [CDVTimer][TotalPluginStartup] 2.591014ms
,2016-09-07 11:35:34.962 ThaliTest[1876:3491459] Resetting plugins due to page load.
,2016-09-07 11:35:36.448 ThaliTest[1876:3491459] Finished load of: file:///var/mobile/Containers/Bundle/Application/09A223EC-160A-485D-8A48-36329DC75765/ThaliTest.app/www/index.html
,2016-09-07 11:35:36.586 ThaliTest[1876:3491459] JXcore Cordova plugin initializing
2016-09-07 11:35:36.586 ThaliTest[1876:3491649] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 11:35:42.447 ThaliTest[1876:3491649] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-07 11:35:42.447 ThaliTest[1876:3491649] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-07 11:35:42.448 ThaliTest[1876:3,491649] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-07 11:35:42.449 ThaliTest[1876:3491649] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```

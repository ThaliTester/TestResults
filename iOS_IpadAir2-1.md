#### Test 83627337e0b549f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337e0b549f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/6FB84045-26EC-4CFA-B761-289F0E329820/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6FB84045-26EC-4CFA-B761-289F0E329820/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337e0b549f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337e0b549f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/318B0A23-92DA-4ADC-9546-F28BB229D02C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57611"
,(lldb)     command script import "/tmp/6FB84045-26EC-4CFA-B761-289F0E329820/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-14 09:26:40.360 ThaliTest[2276:4379546] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7FF9F552-6434-4EB0-8682-8716C71CB5A8/Library/Cookies/Cookies.binarycookies
,2016-09-14 09:26:40.815 ThaliTest[2276:4379546] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 09:26:40.817 ThaliTest[2276:4379546] Multi-tasking -> Device: YES, App: YES
,2016-09-14 09:26:40.836 ThaliTest[2276:4379546] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 09:26:42.755 ThaliTest[2276:4379546] Using UIWebView
,2016-09-14 09:26:42.762 ThaliTest[2276:4379546] [CDVTimer][handleopenurl] 0.455022ms
,2016-09-14 09:26:42.770 ThaliTest[2276:4379546] [CDVTimer][intentandnavigationfilter] 7.395029ms
,2016-09-14 09:26:42.771 ThaliTest[2276:4379546] [CDVTimer][gesturehandler] 0.388980ms
2016-09-14 09:26:42.772 ThaliTest[2276:4379546] [CDVTimer][TotalPluginStartup] 9.979963ms
,2016-09-14 09:26:49.324 ThaliTest[2276:4379546] Resetting plugins due to page load.
,2016-09-14 09:26:53.101 ThaliTest[2276:4379546] Finished load of: file:///var/mobile/Containers/Bundle/Application/318B0A23-92DA-4ADC-9546-F28BB229D02C/ThaliTest.app/www/index.html
,2016-09-14 09:26:53.320 ThaliTest[2276:4379546] JXcore Cordova plugin initializing
,2016-09-14 09:26:53.321 ThaliTest[2276:4379797] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 09:26:59.484 ThaliTest[2276:4379797] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-14 09:26:59.484 ThaliTest[2276:4379797] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 09:26:59.484 ThaliTest[2276:4379797] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 09:26:59.486 ThaliTest[2276:4379797] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
